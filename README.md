# csPortfolio
---
* WebPage [here](https://lilgae.github.io/TestWeb/highlight.html)
* Lighting [here](https://lilgae.github.io/lightning2/)
* Dice [here](https://lilgae.github.io/dice3/)
* Chemotaxis [here](https://lilgae.github.io/chemotaxis4/)
* Presentation [here](https://docs.google.com/presentation/d/17_0oXYXVy0iQVyKe2z0SUOL0PAO1ArPBuLYvPWIvUAw/edit#slide=id.g446c206545_0_25)
* StarField [here](https://lilgae.github.io/starfield5/)
---

```Java
void mouseReleased(){
  background(0);
  startX = mouseX;
  startY = 0;
  endX = mouseX;
  endY = 0;
}

void mouseWheel(MouseEvent event) {
  speed+=event.getCount();
}
  
void moveballs()
    {
      if(startX!=mouseX||startY!=mouseY){  
      ellipse (startX,startY,10,10);
      if (startX>=mouseX)
      startX = startX-(int)(Math.random()*10)+speed;
      else if (startX<=mouseX)
      startX = startX+(int)(Math.random()*10)-speed;
      if (startY>=mouseY)
      startY = startY-(int)(Math.random()*10)+speed;
      else if (startY<=mouseY)
      startY = startY+(int)(Math.random()*10)-speed;
      }
}
```
