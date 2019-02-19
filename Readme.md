## ` Datenfeld ` 
Bei Datenfelder erfolgt die Dateneingabe in einer neuen Zeile mit  `LEERZEICHEN - ` . Es können hier mehrere Werte eingebegen werden.
Bei allen anderen Feldern erfolgt die Dateneingabe direkt in der selben Zeile. 

## layout
immer bei `none` lassen
## active
`true`
`false` 

## promoted 
`true`
`false`

## promotion-text
Hier die Art der Hervorhebung beschreiben. Z.B. Testsieger, schneller Kartenantrag, etc.

## title
advanzia -> Interner Name zum Filtern

## product-name
Advanzia Mastercard GOLD -> Wird in der Box angezeigt.

## product-image
advanzia-mastercard-gold.jpg -> name der Bilddatei. Datei muss unter assets/images/ abgelegt sein.

## cardsystem ` Datenfeld ` 

Yaml Array. Mögliche Werte:
 * mastercard
 * vsia
 * amex
 
Bei Doppelkarten 
 
 \- master
  
 \- visa 

## zahlungsart: 
za0: sofortiger Einzug vom Konto  
za1: Rechnung / monatlich
za2: Teilzahlungsfunktion
za3: Prepaid

## status: 
gold
platin
default


## startguthaben
hier nur eine Zahl eintragen. Keine Währung, etc.

## killer-feature ` Datenfeld `
## usp  ` Datenfeld ` 

 - Dauerhaft ohne Jahresgebühr
 - Weltweit gebührenfrei Abhebungen 

negative: "100% Ausgleich manuell"
ranking: 1.9
test-winner: false
price-1st: 0
price-2nd: 0
bargeld: 0
bargeld-text: "Bargeldabhebung ist Gebührenfrei. Allerdings wird jedoch bis zum Rechnungsausgleich ein eff. Jahreszins von 19,44 % fällig."
bargeld-eurozone: 0
bargeld-eurozone-text: ""
weltweit-kostenlos: true
eurozone-kostenlos: false
sollzins: 18.38
sollzins-text: 
habenzins: 
habenzins-text: 
business-use: false
private-use: true
insurances: true
travel-benefits: false
car-benefits: false
contactless: true
videoident: true
ios-app: true
android-app: true
responsive-website: true
link: /zur-bank/barclaycard-visa/
