# tugakerfið
er það kerfi sem við notum í flestum tilfellum, þar eru gildi staks jafnt og talan  margfölduð með tíu í nta veldi, þar sem n er staðsetning tölunnar 
þá væri 510 til dæmis $5*10^2+1*10^1+0*10^0$

# tvíundarkerfið
### e. binary
er kerfi sem notar 2 sem veldisvísi 
til þess að setja tölu úr tugakerfi yfir í binary **deilir** maður upprunalegu tölunni með **tveimur** og setur afganginn í nta sæti
þetta er svo endurtekið með tölunni sem kom út úr deilingunni, án afgangsins, þangað til maður endar með 0
510 í tvíundarkerfi væri þá reiknað:
$$
\begin{align}
	510&=2*255+0\\
	255&=2*127+1\\
	127&=2*63+1\\
	63&=2*31+1\\
	31&=2*15+1\\
	15&=2*7+1\\
	7&=2*3+1\\
	3&=2*1+1\\
	1&=2*0+1
\end{align}
$$
510 í tvíundarkerfi værir þá $111111110$ sem meikar sens þar sem 512 er $2^9$ og öll stök nema síðasta eru 1

**önnur kerfi sem ég nenni ekki að fara djúpt í**

# áttundakerfið
### e. octal
það má reikna það útfrá tugakerfi eins og maður færi að því að reikna binary nema í stað þess að deila með 2 deilir maður með 8 og afgangurinn getur verið frá 0 til 7

# sextándukerfið
### e. hexadecimal
svipað og áttundakerfið nema vegna þess að maður deilir með 16 getur afgangurinn verið frá 0 til 15, og í stað þess að skrifa tölur eftir 9 sem tölur eru settir bókstafir í staðinn
[[mengi]] hugsanlegra afganstalna er þá $[0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F$

