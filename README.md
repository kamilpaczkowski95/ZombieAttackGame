################ PL

ZOMBIE ATTACK
(Python)

Paczkowski Kamil

   W dokumentacji tej chciałbym poruszyć, czym w ogóle będzie gra Zombie Attack, jakie będą jej założenia, czym się będzie charakteryzować i jaki będzie jej główny cel. 
Przede wszystkim Zombie Attack dedykowane będzie dla osób dobrych zręcznościowo, o mocnych nerwach i mobilizacji do ciągłego bicia rekordów. Głównym jej wątkiem będzie apokalipsa stworów, innych wydziwień, a także walka Nas, jako pojedynczego bohatera próbującego obronić świat przed zagładą. Dążyć będziemy do zabicia jak największej ilości potworów, tym samym nabijając jak największą liczbę punktów, za pośrednictwem wcielenia w wojowniczego żołnierza. Bohater (gracz) będzie musiał pogodzić się z tym, że liczba ich będzie narastała i poziom gry z każdą kolejną sekundą będzie stawał się coraz wyższy, a zarazem trudniejszy. 
Gra tworzona jest przeze mnie przy użyciu Pythona. Ogólny szkic będzie wyglądał w następujący sposób:

X – Nasz bohater   Y- Zombie słabszy     Z-Zombie silny
                          
Analizując szkic widzimy, iż bohater (X) jest atakowany przez 2 rodzaje stworów: Y- słabsi i wolniejsi oraz Z- szybsi i silniejsi. Za zabicie każdego z nich będzie otrzymywał punkty, które podczas całej gry będą sumowane. Głównym celem jest osiągnąć ich jak najwięcej. Warto dodać, iż z każdą kolejną sekundą gra będzie trudniejsza, poprzez większy natłok zombie, którzy będą mnożyć się znacznie szybciej, dodatkowo żwawiej się poruszając. Dodatkowo wprowadzone zostaną strzelające, zmutowane rośliny, jak na obrazku poniżej. Uwaga, jeśli Twoją linię gry przekroczy więcej niż 10 stworów, giniemy.
 
   Atmosfera gry oraz klimat stworzone zostaną przez nastrojową, ponurą muzykę oraz odpowiedni krajobraz, prawdopodobnie las. Oprawa graficzna zostanie wykonana prawdopodobnie w Gimpie, bądź Photoshopie, oparta na wzorach z innych, funkcjonujących i cieszących się popularnością gier.
   

TECHNOLOGIA

  Gra Zombie Attack tworzona jest przeze mnie w języku programowania wysokiego poziomu, mianowicie w Pythonie. Głównym powodem wyboru tego, a nie innego, był przede wszystkim fakt, że jest to mój ulubiony język, w którym odnajduję się najlepiej. Ponadto postanowiłem użyć popularnej, aczkolwiek jednocześnie bardzo efektywnej bilioteki pyGame, co jest zbiorem modułów pythona nastawiony na tworzenie gier internetowych z wykorzystaniem bibliotek SDL; pyGame działa na wielu systemach operacyjnych i wielu architekturach. Pythona wykorzystują m.in.: Google, Yahoo, Nokia, IBM czy NASA w swoich wartych wiele milionów dolarów aplikacjach i projektach. Microsoft jak i Apple oferują pełne wsparcie dla Pythona w swoich systemach operacyjnych i platformach programistycznych. Wiele stron internetowych takich jak YouTube napisane jest w Pythonie.
  Gry i aplikacje wykorzystujące 3D też można stworzyć z wykorzystaniem Pythona. Częstym rozwiązaniem jest udostępnienie w Pythonie API silnika gry napisanego w C/C++. W Pythonie mamy dostęp do kilku silników umożliwiających obsługę grafiki 3D, 2D i pozostałych komponentów potrzebnych do aplikacji tego typu - PyGame, PyCrystal (API na CrystalSpace), Python-Ogre (API na Ogre 3D), pyopengl (API na OpenGL). Ja jednak oprę się ścilnę na Pythonie, nie wplątując w to innych, pokrewnych języków programowania.


Bibliografia:
- Make Games with Pytohn -Sean. M. Tracey
- Beginning Game Development with Python and Pygame Will McGugan
- python.rk.edu.pl
- youtube.com



6 TYGODNIOWY PLAN:

1 tydzień: pierwszy tydzień i pierwsze 10 zmian (commit) poświęcone przygotowaniu dokładnego opisu mojej gry, charakterystyki,            technologii, zarówno w języku polskim jak i angielskim.

2 tydzień (Commit 11,12,13) od 4 marca 2017 roku: dobór odpowiednich bibliotek, dodanie podstawowych zmiennych, zainicjowanie newKindZombies, stworzenie ekranu tytułowego, przygotowanie grafiki gry oraz stworów.

3 tydzień: (Commit 14,15,16): przygotowanie i wprowadzenie odpowiednich czcionek, umieszczenie grafiki w kodzie, umieszczenie dźwięku, dodawanie nowych zombie, wprowadzenie usuwanie poległych, wyświetlanie danych na ekranie głównym.

4 tydzień: (Commit 17,18,19): dodanie strzelania, polepszenie ruchu postaci i zombie oraz ogólnej fabuły, stworzenie ekranu koncowego oraz zakończenia gry.

5 tydzień: (Commit 20): końcowe poprawki, dopracowanie gry, zamknięcie projektu.

----------------------------------------------------------------------------------------------------------------------------

################  ENG
