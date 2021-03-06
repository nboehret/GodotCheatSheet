# GodotCheatSheet

## Nodes

### [Get Node](https://docs.godotengine.org/en/stable/classes/class_node.html#class-node-method-get-node)

![image](https://user-images.githubusercontent.com/82972366/156904914-1eee412f-7acb-4e24-ba3d-f742b8bffdfa.png)

Reference the above Label from the script under the Control Node like `$VSplitContainer/Label`

Example usage: `$VSplitContainer/Label.text = 'Hello'`

Same as: `get_node("VSplitContainer/Label").text = 'Hello'`

## Arrays

### Basics

#### Declare

`var arr = []`

#### Append

`arr.append(1)`

#### Loop

`for item in arr:`

## Strings

### Basics

#### Declare

`var s = 'string variable'`

#### String Contains Value

`if 'string' in 'string variable' or 'string' in s:`

## UI / Control Nodes

### Expand to fill Vertical or Horizontal

A child needs to have the `Size_Flags` set to expand and its parent needs to as well. This is true for parents up the tree unless they already are filling a space in the case of some control items
