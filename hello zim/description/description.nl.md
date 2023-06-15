Schrijf de tekst "Hallo, ZIM!" in het midden van je canvas.
Tip: we gebruiken nooit print("...") omdat dit naar de console.log("..") wordt geschreven, maar wel zog("..").

De code zal er als volgt uit zien (denk aan een label/etiketje in je kledij waarop ook tekst staat)

```javascript 
new Label("Hallo, ZIM!").center();  // size standard 30 points en color black
new Label("Hallo, ZIM!", 30, null, black).center(); // no font is specified so it is null 
new Label({text:"Hallo, ZIM!", size:30, font:null, color: black}).center(); //specify all ZIM DUO elements 
new Label({text:"Hallo, ZIM!", size:30, color:black}).center(); // you don't have to specify all elements in order
```
Je kan natuurlijk ook alles op verschillende lijnen typen maar dat brengt een groter/langer tekstbestand, maar meer duidelijkheid.
```javascript
new Label({
   text:"Hallo, ZIM!",
   size:30,
   color:black
})
   .center();
```

Test je code op [zimjs.com/slate](zimjs.com/slate) of in [zimjs.com/editor](zimjs.com/editor)
Succes

Tip: de Console van de webbrowser openen (doe je met ctrl+shift+i) (=informatie die je krijgt als je code uitvoert)
* standaard gebruikt javascript console.log("Hallo, ZIM") 
* maar ZIMjs verkort alles naar zog("Hallo, ZIM") meer info in de [https://zimjs.com/docs.html?item=zog](https://zimjs.com/docs.html?item=zog)
```javascript
zog("Hallo, ZIM")
```

Meer info there: 

[afbeelding van op zimjs.com/docs zog](https://i.imgur.com/1f6WRNM.png){: .dodona-lightbox}
<br>
<div class="dodona-centered-group">
   <img src="https://i.imgur.com/iz3nQRN.png" 
        data-caption="zog() rechtsboven zoeken, EXPAND-knop om code-beschrijving te lezen"
   />
  <br>
   Je klikt op EXPAND en ziet deze informatie over hoe je de code zog() moet gebruiken 
 <br>
  <img src="https://i.imgur.com/1f6WRNM.png" width="500"
       data-caption="zog() codebeschrijving met ook kleurweergave mogelijk in de console"
   />
 <br> Tip: avatar Pragma (Madeleine Zen, dochter van uitvinder Dan Zen) kan je ook terugvinden op de banner op zimjs.com/kids  
</div>
