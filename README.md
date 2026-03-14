# Wraprobot

Maston maalipurkkien pakkausrobotin ohjauslogiikka ja siihen liittyvä sähköistysratkaisu
Logiikka on Omron CP1L-EM30TD1 kytkettynä Elite Robots EC66 -robottimanipulaattoriin Modbus/TCP yhteydellä.
Kone pakkaa kutistemuovitettavia purkkeja pahvialustalle. Purkit saapuvat täyttölinjalta pyöröpöydän kautta 
poimintakuljettimelle, josta robotti nostaa ne pahvialustalle. Alustat syötetään pakkauspositioon makasiinista
logiikan ohjauksessa.Alustoja on (ainakin) 2 eri kokoa, kummatkin omassa makasiinissaan joka asennetaan latauspaikkaan tarpeen mukaan.
Logiikka tunnistaa alustan ja pakattavan astian koon. Purkit pysähtyvät poimintakuljettimelle kokoaan vastaaviin kohtiin kaiteiden
ohjaamana. Kaiteet kapenevat niin että pienimmät purkit etenevät pisimmälle.
Kun purkit on nostettu alustalle, alusta siirretään muovituskoneen tulokuljettimelle josta prosessi jatkuu kuten aiemminkin.
