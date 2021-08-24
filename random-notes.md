These are just some random ideas/concepts about how this thing should work, nothing to see here

**State machines:**
treefarm: walk around, mine every tree, plant saplings, store/burn excess wood
mine: descend, mine stuff, bring stuff back
build: clear area below farm, make walls, place chests

1st turtle (master): treefarm -> get "some" fuel -> create room -> treefarm until "enough" fuel -> mine for 2nd and 3rd turtle resources -> create other 2 turtles -> treefarm only
2nd turtle: mine -> store -> refuel -> mine

3rd turtle(?): empty buffer chest to store stuff, smelt stored items

Room layout: 7x7, 3 tall, solid walls, one wall has 14 double chests
C: chests, X: elevator shaft, O: reserved "empty" space, T: Torch, R: reserved robot space, F: Furnaces on top of eachother

O O O F R C C
O O O O R C C
O O O T R C C
O O T X R C C
O O O T R C C
O O O O R C C
O O O F R C C

Room resources:
chests require 2x2x7x8 = 224 wood planks
furnaces require 2x3x8 = 48 stone
3 torches: 2 planks and 1 coal

Vertical movement only allowed in elevator shaft
Random thrash gets thrown somewhere?
