# CaptainArcade Learning

## 1. Les variables

### 1.I : Définir une variable
Une variable se définit par défaut comme : type nom = valeur ;


/!\ Attention, on ne peut pas nommé deux variables par le meme nom, mais pour redéfinir sa valeur, il suffit de faire ->

nom = valeur


Par exemple : 

- string : (chaine de caractères -> text) -> string y = "text";
- int : (integer -> nombre) -> int x = 193;
/!\ Pour ajouté une valeur à int, il suffit de faire nom++;
- bool : (boolean -> true/false) -> bool z = false; 
z = true;
"" != ''
- char : (character -> a, b, c, etc...) -> char e = 'a';


## 2. Les méthodes
Les méthodes sont des actions allant être executé **uniquement** lorse qu'on les appelles.

### 3. Méthode inclus en C#

Console.WriteLine("text"); -> écris le text dans la console et d'aller à la ligne
Console.Write("text"): -> écris le text dans la console.
Console.Title = "titre de la console"; -> donne un titre à la console
Console.ForegroundColor = ConsoleColor.Red; -> Les prochain texte écris seront en rouge 
Console.BashgroundColor = ConsoleColor.Red; -> Les prochain texte écris auront un arriere plan en rouge 

string text = Console.ReadLine(); -> permet d'attendre une chaine de caractère et de le stocké sous le nom de variable "text".
char key = Console.ReadKey(); -> opermet d'attendre une touche et la stock sous le nom de la variable "key";

