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

In this documentation I would like show in general, what is my game Zombie Attack about, what will be its assumptions and what are the main points and what is the purpose of this game.
First of all Zombie Attack is dedicated for people with good manual skills with nerves of steel who are hardworking and with mobilization to keep beating new records.
The main thread will be Apocalypse of zombies, monsters and other creatures as well as the fight against us, as a single hero trying to defend the world from destruction. We should strive for killing as many monsters as possible, and try to reach the highest number of points by transforming into brave soldier. Character (the player) will have to come to therms with the fact that the number of zombies will increase and the difficulty level will become increasingly higher in each second. The game is created by me by using Python. The general sketch will looks as follows:

X- our hero, Y- weaker zombie, Z- strong zombie

Analyzing this sketch we can see that the hero is attacked by two kinds of creatures: Y- weaker and slower zombies and Z- faster and more powerful zombies. For killing each of them we will receive points which during the game will be added together and sum up. The main objective is to achive as many of them as possible. It's worth to add, that with every second, the game will be more difficult by a larger crowd of zombies who will multiply much faster and also move faster. In addiction, the shooting mutant plants will be introduced to the game, as in the image below. Note: if your game line exceeds more than 10  creatures, we die.
 The atmosphere of the game will be created by moody, gloomy music and proper landscape (probably forest). Artwork will be made probably in Gimp or Photoshop, based on the designs of the other well known and popular games.

TECHNOLOGY
Zombie Attack is created by me in high level of programming language, namely by Python. Main reason for choosing this one, not the other, was primarily the fact that this is my favourite language in which I find myself the best. In addiction, I decided to use the popular, but at the same time very effective pyGame library, which is the collection of Phytons modules to create online games using SDL libraries; pyGame works on multiple operating systems and multiple architectures. Phyton uses many brands such as:  Google, Yahoo, Nokia, IBM or NASA to their worth many millions dollars applications and projects. Microsoft and Apple offer full support for Phyton in their operating systems and development platforms. Many websites such as YouTube is written in Python. Games and applications that use 3D technology you can create using Python. A common solution is to share in Phyton API game engine written in C/C++. In Phyton, we have access to several engines to support 3D graphics, 2D and other components needed for his type of application- PyGame, PyCrystal (API na CrystalSpace), Python-Ogre (API na Ogre 3D), pyopengl (API na OpenGL).
I will base strictly on Phyton, without combining into this other related programming languages.


Bibliograpgy:
- Make Games with Pytohn -Sean. M. Tracey
- Beginning Game Development with Python and Pygame Will McGugan
- python.rk.edu.pl
- youtube.com
