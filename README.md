# abimm-lottogame
[standalone] Script FiveM Lotto Game 

#Make sure you using qbcoreframework
qbCore framework:  (https://github.com/abimmxd/qb-core)

## Setup
1. ensure abimm-lottogame at server.cfg
2. copy paste **lotto.png** in inventory/html/images folder
3 add see below to you shared.lua


```
["lotto"] = {
  ["name"] = "lotto",
  ["label"] = "Lotto ticket",
  ["weight"] = 10,
  ["type"] = "item", 
  ["image"] = "lotto.png",
  ["unique"] = false, 
  ["useable"] = true, 
  ["shouldClose"] = true,  
  ["combinable"] = nil,  
  ["description"] = "Lucky Ticket"},
 ```
 
## Win screen
https://media.giphy.com/media/tupEdbE0QE6USnbZsr/source.gif

## Lost screen
https://media.giphy.com/media/l1Kx74oMJweCiFZOL6/source.gif

