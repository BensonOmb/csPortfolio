# csPortfolio

* MyWebPage [here](https://bensonomb.github.io/lightning2/index.html)
* Lightning [here](https://bensonomb.github.io/lightning2/index.html)
* Dice [here](https://bensonomb.github.io/dice3/)
* Chemotaxis [here](https://bensonomb.github.io/chemotaxis4/)
* Starfield [here](https://bensonomb.github.io/starfield5/)
* St.Thomas [here](https://docs.google.com/presentation/d/e/2PACX-1vSP2GNKvvXJNqUpuG9-HYwJcOF9SgRrhvP0IVNJMrkWlJFsjdZhfSBbly79so4iVE1JYtAqScrAQ7IM/pub?start=false&loop=false&delayms=3000)

The following code was difficult because I had trouble finding out how to move the ball in this certain way, I got past it by trying alot of different, and mostly random code and finding out what happened. It took a long time but the trail and error method really helped because it not only showed solutions but also got my brain to think in other areas besides the one way I normal think.

'''java{

class OddballParticle implements Particle {
  double x;
  double y;
  double speed;
  double angle=(Math.PI*2);
  int random;
  
  int clr;
  OddballParticle(int x, int y) {
    this.x=x;
    this.y=y;
    clr=((int)(Math.random()*245)+10);
  }



  public void move() {
    speed=Math.random()*5;
    angle+=.025;

    x+=Math.cos(angle)*speed;
    y+=Math.sin(angle)*speed;
     
  }
  public void show() {
    noStroke();
    fill(clr,clr,clr);
    ellipse(width/2,height/2, (int)((.5)*x), (int)((.5)*y));
  }
}
'''Java

 
