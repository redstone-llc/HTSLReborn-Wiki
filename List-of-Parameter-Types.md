## String

A collection of characters. If the value includes a space, use quotes around the whole thing.

## Number

A number. Can always be a whole number (suffix `W`, can sometimes be a decimal number (suffix `D`) depending on the action/parameter. 

## Value

Either a number or a string

## Boolean

Either `true` or `false`

## Action

An HTSL action

## Item Path

A path to an item's NBT file. This is relative to the script file. Preferably surround in quotes, especially if it includes a space.

## Assignment Operator

One of the following:

* **Set:** `set`, `=`
* **Add:** `inc`, `+=`
* **Subtract:** `dec`, `-=`
* **Multiply:** `mult`, `*=`
* **Divide:** `div`, `/=`, `//=`
* Advanced Operations (make sure this it toggled on in any conditions menu)
  * **Bitwise And:** `and`, `&=`
  * **Bitwise Or:** `or`, `|=`
  * **Left Shift:** `leftShift`, `shl`, `<<=`
  * **Arithmetic Right Shift:** `arithmeticRightShift`, `shr`, `>>=`
  * **Logical Right Shift:** `logicalRightShift`, `lshr`, `>>>=`

## Conditional Operator

One of the following:

* **Equals:** `equals`, `==`
* **Less Than:** `lessThan`, `<`
* **Less Than or Equal:** `lessThanOrEquals`, `<=`
* **Greater Than:** `greaterThan`, `>`
* **Greater Than or Equal:** `greaterThanOrEquals`, `>=`

## Location

One of the following:

* **House Spawn:** `house_spawn`
* **Current Location:** `current_location`
* **Invoker's Location:** `invokers_location`
* **Custom Coordinates:** `custom_coordinates "<x> <y> <z> [yaw] [pitch]"`
