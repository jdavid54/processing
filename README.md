# processing
examples of pde files (processing.js)


# html file
// import js
<script src="processing.js"></script>
// canvas tag calling pde file
<canvas data-processing-sources="hello-web.pde"></canvas>

# pde file (ex : hello-web.pde)
void setup() {
  size(1000, 800);
}

void draw() {
  if (mousePressed) {
    fill(0);
  } else {
    fill(255);
  }
  ellipse(mouseX, mouseY, 80, 80);
}
