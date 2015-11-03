Learn You A Haskell
===================

Temporary repo used while learning Haskell syntax.
Following [learnyouahaskell.com](http://learnyouahaskell.com).

Summary
-------

#### Basics
    + * - /
    && || not
    == /=

    succ x
    min x y
    max x y

### If-else
    x = (if x > y then x else y)

### Lists
    [1,2,3,4] ++ [5,6,7,8]
    4:[5,6,7] % Cons operator
    [1,2,3,4] !! 2 => 3
Lists are compared in lexicographical order.

Basic list functions:
* head
* tail
* last
* init
* length
* null
* reverse
* take
* drop
* maximum
* minimum
* sum
* product
* elem
* cycle
* repeat
* replicate

#### Ranges
    [1..20]
    ['A'..'Z']
    ['A','C'..'Z']

#### Sets
    [x*2 | x <- [1..10], x*2 >= 12, x/= 7]
    [ x*y | x <- [2,5,10], y <- [8,10,11], x*y > 50]

#### Tuples
    [("John","Doe",55),("Keith","Richards",99)]

On pairs
* fst
* snd


