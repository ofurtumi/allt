# gott að muna

## em og rem
þegar verið er að nota *em* gildi á einhverju er miðað við **síðustu** skilgreiningu í foreldri

```css
html {
	font-size: 16px; 	*/ font size skilgreint sem 16px, texti innan html er núna 16px */ 
}
.text {
	font-size: 2em; 	*/ font size skilgreint sem 2em, texti innan .text er þá 2 x 16px */ 
}
.text p {
	font-size: 1.5em;  */ font size skilgreint sem 1.5em, texti innan .text p er þá 1.5 x 2 x 16px */ 
}
```
ef þú vilt nota rótar *em* gildið þá er hægt að nota *rem*, sem sleppir þessum trjá reikningi og fer beint í efsta gildið

## box módelið
muna shorthand fyrir [[box model]] er 
```css
p {
	margin: 1em;									*/ margin á öllum hliðum 1em*/
	padding: 1em 2em;						    */ padding á topp og botn 1em, hægri vinstri 2em*/
	border: 1em 2em 3em;					 */ border á topp 1em, hægri vinstri 2em, botn 3em*/
	box-shadow: 1em 2em 3em 4em;	*/ shadow á topp 1em, hægri 2em, botn 3em, vinstri 4em */
}
```
> gott að muna að þetta fer **klukkuhringinn** og byrjar á **tólf**

## border 
skemmtilegt border radius
```css
border-radius: 85px 85px 35px 35px / 150px 150px 35px 35px;
```

### generators 
- [box shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders/Box-shadow_generator)
- [border radius](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders/Border-radius_generator)