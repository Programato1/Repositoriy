<html>
 <head>
 <title>Перша лабораторна</title>
 </head>
 <body>
  <h1>Богуш Роман Васильович</h1>
  <p>Лабораторна робота1.</p>
  <h2>Блітц опитування</h2>
  <p>тел.+380951584079</p>
  <h3>Початок питань</h3>
  <p>Який ваш улюблений президент?</p>
  <input type="radio" id="contactChoice1"
     name="contact" value="email">
    <label for="contactChoice1">Зеленський</label>

    <input type="radio" id="contactChoice2"
     name="contact" value="phone">
    <label for="contactChoice2">Порошенко</label>

    <input type="radio" id="contactChoice3"
     name="contact" value="mail">
    <label for="contactChoice3">Янукович</label>
    <form method="post" action="input5.php">
   <p><b>Який улюблений ваш виробник цукерок?</b></p>
   <p><input type="checkbox" name="option1" value="a1" checked>АВК<Br>
   <input type="checkbox" name="option2" value="a2">Корона<Br>
   <input type="checkbox" name="option3" value="a3">Світоч<Br>
   <input type="checkbox" name="option4" value="a4">Рошен<Br>
   <input type="checkbox" name="option5" value="a5">Міллєнніум</p>
   <p><input type="submit" value="Отправить"></p>
   <form action="textarea1.php" method="post">
    <p><b>Яка якіть поставлених питань?</b></p>
    <p><textarea rows="10" cols="45" name="text"></textarea></p>
    <p><input type="submit" value="Отправить"></p>
  </form>
  </form>
 </body>
</html>
