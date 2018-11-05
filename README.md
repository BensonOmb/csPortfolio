# csPortfolio

* MyWebPage [here](https://bensonomb.github.io/lightning2/index.html)
* Lightning [here](https://bensonomb.github.io/lightning2/index.html)
* Dice [here](https://bensonomb.github.io/dice3/)
* Chemotaxis [here](https://bensonomb.github.io/chemotaxis4/)
* Starfield [here](https://bensonomb.github.io/starfield5/)
* St.Thomas [here](https://docs.google.com/presentation/d/1iZrKE3-hbXkK3rF7mpYMKIr_VQY1mwyH16PAfJbMW9s/edit#slide=id.p)

```Java
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
}```
