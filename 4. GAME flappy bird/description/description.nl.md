We maken het game Flappy Bird opnieuw [zimjs.com/slate](https://zimjs.com/slate)
We hebben het spel van [zimjs.com/certificates](https://zimjs.com/certificates) omgezet naar een echt flappy Bird spel.
Deel 1:
```javascript
import zim from "https://zimjs.org/cdn/01/zim_physics";
new Frame(FIT, 1289, 720, light, dark, ready, [
  { src: "https://fonts.googleapis.com/css2?family=Luckiest+Guy" }
]);
function ready() {
  new Pic("https://i.imgur.com/VFYrgK8.png")
    .scaleTo()
    .pos(0, 0, CENTER, BOTTOM);

  new Label(
    "FlappyBird BADGE part 1: \nhttps://zimjs.com/badges/game#badge1\nto do: click and drag somewhere els the bird onto the stage"
  ).pos(0, 40, CENTER, TOP);
  //1 put your code here
  const physics = new Physics();
  physics.drag();
  //const cloud = new Rectangle(50, 50, lighter).centerReg().addPhysics();

  var assets = [{ id: "birdyellow", src: "VODQMzW.png" }]; // or whatever!
  var path = "https://i.imgur.com/"; // or wherever!
  var load = F.loadAssets(assets, path);
  load.on("complete", () => {
    const bird = new Pic("birdyellow").siz(100).centerReg().addPhysics();
    bird.drag({ all: true, overCursor: "grab", dragCursor: "grab" }); // NOT .cur({dragCursor:"grab"})
    //const bounds = pic.getBounds();

    // pic.hitArea = null; // optional if you want only letters to be pressed
    //pic.effect(new AlphaEffect(mask));
  }); //load assets
}

   ```
