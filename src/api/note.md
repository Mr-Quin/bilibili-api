*Note to self:*

The api uses some sort of directed graph structure.

Each node has an action method that takes a payload and returns some data.

Getting data from a node means recursively finding its root, calling "get" on the root, and passing the returned data to each children node until it reaches the entry point node.
 
