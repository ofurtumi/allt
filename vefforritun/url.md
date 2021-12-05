# url
sjá um að staðsetja og skilgreina hvernig við sækjum vefsíður yfir [[http]]
urlar eru byggðir upp af með eftirfarandi hlutum:

>## samskiptareglu (e. protocol)
>t.d [[http]] eða [[ftp]] táknað með **foo://**

>## vefþjóni (e. web server, domain)
>ehv [[lén]] vanalega en líka hægt að nota beina [[ip|ip tölu]]

>## slóð (e. path)
>er staðurinn þar sem vafrinn á að sækja síðuna, þe. það sem kemur á eftir vefþjónsnafninu. í urlinu *sjomli.is/__blogg__* er blogg slóðin, mappan sem á að birta.
>slóðin getur svo líka innihaldið *query-streng* sem er þá samansafn af aukaupplýsingum sem sendar eru á vefsíðu með **?** fremst og síðan ehv gildi, *sjomli.is/blogg__?foo=true__*
>svo getur verið enn eitt í slóðinni það er *fragment identifier* sem væri þá staðsetning innan vefsíðu táknaður með **#**, *sjomli.is/blogg?foo=true__\#bar__*

>í linknum sem er kominn *https://sjomli.is/blogg?foo=true#bar*, sem er btw bara ehv bull, er hægt að lesa úr að verið sé að sækja **vefsíðuna** *blogg* á **vefþjónin** *sjomli.is* með **samskiptareglunni** *https* þar sem *foo* er jafnt og *true* og **vafrinn** á að staðsetja sig hjá *bar*