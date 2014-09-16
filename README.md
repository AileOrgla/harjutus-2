harjutus-2
==========
<!DOCTYPE HTML>
<html>
   <head>
   <title>Harjutus</title>
	 <meta http-equiv="Content-Type" content="text/html;
   cahrset=utf-8">
   <title>Harjutus - PHP põhitõed</title>
	 </head>
   <body>
   	
      <h1>See dokument on minu esimene katsetus PHP-ga</h1>
      <?php 
          echo "Tere! " . "Siin on teine tekst " . "Siin ka"; 
          echo "<br>";
          echo "Järgmine rida";
       ?>

      <br>
      <h2>Arvutamine</h2>
      <p>Siin teeme erinevaid tehteid</p>

      <?php echo "Nelja ja viie summa on " . (4 + 5) ; ?>
      <br>
      <?php 
          // Siin on PHP kommentaar.
        # See on ka kommentaar.
        /*Kommentaar
        Kommentaar*/
          echo 4 - 5; 
      ?>
      <br>
      <?php echo 4 * 5; ?>
      <br>
      <?php echo 4 / 5; ?>

      <h2>Muutujad</h2>

      <?php 
      $number = 5 - 4;
      $number2 = 9;
      $text = "Kahe arvu summa on";

      echo  
      "<p>Siin tuleb list</p>
      <ul>
          <li>".$text."</li>
          <li> ".($number + $number2)."</li>
      </ul>" ;   
      ?>
   </body>

</html>
