## NHS Bodycam
1. This is a edit of another bodycam to fit uk servers.
This is very good for RP and people who stream to show that you have a body camera ect!


## INSTALL INSTRUCTIONS
1. Go to qb-core/shared/items.lua:

	Paste this
```lua
	["bodycam"] 		 			 = {["name"] = "bodycam",       	    	["label"] = "Body Camera",	 				["weight"] = 20, 		["type"] = "item", 		["image"] = "bodycam.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   ["combinable"] = nil,   ["description"] = "Body Camera"},
```

2. Configure the script to your liking in qb-NHSbodycam/config.lua

3. Add qb-NHSbodycam/img to qb-inventory/html/img

4. Add as your last resource in your server.cfg "ensure qb-NHSbodycam"

5. You can also add it to your NHS armory so workers can grab it more easily!


6. Add This To [qb]/qb-ambulancejob/config.lua >>> Config.Items

```lua
        [7] = {
            name = "bodycam",
            price = 50,
            amount = 1,
            info = {},
            type = "item",
            slot = 7,
        },
```



## PREVIEW

![Image](https://capy-cdn.xyz/3kWYoZlbLPMS.png)



##




This script is a edit of [Dog-Bodycam](https://github.com/BobyTheDev/dog-bodycam)
