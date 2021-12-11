# net
net, *e. graph*, er leið til að setja fram lýsingar á **hnútum**, *e. nodes*, og **leggja** , *e. edges*, á milli þeirra
skilgreining á óstefndu neti $G = (V,E)$ er tvennd þar sem $V$ er mengi **hnúta** sem er ekki tómt, $E$ er mengi **leggja**
hver leggur er tengdur við einn eða tvo hnúta, þe. **endahnúta** leggsins 
*ath. þegar leggur er aðeins tengdur við einn hnút myndar hann svona asnalega lykkju frá og til sama hnútsins*
leggir í óstefndum netum vísa ekki í neina sérstaka átt

## nokkur sérstök net
> **tóm net**
> net $G=(V,E)$ þar sem $E=V=\varnothing$, þe. netið er tómt ef það inniheldur **enga leggi né hnúta**

> **núllnet**
> net $G=(V,E)$ þar sem $E=\varnothing$, þe. netið er núllnet ef það inniheldur enga leggi til þess að tengja hnúta þess saman

>**fullskipuð net**
>eru *einföld* net með $n$ hnútum, og hafa nákvæmlega einn legg á milli hverra tveggja hnúta, fullskipuð net með $n$ hnútum eru táknuð með $K_n$

>**hringnet**
>eru einföld net með $n\ge 3$ hnútum þar sem hver hnútur er **tengdur við nágranna** sína, þe. hnúturinn $v_2$ væri tengdur $v_1$ og $v_3$, n-ti hnúturinn $v_n$ tengist  svo $v_{n-1}$ og $v_1$, þannig netið myndar **einn stórann hring**, hringnet eru táknuð með $C_n$

>**hjólnet** 
>eru hringnet þar sem búið er að **bæta einum auka hnút í mitt netið**, allir hnútar netsins tengjast í þennan hnút , ef taka ætti *hringnetið* $C_3$ og breyta því í *hjólnet*, yrði það að hjólnetinu $W_3$ sem inniheldur samt fjóra hnúta, hjólnet eru táknuð með $W_n$

>**ofurteningar**
>eða *n-teningar* eru myndaðir þannig að ef maður byrjar með $Q_n$, þe. ofurtenging með $2^n$ fjölda hnúta, væri $Q_{n+1}$ net þar sem búið er að afrita alla hnúta $Q_n$ og mynda legg á milli upprunalega hnútsins og afrit hans, ofurteningar eru eins og sést fyrir ofan táknaðir með $Q_n$
>*ath. það er alltaf hægt að finna [[hamilton rás]] í n-víðum ofurtening ef það er hægt að sýna fram á að hún sé til í $n-1$ víðum ofurtening, og þar sem hægt er að finna hamilton rás í $Q_0$ ofurtening er hún til í þeim öllum*