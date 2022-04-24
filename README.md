# Linear congruential generator
## Example
```scala
local LCG gen = LCG.create(-1) // -1 for random seed
local real r = gen.real(-1, 3) // --> [-1., 3.]
local integer i = gen.integer(-10, 20) // --> [-10, 20]
```