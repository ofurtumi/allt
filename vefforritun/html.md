# hypertext markup language
er lýsandi umbrotsmál og án efa eitt mest kunna "forritunarmál" sem til er. fyrstu útgáfur voru byggðar á *SGML* sem stendur fyrir standard generalized markup language og er *ISO* staðall sem skilgreinir **almennt** markup mál fyrir skjöl, það er byggt á tveimur hugmyndum:
- snið ætti að vera lýsandi
- snið ætti að vera strangt svo auðvelt sé að vinna úr því

W3C sér núna um stöðlun á html og á sama tíma css

## html element
html er byggt upp af svokölluðum **elementum** stökum sem geta innihaldið texta, önnur element eða bara ekki neitt, dæmi um slík væru *\<p>* og *\<div>* þar sem *p* er ætlað til þess að halda texta (e. paragraph) og div er til þess að skipta hlutum niður (e. division).
>hægt er að finna lista með öllum elementum og útkýringar á þeim á vef  <a href ="https://developer.mozilla.org/en-US/docs/Web/HTML/Element">mozilla developers</a>

## html tags
flest *element* hafa byrjunar- og endatag sem segja hvar element byrja og hvar þau enda þe. byrjunartagið fyrir paragraphs væri *\<p>* og endatagið *\</p>*, oft er ruglað saman **element** og **tag** en gott að muna að tag er eins og *datatype* (int, string, div, p) og á meðan element er gildið

## html attributes
**attribute** er hægt að nota til þess að ljá **elementi** frekari merkingu og í sumum tilfellum virkni, þetta eru gildi eins og fyrir *\<a>* tagið sem þarf að hafa *href* attribute til þess að geta hyperlinkað yfir á ehv annan stað. í sumum tilfellum eru attributes bara til þess að kveikja og slökkva á hlutum eins og *input checkbox* sem notast við boolean attributið *checked*
mest notuðu attributin eru samt án efa *class* og *id* sem er svo hægt að vitna beint í, í gegn um bæði [[css]] og [[javascript]]

