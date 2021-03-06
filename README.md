# Procedural Textures
by [Patricio Gonzalez Vivo](https://github.com/patriciogonzalezvivo)

The [Tangrams](https://github.com/tangrams) teams ([web](https://github.com/tangrams/tangram) and [native](https://github.com/tangrams/tangram-es)) are excited about the possibilities of using the OpenGL Shading Language to render maps. As Peter and Brett describe in [this article](https://mapzen.com/blog/tangram-a-mapping-library), we use them for everything from geometry extrusion to lighting effects. That’s what makes tangram’s map engine fast, powerful and highly flexible. 

Another use of GLSL Shaders is for generating procedural textures in real time. This allows mappers to make interesting patterns programmatically and apply them to different geometries using custom rules.

This [repository](http://github.com/tangrams/ProceduralTextures) and [on-line gallery](http://tangrams.github.io/ProceduralTextures/) show a small collection of examples to inspire mapmakers to use, code and share generative textures for maps.

## How to install this gallery on your local machine?

* Clone this repository locally and run a Python HTTP Server.

```
git clone https://github.com/tangrams/ProceduralTextures
cd ProceduralTextures
python -m SimpleHTTPServer
```

* Then open your web browser to [http://localhost:8000/](http://localhost:8000) (or the URL specified by the Python script, if different).

## Gallery

#### [Shapes](http://tangrams.github.io/ProceduralTextures/)

<canvas onclick="viewShader('shapes/box.frag');" src="shapes/box.frag"></canvas>
<canvas onclick="viewShader('shapes/circle.frag');" src="shapes/circle.frag"></canvas>
<canvas onclick="viewShader('shapes/cross.frag');"  src="shapes/cross.frag"></canvas>

#### [Patterns](http://tangrams.github.io/ProceduralTextures/)

<canvas onclick="viewShader('patterns/grid.frag');" src="patterns/grid.frag"></canvas>
<canvas onclick="viewShader('patterns/bricks.frag');" src="patterns/bricks.frag"></canvas>
<canvas onclick="viewShader('patterns/sidegrid.frag');" src="patterns/sidegrid.frag"></canvas>
<canvas onclick="viewShader('patterns/checks.frag');" src="patterns/checks.frag"></canvas>
<canvas onclick="viewShader('patterns/diamond.frag');" src="patterns/diamond.frag"></canvas>
<canvas onclick="viewShader('patterns/nuts.frag');" src="patterns/nuts.frag"></canvas>


#### [Animations](http://tangrams.github.io/ProceduralTextures/)

<canvas onclick="viewShader('animations/beatingdots.frag');" src="animations/beatingdots.frag"></canvas>
<canvas onclick="viewShader('animations/movingdots.frag');" src="animations/movingdots.frag"></canvas>
<canvas onclick="viewShader('animations/polardots.frag');" src="animations/polardots.frag"></canvas>
<canvas onclick="viewShader('animations/rotatingdots.frag');" src="animations/rotatingdots.frag"></canvas>
<canvas onclick="viewShader('animations/marchingboxes.frag');" src="animations/marchingboxes.frag"></canvas>
