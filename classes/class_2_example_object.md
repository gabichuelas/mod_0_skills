# instance: table_1 #

## attributes ##

`seat_capacity` = 4

`seats_available` = 4

`has_service` = false

`order` = { 1: dish1, 2: dish2, 3: dish3, 4: dish4 }

`server` => name

## Methods ##

`remove_chair(1)` => `seat_capacity` is now 3

`seat_table(3)` => `seats_available` is now 1

`assign_server("Wendy")` => makes `has_service` true, and `server` is now "Wendy"

`take_order` => replaces dish# variables in hash with dish name string
