# instance: pint_glass #

## attributes ##

`is_clean` = false <br>
`material` = "glass" (string)<br>
`is_broken` = false<br>
`oz_in_glass` = 0 (integer/float)

## Methods ##

`pint_glass.wash` => true

`pint_glass.get_material` => "glass"

`pint_glass.throw` => true

`pint_glass.pour_drink(oz)` => `oz_in_glass += oz`

`pint_glass.spill_drink(oz)` => `oz_in_glass -= oz`
