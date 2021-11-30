### e. time complexity
ef það á að athuga hvort ehv fall sé jafnt og ehv bigO þarf að finna fasta k og fasta c þar sem þegar $x>k$ gildir að $fall<c*bigO$

# dæmi
er $7x^2 = O(x^3)$
látum $k=7$ og $c=1$
þá er hægt að athuga, er $7x^2<1*x^3$ þegar $x>7$
látum $x=8$ þá er $7*8^2<1*8^3$ sem er $448<512$ sem er satt þannig $7x^2=O(x^3)$

# önnur aðferð
betri leið, *því ég skil ekki þessa aðferð er að athuga hversu oft fallið endurtekur sig*
ef ég er með fallið $n!=(n-1)(n-2)(n-3)...2*1\le n*n*...*n=n^n$
svo er líka bara listi með stóra o gildum algengra falla
það er miklu þægilegra að sjá stóra-O í forritum, þá þarf bara að leggja saman og setja í veldi allar lykkjur með hámarksfjölda aðgerða

stóra-O hjá **[[fylkjamargföldun]]** þar sem fylkin eru bæði $n\times m$ væri n*m*n*m