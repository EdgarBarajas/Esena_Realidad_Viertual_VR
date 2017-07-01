# Esena_Realidad_Viertual_VR
Esena de realidad virtual con A-Frame
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8"/>
    <script src="https://aframe.io/releases/0.5.0/aframe.min.js"></script>
    <title>Mi Proyecto A-Frame</title>
  </head>
  <body>
    <a-scene>
      <!--FONDO-->
      <a-sky>
        <a-animation attribute="material.color" from="purple" to="black" dur="3000" repeat="undefinite"></a-animation>
      </a-sky>

      <!--ESFERA-->
      <a-sphere position="-3 .5 1" radius= "2">
        <a-animation attribute="position" from=" .5 -4.8" to="2 4 -11" dur="3000" repeat="undefinite">
        </a-animation>

        <a-animation attribute="material.color" from="red" to="yellow" dur="1000" repeat="undefinite"></a-animation>

        <a-animation attribute="scale" begin="3000" to="1.5 1.5 1.5" repeat="undefinite"></a-animation>
      </a-sphere>

      <!--CUBO-->
      <a-box position="-2 1.5 -3" rotation="45 90 180" color="green">
        <a-animation attribute="scale" begin="5000" to=".5 .5 .5" dur="3000" repeat="undefinite"></a-animation>
        <a-animation atributte="rotation" from="45 90 180" to="45 360 360" dur="3000" repeat="undefinite">
        </a-animation>
      </a-box>
    </a-scene>
  </body>
</html>
<!--By J.B>
