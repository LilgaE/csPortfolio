# Evan Lilga's csPortfolio
---
Title | link
------------ | -------------
WebPage | [here](https://lilgae.github.io/TestWeb/highlight.html)
Dice | [here]()
Chemotaxis | [here]()
StarField | [here]()
Christmas Card | [here](https://lilgae.github.io/projectTemplate/)
---

```Java
void mouseReleased(){
  background(0);
  startX = mouseX;
  startY = 0;
  endX = mouseX;
  endY = 0;
  }
  
red=round((random(0,255)));
green=round((random(0,255)));
blue=round((random(0,255)));
fill(red,green,blue);
ellipse (mouseX,mouseY,25,25);

class star implements Others
{
  double startX;
  double startY;
  double angle;
  int speed;
  float zoom,zoom1;
  
    star(){
      startX=250;
      startY=250;
      zoom=4;
      angle=Math.PI*Math.random()*2;
      speed=(int)(Math.random()*20)/2;
    }
    void movestars()
    {
      startX+=Math.sin(angle)*(Math.random()*speed);
      startY+=Math.cos(angle)*(Math.random()*speed);
      
      if(startX>=500){
        startX=1;
        startY=499;
      }
      if(startX<=0){
         startX=499;
        startY=1;
      }
      if(startY>=500){
        startY=1;
        startX=1;
      }
       if(startY<0){
         startX=499;
        startY=499;
      }
      //if(startX>=500 && startY>=500){
      //   startX=1;
      //  startY=1;
      //}
      //if(startX<=500 && startY>=500){
      //   startX=499;
      //  startY=1;
      //}
      //if(startX<=500 && startY<=500){
      //   startX=499;
      //  startY=499;
      //}
      //if(startX>=500 && startY<=500){
      //   startX=1;
      //  startY=499;
      //}
      
}
```
