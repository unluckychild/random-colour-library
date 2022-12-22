# random-colour-library


Generates random colour. You can either choose random from the whole pool or random within 1 colour type pool.


example:


$my=new GetColor();

$my->addColor("new color");  //You can add your own colour here

$my->getRandomColor(3, false, false)


first parameter = number - how many colours do you want

second parameter one type? = true/false - do you want one type or many colour types (Colours are divided into same colour category)

third parameter repeat colors = true/false - can colours appear more than once?
