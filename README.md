### The Decent Hexagon

This is the docs for py_machine(https://pypi.org/project/py-machine-The-Hexagon/), it will go over what you can do with it.

### docs
## py_machine.Level(width, height)
this creates a level object which you can add and remove cells from

# py_machine.Level.repr(self)
it returns the level code for that level object, repr is what happens when you call print(py_machine.Level)

# py_machine.Level.add_description(self, description)
sets the description of the level

# py_machine.Level.add_cell(self, cell)
puts a cell into its ```self.cells``` list

# py_machine.Level.add_placeable(self, placeable)
puts a placeable into its ```self.placeables``` list

# py_machine.Level.remove_object(self, x, y)
removes all placeables and cells from that x and y coordinates


## py_machine.Cell(x, y, type, angle)
creates a cell with those values

## py_machine.GeneratorCell(x, y, angle)
creates a GeneratorCell with those values

## py_machine.CWRotatorCell(x, y, angle)
creates a CWRotatorCell with those values

## py_machine.CCWRotatorCell(x, y, angle)
creates a CCWRotatorCell cell with those values

## py_machine.MoveCell(x, y, angle)
creates a MoveCell with those values

## py_machine.SlideCell(x, y, angle)
creates a SlideCell with those values

## py_machine.PushCell(x, y, angle)
creates a PushCell with those values

## py_machine.ImmobileCell(x, y, angle)
creates a ImmobileCell with those values

## py_machine.EnemyCell(x, y, angle)
creates a EnemyCell with those values

## py_machine.TrashCell(x, y, angle)
creates a TrashCell with those values

## py_machine.Placeable(x, y)
creates a Placeable with those values

## py_machine.b74intdecode(text)
decodes a base 74 number

## py_machine.b74intencode(text)
encodes a base 74 number
