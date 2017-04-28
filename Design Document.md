#Corporation design document
##UI
###corperations window
####tabs
#####corpate listings 
.listing of all corperations(name,product,trading from:to)
	modify nationalised corporation - opens modify corporation window
	close nationalised corporation - close nationalised corporation window
.tick box: show only nationalised corporations (player started)
.button: create a new corperation - opens new corporation window
.Filter by: product, trading to, trading from

#####corpate taxes
.general tax listing: taxs by product
	modify tax value - opens modify tax value window
.boarder tariff listing: taxes specified by the player for foriegn trading
	modify tax value - opens modify boarder tariff  window
	delete tax - opens delete tax window
.button: create new boarder tariff - opens new boarder tariff window

#####corpate contributions
.energy credits
.minerals
.food
.listing of research contributions(research type, contribution amount)
.(every corporation contributes 0.1 - 1% research boost for the research type releated to the product they trade)
#####lobbying(coroprations can lobby for tax reductions in return for influcence)
.listing of lobbying groups(group name, for(product,boarder from, boarder to), value)
					delete tax reduction - opens delete tax reduction window
					
####dialogue windows
#####new nationalised corporation
name,product, energy credit funding

#####edit nationalised corporation
product,energy credit funding, privatise?(only after a period if time, can't undo,)

#####close nationalised corporation window
are you sure?				

#####edit tax value
tax percentage value

#####new boarder tariff
tax value, trade from?, trade to?
#####edit specific tax 
tax value, trade from?, trade to?

#####delete tax window
are you sure?

#####delete tax reduction window
are you sure?
###trade window
####trade options
trade tarrifs for product types
###outliner
corporation fleets listing
##space gameplay
.trade ships fly about from planet to planet
.trade ships can be destroyed (pirates,war)
.trade ships can be escorted by private war ships
.trade foreign trade ships destroyed (pirates, war) will cause problems with that civ and you can cause problems for a civ in the same way
.In the outliner you should be able to see a listing of all trade fleets
.pirate dens will spawn you will be requested to deal with it 
.can build defense fleet stations that will spawn based on funding defense fleets using your ship designs 
.In the outliner you should be able to see a listing of all defense fleets 
.you can charter companies to mine resources or research on your behalf instead building a station yourself, for reduced maintenance but for reduced resources 
.private companies can on there own start mining/research, you don't pay maintenance on them but you get far less resources in return compared to chartered mining
.can still build stations as normal
.stations will be named according to the owning company (if applicable)
##planet gameplay
.Build, maintain and upgrade buildings as normal
.Charter companies to do the above for you for no maintainence but reduced returns
.Build factories and rent to a company for reduced building maintenance and get research contribution multiplier (5x maybe?) for there product (so it speeds up a research type even more)
.Company can only rent one factory at a time