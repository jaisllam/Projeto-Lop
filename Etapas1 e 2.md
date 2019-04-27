# Projeto-Lop
/* 
    Equipe: 
        Kaio Yuri Lopes de Araújo - A (Líder) 
        Jaíslla Macêdo da Silva  - C 
        Etapa 1 e 2
*/

function setup() {
  createCanvas(400, 400);
}
xc=350;
yc=350;

function draw() {
  background(01);
  rect(20, 20, 80, 80);
  fill(255, 0, 0);
  ellipse(xc, yc, 80, 80);
  fill(0,0,255)
  if (keyIsDown(RIGHT_ARROW))
  xc=xc+7;
  if (keyIsDown(LEFT_ARROW))
  xc=xc-7;
  if (keyIsDown(UP_ARROW))
  yc=yc-7;
  if (keyIsDown(DOWN_ARROW))
  yc=yc+7;
}
