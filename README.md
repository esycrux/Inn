## Pirate
have Name, Hp, AlcoholLevel and list of drinks

When you creating instance of pirate, you can specify gold ammount, If you dont specify it, it should get random value between 10 - 30

ToString method should return text in this format  "Im Esy, I had x drinks.""

After pirate buys a drink you should incerase alcohol level by 2 for beer by 6 for rum.

he should have Drink method that print message into conosle
	if alhocol level is under 15 he will yell "Cheers, and he drink his {drink}" 
	in that case use name of the latest drink he bought
	
	if pirate doesn have any drink he will yell "Gimee that booze!"
	
	if his alcohol level is over 15 he will yell "Yaaaaaarrrr"

### Captain

His gold ammount is doubled from starting ammount

His alcohol resilience is better, alcohol level is incerased only by half comapred to normal pirate.

He have method GrabDrink whitch should accept pirate as an argument and steal his last ordered drink and drink it



## Inn Class
It should have list of all pirates

It should have method JoinParty taking pirate as an argument.
	Ther should be only one captain in Inn
	pirate will be added to pirate list in this Inn

it should have SellDrink method which take operate as an argument.
	If pirate have more than 20 gold he will receive Rum and will decrase his gold count by 5
	If pirate have less than 20 gold, he should receive beer and will cost him 2 golds
	If pirate have less than 2 gold, bartender only shout on him

It should have method GetSummary which return count for every drink pirates in this inn have in this format
	{ rum: 3}
	{ beer: 7}

It should have method GetSum with optional parameter pirate
	If you pass pirate return cost of the Drink he had
	If you use it withou paramater count cost for all drinks for all pirates

It should have method OneMoreRound when all pirates buy a drink

It should have method PArty method. in this method pirate will spend all their money and buy drink. After every round they will drink drink.
	There is 50% chance the captain will use GrabDrink method to a random pirate
