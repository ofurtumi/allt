# cascading style sheesh
css er notað til hliðsjónar [[html]] og skilgreinir útlit og uppsetningu gagna sem eru fengin úr html eða [[javascript]] skjölum. málfræði í css er einföld og er í raun hægt að lýsa *allri* virkni css með einni línu: `selector {property: value;}`

## selectors
css sækir *selectors* í [[DOM]], nema pseudo-element og klasa, og má skipta þeim svona niður: 

| selector       | meining                          |
| -------------- | -------------------------------- |
| *              | öll element                      |
| div            | öll div                          |
| div p          | öll p, afkomendur div            |
| div > p        | öll p sem eru börn p             |
| p + p          | öll p með p sem fyrra systkini   |
| p ~ span       | öll span sem koma á eftir p      |
| div.important  | öll div sem hafa class important |
| a:hover        | öll a sem eru hovered            |
| div#main       | öll div sem hafa id main         |
| div[lang="is"] | öll div með attribute lang=is    |


## gervi-element (e. pseudo-element)
gervi element eru element sem eru ekki til staðar í [[DOM]] trénu, þetta geta verið element eins og **before**, **after** eða jafnvel eitthvað eins hentugt og **first-letter**
*gervi element* eru skilgreind með tveimur tvípunktum **::**
>linkur á mozilla docs yfir [gervi element ](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)

það eru líka til svokallaðir *gerviklasar (e. pseudo-classes)* sem, eins og **hover**, eru skilgreindir með einum tvípunki, **:** , og bjóða upp á ýmsa virkni
> linkur á mozilla docs yfir [gerviklasa](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)

