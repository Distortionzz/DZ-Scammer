## Distortionz_z ( DZ-Scammer ) (.Lua Beginner Scripter) Made in - 5/1/2023 - Visual Studio Code ##

Intended for FiveM - (Gta5 Mod)


Where to find me!
Discord: Distortionz_z#5314

## Installation ##

- Requried Dependecies (( Note: Script Wont work correctly without the required dependecies ))
    1. Latest QBCore Framework (Link: https://github.com/qbcore-framework/qb-core.git )
    2. Latest QB-Target (Link: https://github.com/qbcore-framework/qb-target.git )
    3. Latest QB-Progressbar (Link: https://github.com/qbcore-framework/progressbar.git ) 

- Required install Items for qb-core -
    1. Forged Documents
    2. Mastercard

- Steps for installing the items
    1. Go to "qb" folder
    2. Go to "Shared" folder
    3. Go to "items.lua" file
    4. Add the following code in a new section.
        
        -- DZ-Scammer Items
    	['forgedocument'] 			 = {['name'] = 'forgedocuments', 				['label'] = 'Fake Documents', 		['weight'] = 100, 		['type'] = 'item', 		['image'] = 'forgedocuments.png', 		['unique'] = true, 		['useable'] = true, 	['shouldClose'] = false,	   ['combinable'] = nil,   ['description'] = 'A folder containg forge card documents.'},
        ['mastercard'] 				 = {['name'] = 'mastercard', 				    ['label'] = 'Master Card', 			['weight'] = 0, 		['type'] = 'item', 		['image'] = 'mastercard.png', 			['unique'] = true, 		['useable'] = true, 	['shouldClose'] = false,       ['combinable'] = nil,   ['description'] = 'MasterCard can be used via ATM'},
    5. Add the "image" to your Inventory images.
    6. Open server.cfj and ensure DZ-SCAMMER
    7. Done ! Enjoy!


## Stay in touch with my github! ##
Link: https://github.com/Distortionzz        
