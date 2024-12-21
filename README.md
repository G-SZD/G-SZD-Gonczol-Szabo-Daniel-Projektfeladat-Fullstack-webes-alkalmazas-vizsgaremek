# Európai hulladékcsökkentés és élelmiszer hulladék gazdálkodási rendszer
<!-- <img src="img/coverimage.jpeg"> -->
<p>  Az Élelmiszer-hulladék-kezelési projekt koncepciója az, hogy összegyűjti a felesleges élelmiszert az adományozóktól, mint például szállodáktól, éttermektől, nonprofit szervezetektől és szétosztja a rászoruló embereknek. </p>
<h2>Eszközök és technológiák</h2> 
<ul>
 <li>Frontend : HTML, CSS,  JavaScript</li>
 <li>Backend  : php</li>
 <li>webserver: xampp server</li>
 <li>Adatbázis: MySQL </li>
</ul>

 <h2>A rendszer három modulból áll. </h2>
    <ul><li>User</li>
    <li>Admin</li>
    <li>Delivery</li></ul>
   <br>
    <p>A Felhasználói modult azoknak az embereknek tervezték, akik az élelmiszer-pazarlás csökkentése érdekében szeretnék felajánlani a  megmaradt ételeiket. A felhasználói modul felelős azért, hogy elfogadja az élelmiszer-adományokat olyan felhasználóktól, akiknek nagyon sok élelmiszerük van, például éttermektől cégektől vagy magánszemélyektől. A modul lehetőséget kínál a felhasználók számára, hogy regisztráljanak, bejelentkezzenek és élelmiszert adományozzanak. A felhasználók kiválaszthatják az adományozni kívánt élelmiszer típusát és mennyiségét, és a rendszer összeegyezteti ezeket a legközelebbi rászoruló emberekkel vagy szervezetekkel továbbá a modul segítségével a felhasználók megtekinthetik adományaikat is. A Felhasználói modul az Adminisztrációs modul számára nyújt információkat további feldolgozásra.
   </p><br>
   <p>
      Az Adminisztrátor modul a platformon regisztrált trösztök, amelyek a vagyonkezeléssel megbízott holdingok, civil szervezetek és jótékonysági szervezetek számára készült. Az Admin modul az ételosztási folyamatot irányító rendszergazdáknak készült. Az Adminisztrációs modul információkat kap az élelmiszer-adományozásról a Felhasználó modulból, és felsorolja azokat a civil szervezetek és jótékonysági szervezetek számára, amelyek ezek közül választhatnak. Az adminisztrátorok megtekinthetik és kezelhetik a kapott adományok listáját, az adományozott élelmiszerek típusát és mennyiségét. A civil szervezetek és a jótékonysági szervezetek az Adminisztrációs modulból kiválaszthatják a számukra feltétlenül szükséges élelmiszer-adományt, és kérhetik az átvételt a Szállítás modulba. Az Admin modul feladata a kérések nyomon követése és annak nyomon követése, hogy a szervezetek milyen adományokat vettek fel.
   </p><br>
    <p>A kézbesítő modul azoknak a magánszemélyeknek van, akik az élelmiszer-adományozási folyamatban részt akarnak venni az átvételi és kiszállítási szolgáltatások segítségeivel. A kézbesítők regisztrálhatják magukat a platformon. A Delivery Person modul átvételi és leadási szolgáltatásokat nyújt azoknak a civil szervezeteknek és jótékonysági szervezeteknek, amelyek élelmiszeradományt kértek. A kézbesítő modul megmutatja az élelmiszer-adomány felvételének és leadásának helyét.
    </p><br>
    <p>Az Élelmiszer hulladék kezelési rendszert úgy alakították ki, hogy a felesleges élelmiszer elosztását biztosítsa  a rászorulók között. A Felhasználó modul fogadja az élelmiszer-adományokat, az Adminisztrációs modul pedig felsorolja azokat a civil szervezeteket és jótékonysági szervezeteket amelyek közül választhatnak, a Kézbesítő modul pedig átvételi és kiszállítási szolgáltatásokat viszonoz. Ez a rendszer a közösség javát szolgálja az élelmiszer-pazarlás csökkentésével és a rászorulók segítésével.
    </p>
 <p>
Az XAMPP szoftver telepítve van a C:\ meghajtóra a  számítógépembe ahonnan meg lehet nyitni a meglévő, PHP-val készült webhelyeket.
A PHP eredeti jelentése a Personal HomePage volt. De ez most a  Hypertext Preprocessor rekurzív rövidítése. AZ XAMPP mappában van a MySQL mappa ezt megnyitottam majd a bin mappa megnyitása után másoltam ezt az elérési utat C:\xampp\mysql\bin és a keresősávban kerestem szerkesztéseket a rendszerkörnyezeti változók miatt, a megnyitás után a környezeti változókhoz a rendszerváltozónál kerestem elérési utat Path-t duplán kattintottam erre, még egy felugró ablak jelent meg ahol új szakaszba jutottam ahova bemásoltam a meglévő könyvtárból: C:\xampp\mysql\bin 
a bin mappa elérési útját majd az ok-ra kattintottam három alkalommal és így az elérési út bekerült a rendszerkörnyezeti változók közé. 
Telepítettem egy .zip fájlt food-waste-management-system-main néven ami az élelmiszer-hulladék fő kezelési rendszere.
Jobb gombbal kattintottam aztán kiválasztottam - Az összes kibontása… - gombra majd letöltöttem és kicsomagoltam a fájlokat a C:\ meghajtóra C:\Users\Dániel\Downloads. A fájlok kicsomagolásra kerültek az aktuális mappába ahol a .zip fájl is van. Rákattintottam a mappára, ez a fő könyvtár ahol a fájlok vannak. Megnyitottam a Visual Studio Code-ban a projektet amely PHP alkalmazásban van ennek futtatásához jobbra a keresősávban megkerestem a XAMPP vezérlőpultot és elindítottam 
az Apache Port(s) 80,443
és a MySQL Port(s) 3306 szervereket mely a fekete betűknél zöld szimbólummal jelentek meg így a szerverek megfelelően elindultak. Ebben a fájlban megkerestem a database-t, az adatbázist ahol van a demo.sql, megnyitottam ez egy lekérdezés és nem használtam ezt a fájlt szerkesztési célra. Megkerestem a connection.php-t ahol megtaláltam a demo részt.

A böngésző keresősávba beírtam, hogy localhost és megjelent http://localhost/dashboard/
Apache Friends FAQs HOW-TO Guides PHPInfo phpMyAdmin

XAMPP Apache + MariaDB + PHP + Perl

You have successfully installed XAMPP on this system!
És a többi szöveg angolul.
Ez egy webhely ami a helyi gazdagépen fut. Ezt követően beírtam, hogy localhost/phpmyadmin tehát a PHP adatbázis sikeresen meg lett nyitva mert elindítottam a szervereket.
A http://localhost/phpmyadmin/ weboldalon új szakaszra kattintottam a bal felső sarokban és az adatbázis nevébe bemásoltam és beillesztettem a connection.php szöveges részből a demo szót ami az új Adatbázis neve lett és rákattintottam a létrehozás gombra ami mindent megtart alapértelmezés szerint. Itt az importálás szakaszra kattintottam majd kiválasztottam az importálandó fájlt és a Letöltések közül rákattintottam telepített projektre ami a food-waste-management-system-main amely kibontható fájl és a database, az adatbázis mappán belül van a demo.sql fájl ami egy SQL forrásfájl jobb gombbal kattintottam megnyitottam és megjelent phpMyAdmin felületen Importálás az adatbázisba demóba majd a lenti Importálás gomra kattintottam. Minden zöld pipa, minden rendben az összes tábla sikeresen létrejött.
Ezek a táblázatok admin kézbesítők élelmiszer-adományok bejelentkezés felhasználói visszajelzések, így a projekt sikeresen be lett állítva, annyit kellett tenni, hogy a food-waste-management-system-main mappát kiválasztottam kimásoltam és beillesztettem a Helyi lemez (C:) > xampp > htodcs > mappába. A beillesztés után a böngészőt kezdtem megint használni és a food-waste-management-system-main csak a szöveget kimásoltam és a localhost/ után beillesztettem:
localhost/food-waste-management-system-main ami a címsorban http://localhost/food-waste-management-system-main/ jelent meg kattintható weboldal részekkel:

Welcome to Food Donate
Login as
User
Admin
Delivery
A projekt sikeresen megnyílt innen lehet a weboldal használatával bejelentkezni felhasználóként vagy adminként jelszót és emailt regisztrálni.
    </p>
   



