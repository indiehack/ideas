# OurRestaurants ver. 0
- pro každou restauraci jeden chat 
- každý se pak přihlásí k chatům které ho zajímají
Pro tuto verzi by se mi líbily technologie:  bash script, python, api skype klienta (přes knihovnu Skype4Py nebo použitím robota Sevabot), cron na serveru

# OurRestaurants ver. 1
- plně konfigurovatelná verze s webovým rozhraním pro jednotlivé uživatele
- s možností hodnotit restaurace a jídla z nabídky
- personalizovaný seřazený seznam jídel podle předchozích preferencí
- po kliknutí na nejzajímavější jídlo ukáže seznam lidí, kteří mají toto jídlo nebo restauraci taky rádi
- po doplnění času (pamatoval by se taky z minula):
    sestavení chatu pro lidi z dané skupiny s nabídnutým časem
- pro chat se může použít slack, skype, email...
Technologie buď: bash script, api skype klienta, cron na serveru, python, bottle a sqlite (ale asi by to bylo docela složité)
Nebo:  typescript, Hubot, a možná elastic search (možná neméně složité)

Do verze 0 a hlavně 1 jsem zahrnul nápady od @tom-metz @bob @martin.dobias @miklos @mojzis ze slack chatu na které jsem předtím ani nechtěl pomyslet aby to bylo realizovatelné. 

Už pouhá poloviční realizace verze 1 se dá pokládat za úspěch. A co teprve kompletní...


## Pár odkazů na menu okolních oblíbených restraurací
- http://www.pricnyrez.cz/cz
- http://reznicka.jinakrajina.cz/cs/denni-nabidka/
- http://www.elpueblo.cz/cs/denni-nabidka/
- Hloupý Honza: https://www.zomato.com/cs/widgets/daily_menu?entity_id=16506572
- http://www.bombayexpress.cz/nabidka/#mix a http://www.bombayexpress.cz/denni-nabidka/ (přes odkaz)
- Dietní jídelna ve Spálené http://www.prahamp.cz/index.php?nid=7262&lid=cs&oid=2797599
- http://www.deliviet.cz/jidelni-listek
- Jednota v Oletalce (nutno zvolit) https://kamweb.ruk.cuni.cz/webkredit/ZalozkaObjednavani.aspx
