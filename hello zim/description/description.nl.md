Schrijf de tekst "Hallo, ZIM!" in het midden van je canvas.
De code zal er als volgt uit zien
* new Label("Hallo, ZIM!").center();  // size standard 30 points en color black
* new Label("Hallo, ZIM!", 30, null, black).center(); // no font is specified so it is null
* new Label({text:"Hallo, ZIM!", size:30, font:null, color: black}).center(); //specify all ZIM DUO elements
* new Label({text:"Hallo, ZIM!", size:30, color:black}).center(); // you don't have to specify all elements in order

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

Tip: console (informatie die je krijgt als je code typt.
* standaard gebruikt javascript console.log("Hallo, ZIM") 
* maar ZIMjs verkort alles naar zog("Hallo, ZIM") meer info in de [https://zimjs.com/docs.html?item=zog](https://zimjs.com/docs.html?item=zog)

Meer info there: 
<a href="https://i.imgur.com/1f6WRNM.png" class="dodona-lightbox">Show image</a>
[afbeelding van op zimjs.com/docs zog()](https://i.imgur.com/1f6WRNM.png){: .dodona-lightbox}
<div class="dodona-centered-group">
   <img src="https://i.imgur.com/iz3nQRN.png" />
  <img src="https://i.imgur.com/1f6WRNM.png" />
 ![https://i.imgur.com/iz3nQRN.png](https://i.imgur.com/1f6WRNM.png)
</div>
