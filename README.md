# portfolio
## CSharp  

Csharp heb ik leren gebruiken tijdens mijn richting Informatica Beheer.  

**Overloads Definiëren**

- https://dotnetfiddle.net/RXn26T  
- https://dotnetfiddle.net/2p3lt0  

**Declareren en gebruiken van variablen**

- https://dotnetfiddle.net/B0pOkm  
- https://dotnetfiddle.net/ypzI56  
- https://dotnetfiddle.net/oUiGbX  
- https://dotnetfiddle.net/IevPq4  
--> zo heb je bevoorbeeld; integer, long, ulong, char, double , etc.

**Return waardes toepassen**

- https://dotnetfiddle.net/NgvLV7  
- https://dotnetfiddle.net/7Fcpfv  
- https://dotnetfiddle.net/Y6EENw  
- https://dotnetfiddle.net/Y6EENw  
- https://dotnetfiddle.net/VT0CVE   
- https://dotnetfiddle.net/ZVfqNW  --> belangrijk
      
voorbeeld van unused code na return; https://dotnetfiddle.net/8v2NKw  ; als je een regel code invoegt na een return ga je er eigenlijk voor zorgen dat die regel code onder je return niet wordt gebruikt, dus gewoon weg wordt overgeslagen. Hij begint dan na de return terug van het begin.

**code refactoren**

- https://github.com/MichielVE-immalle/CookieClickerWpf  --> volledige code
--> veel methodes worden herhaald, deze code kun je dus verkorten door alles dezelfde naam te geven, NIET VERGETEN; de namen moeten dan ook in uw XAML-code worden aangepast. Dit komt doordat deze methodes eventhandlers zijn.

nl.
```
   private void Coockie_MouseEnter(object sender, MouseEventArgs e)
        {
            Coockie.Fill = new SolidColorBrush(Colors.SaddleBrown);
            Coockie.StrokeThickness = 4;
            Coockie.Stroke = new SolidColorBrush(Colors.Black);
        }


        private void Coockie_MouseLeave(object sender, MouseEventArgs e)
        {
            Coockie.Fill = new SolidColorBrush(Colors.Gray);
            Coockie.StrokeThickness = 2;
            Coockie.Stroke = new SolidColorBrush(Colors.Black);
        }

       

        private void Coockie_MouseLeftButtonDown(object sender, MouseButtonEventArgs e)
        {
            getal = getal +1;
            teller.Text = String.Format("{0}", getal);  
        }
        
```

**if/then/else**  
De if-opdracht test de waarde die men heeft opgegeven.
```
int eline = 16;
if (eline == 16) --> hier gaat hij na of de integer wel degelijk 16 is. als dit effectief zo is gaat hij "leuk afprinten", als het niet                                                                                                    16 is gaat hij "niet juist afprinten.
{
      Console.WriteLine("leuk");
}
else 
{
      Console.WriteLine("Niet juist");
}
```
Het =-teken wordt in je code aangegeven als ==.

als je een method wilt returnen, vb. de method;

```
static void Berekening(int getal1 , int Getal 2)
{
int optelling = getal1 + getal2
return optelling
}
```

Dan moet je nog een regel code afprinten in de main method om deze afteprinten;
```
 static void Main(string[] args)
 {
 Console.WriteLine(Berekening(3 , 3));
 }
```  
vervolgens druk je op F5, hij print het getal 6 af (3+3=6).
## JavaScript  


```
Console.WriteLine(Line)

```   

