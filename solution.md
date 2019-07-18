clearTopHalf: aPicture
|tempHeight|
//Obtenemos el alto de aPicture
tempHeight := aPicture height;
//Pasamos a blanco las filas desde 1 hasta la mitad de la altura
1 to: (tempHeight/2) do: [:i | aPicture rowToWhite: i];
^aPicture