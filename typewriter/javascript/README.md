<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Typewriter</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bulma/0.7.2/css/bulma.css">
  </head>
  <body>
    <div class="container">
      <h1 class="title">Typewriter</h1>
      <p>Te mostramos como crear tu propio typewriter es muy sencillo: </p>
      <br><br>
      <strong>Html</strong>
      <br>
      <code>
        &lt;div class=&quot;text&quot; id=&quot;ejemploId&quot;
        atw-time=&quot;200&quot;
        atw-text=&quot;En un lugar muy lejano llamado Pentagrama, habitaban animales que pod&iacute;an tocar instrumentos musicales. Los p&aacute;jaros, los conejos, los zorros y los osos, cada uno de ellos llevaba su instrumento colgado en el cuello, y a cada minuto del d&iacute;a, entonaban bellas y agradables melod&iacute;as que alegraban todo el bosque.&quot;
        atw-random=&quot;atw-ramdom&quot;&gt;

        &lt;/div&gt;
      </code>

      <br>
      <strong>Javascript</strong>
      <br>
      <code>

        AjalTypeWriter('ejemploId',`contenido`,tiempo);
      </code>
      <br><br>

      <p>Lo que genera la siguiente salida:</p>
      <div class="text" id="ejemploId"
      atw-time="70"
      atw-text="En un lugar muy lejano llamado Pentagrama, habitaban animales que podían tocar instrumentos musicales. Los pájaros, los conejos, los zorros y los osos, cada uno de ellos llevaba su instrumento colgado en el cuello, y a cada minuto del día, entonaban bellas y agradables melodías que alegraban todo el bosque."
      atw-random="atw-ramdom">

      </div>

      <strong>Opciones</strong>
      <table class="table">
        <tr>
          <td>atw-time</td>
          <td>Especifica el tiempo entre cada letra</td>
        </tr>
        <tr>
          <td>atw-text</td>
          <td>Especifica el texto que se despliega</td>
        </tr>
        <tr>
          <td>atw-random</td>
          <td>Especifica si el tiempo es random</td>
        </tr>
      </table>

    </div>
    <div class="footer">
      Todos los derechos reservados por Ajal Technology 2019
    </div>
    <script type="text/javascript" src="ajal.typewriter.js"></script>
    <script type="text/javascript">
        new AjalTypeWriter('ejemploId').start();
    </script>
  </body>
</html>
