# Gulp---configuration
Konfiguracja gulp.js

- Krok 1:  Otwórz terminal i wpisz komnndę: npm i
- Krok 2: Stwórz następującą strukturę plików  
![image](https://github.com/mik00laj/Gulp---configuration/assets/108618874/47ce5279-10f0-4e6a-af5c-490d29773cd1)


# Opis 
- series() - funckje są wykonywane jedna po drugiej - synchornicznie 
- parallel() - funckje są wykonywane jednocześnie na raz - asynchronicznie 

1) gulp -> narzędzie do automatyzacji zadań w środowisku Node.js. Umożliwia ono programistom tworzenie złożonych procesów budowania i wdrażania aplikacji internetowych.

2) gulp-cssnano -> umożliwia kompresję plików CSS, co pozwala na zmniejszenie ich rozmiaru i poprawienie wydajności strony internetowej.

3) gulp-autoprefixer -> umożliwia automatyczne dodanie prefiksów przeglądarkowych do reguł CSS, co pozwala na uzyskanie spójności wyglądu strony internetowej na różnych przeglądarkach. 

4) gulp-rename -> pozwala na zmianę nazw plików w procesie budowania. Jest to przydatne, gdy potrzebujemy np. zmienić rozszerzenie pliku.

5) gulp-babel -> Moduł ten umożliwia kompilację kodu JavaScript napisanego w nowszych wersjach ECMAScript do starszych wersji, które są obsługiwane przez większość przeglądarek internetowych. Dzięki temu programiści mogą korzystać z najnowszych funkcji języka, nie martwiąc się o to, czy ich kod działa na starszych przeglądarkach.

6) gulp-uglify ->  służy do minifikacji (zmniejszania rozmiaru) kodu JavaScript. Moduł ten korzysta z biblioteki UglifyJS, która pozwala na zmniejszenie rozmiaru kodu poprzez usuwanie zbędnych białych znaków, komentarzy oraz skracanie nazw zmiennych i funkcji.

7) gulp-imagemin -> służy do optymalizacji obrazów. Pozwala na automatyczną kompresję obrazów, zmniejszając ich rozmiar przy minimalnej utracie jakości. Dzięki gulp-imagemin możesz zoptymalizować obrazy używane w Twoim projekcie, co przyspiesza ładowanie strony internetowej.
 
8) gulp-sourcemaps -> generuje mapy źródłowe (source maps) dla plików CSS i JavaScript. Mapy źródłowe to pliki, które zawierają informacje o położeniu kodu źródłowego w plikach wynikowych, co ułatwia debugowanie i śledzenie problemów w kodzie źródłowym.	

9) gulp-kit -> ułatwia pracę z szablonami HTML. Zapewnia możliwość tworzenia częściowych szablonów, importowania ich i używania w innych plikach HTML. gulp-kit oferuje też inne funkcje ułatwiające manipulację treścią i strukturą szablonów HTML.

W folderze html umieszczamy pliki .kit (1.strona główna, 2.podstronny, 3.szablony) do pracy z kitem:
1)  index.kit
2)  podstronna.kit
3) _szablon.kit  np. _naw.kit _footer.kit
   Improtujemy szablony do strony głównej lub podstronyy za pomocą include/import 
    <!-- @include 'nav.kit' -->   <!-- @import 'footer.kit' -->

*** Do pracy z kitem należy odkomentować linijke 77 i zakomentować linijkie 75 ***

10) gulp-clean -> służy do usuwania plików i katalogów. Jest użyteczny, gdy chcesz wyczyścić katalogi wynikowe przed ponownym uruchomieniem zadań Gulp, aby uniknąć niepożądanych plików.

11) browserSync -> to narzędzie, które pozwala na synchronizację i podgląd zmian w czasie rzeczywistym podczas pracy nad projektem. Zapewnia automatyczne odświeżanie przeglądarki po zapisaniu zmian w kodzie, wspiera podgląd na wielu urządzeniach jednocześnie i oferuje wiele innych przydatnych funkcji do rozwoju stron internetowych.
