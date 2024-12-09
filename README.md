# Élelmiszerhulladék-gazdálkodási rendszer
<!-- <img src="img/coverimage.jpeg"> -->
<p>  The basic concept of this project  Food Waste Management is to collect theexcess/leftover food from donors such as hotels, restaurants, and distribute to  the  needy people .</p>
<h2>Tools and Technologies</h2> 
<ul>
 <li>Frontend : HTML, CSS,  JavaScript</li>
 <li>Backend  : php</li>
 <li>webserver: xampp server</li>
 <li>Database: MySQL </li>
</ul>

 <h2>The system has three modules. </h2>
    <ul><li>User</li>
    <li>Admin</li>
    <li>Delivery</li></ul>
   <br>
    <p>The User module is designed for people who wish to donate their excess or leftover food to help reduce food wastage.The User module is responsible for accepting food donations from users who have excess food, such as marriage halls, restaurants, or individuals.The module provides users with the ability to register, login, and donate food. Users can select the type and quantity of food they want to donate, and the system will match their donation with the nearest needy people or organizations.The module also allows users to view their donations.The User module provides the information to the Admin module for further processing.
   </p><br>
   <p>
      The Administrator module is for trusts, NGOs, and charities that are registered on the platform. The Admin module is designed for system administrators who manage the food distribution process. The Admin module receives information about the food donation from the User module and lists it for NGOs and charities to choose from.Admins can view and manage the list of donations received, including the type and quantity of food donated. NGOs and charities can select the food donation they need from the Admin module and request a pickup to the Delivery module.The Admin module is responsible for tracking the requests and keeping track of which organizations have taken which donations
   </p><br>
    <p>The Delivery Person module is for individuals who wish to participate in the food donation process by providing pickup and delivery services. Delivery personnel can register themselves on the platform .The Delivery Person module provides pickup and drop-off services for NGOs and charities who have requested a food donation.The Delivery Person module shows the pickup location and drop location of the food donation.
    </p><br>
    <p>Overall, the Food Waste Management System is designed to efficiently manage excess food and ensure that it is distributed to those in need. The User module accepts food donations, the Admin module lists them for NGOs and charities to choose from, and the Delivery Person module provides pickup and drop-off services. This system benefits the community by reducing food waste and helping those in need.
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
   



