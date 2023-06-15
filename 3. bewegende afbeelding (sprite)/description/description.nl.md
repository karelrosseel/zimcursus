We gaan even dit voorbeeld uitleggen in [zimjs.com/slate](zimjs.com/slate)
```javascript
var assets = [{id:"boeva", src:"j5Jx6Zs.png"}]; // or whatever!
var path = "https://i.imgur.com/"; // or wherever!
F.loadAssets(assets, path);
F.on("complete", ()=>{
  
    var sprite1 = new Sprite("boeva", 13, 3)
        .center()
        .run({time:10, loop:true});  
});

new Label({
   text:"Hallo, Boeva!",
   size:30,
   color:black
})
   .pos(0,100,CENTER,TOP);
   ```
