# Klasifikacija Podatkov - Strojno Učenje (WPF)

Aplikacija je namenjena učenju, testiranju in vizualizaciji algoritmov strojnega učenja na podatkovnih množicah (klasifikacija rdečih vin). Zgrajena je kot namizna aplikacija v ogrodju .NET 9 z uporabo WPF (Windows Presentation Foundation) za grafični vmesnik.

## Lastnosti in Algoritmi
- **K-najbližjih sosedov (K-NN):** Implementacija klasifikacijskega algoritma na podlagi evklidske razdalje med sosedi.
- **Odločitvena drevesa:** Klasifikacija z uporabo logike odločitvenega drevesa (`DrevoAlgoritem`).
- **Analiza podatkov:** Podpora za uvoz in obdelavo podatkov iz datoteke `winequality-red.csv`.

## Tehnologije
- **Ogrodje:** .NET 9.0 (WPF)
- **Programski jezik:** C#

## Kako zagnati projekt
1. Prepričajte se, da imate nameščen **.NET 9 SDK** in **Visual Studio 2022**.
2. Odprite rešitev `StrojnoUcenjeProjekt.sln`.
3. Preverite, ali je v mapi prisotna podatkovna datoteka `winequality-red.csv`.
4. Pritisnite `F5` ali gumb **Start** v Visual Studiu za zagon namizne aplikacije.
