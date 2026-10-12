# Blocky

A module that makes using a Blockpad block as a function easier. 

## Syntax

### ApplyBlock
Blocky.ApplyBlock(block,inputs,values)

This function takes a block (either a block defined in your file or a block from the library), a vector of the input names and a corresponding vector of the input values, and returns a key-value dictionary that can be queried for output values.

### ArrayToDict
Blocky.ArrayToDict(array)

This function takes a 2D array, where the first column contains the keys and the second column contains the values, and returns a native Blockpad key-value dictionary structure.
The reverse of this is the built-in Library.Scripts.KeysAndValues function. This function is used internally by Blocky.ApplyBlock

## Example
See Blocky.bpad for the module and an example report explaining how to use it.

