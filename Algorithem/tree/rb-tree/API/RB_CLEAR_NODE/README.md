RB_CLEAR_NODE [中文教程](https://biscuitos.github.io/blog/RBTREE_RB_CLEAR_NODE/)
----------------------------------

```
RB-Tree

                                                       [] Black node
                                                       () Red node
                   [4]
                    |
         o----------o----------o
         |                     |
        (2)                   (7)
         |                     |
  o------o------o      o-------o-------o
  |             |      |               |             
 [1]           [3]    [5]             [9]
                                       |
                               o-------o-------o
                               |               |
                              (8)            (129)
```

## Context:

Remove rb_node from RBTree from rb_erase().


* Driver Files: rbtree.c

## Usage

Copy Driver Files into `/drivers/xxx/`, and modify Makefile on current 
directory, as follow:

```
obj-$(CONFIG_RBTREE_XX) += rbtree.o
```

Then, compile driver or dts. Details :

```
make
```

## Running

Packing image and runing on the target board.
