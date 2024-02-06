# primer-codigo-esfera

void setup() {
  size(400, 400);  // Establece el tamaño del lienzo
}

void draw() {
  background(255);  // Establece el fondo blanco

  // Dibuja un círculo en el centro del lienzo
  fill(255, 0, 0);  // Establece el color de relleno a rojo
  ellipse(width/2, height/2, 50, 50);  // Dibuja el círculo
}
