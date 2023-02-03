# abimm-lottogame
[standalone] Script FiveM Lotto Game 

#Make sure you using qbcoreframework
qbCore framework:  (https://github.com/qbcore-framework)

## Setup
1. ensure abimm-lottogame at server.cfg
2. copy paste **lotto.png** in inventory/html/images folder
3. add see below to you shared.lua


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
 
## Image Lotto

![alt text](https://github.com/abimmxd/abimm-lottogame/blob/main/lotto.png)

