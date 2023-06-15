We gaan een sprite van boeva even uitproberen.

'''javascript
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
'''
