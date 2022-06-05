# **Oasis**

![Oasis](./ReadmeImages/TitleImage.png)

---

**Name:** Dennis Hawran

**Betreuer:** Prof. Jirka Del'Oro-Friedl

**Semester:** WS 2021/22

---

## **Inhalt**
[Einführung](#einführung)

[Konzeption](#konzeption)

[Geschichte](#kurz-geschichte)

[Solar Level](#solar-level)

[Constellations Level](#constellation-level)

[Moon Level](#moon-level)

[Trailer](#trailer)

[Bilder](#bilder)

[Credits](#credits)

---

## **Einführung**
Diese Arbeit wurde im Rahmen einer Studienarbeit im WS 2021/22 erstellt. Es wurde ein VR-Spiel entwickelt welches später in einem haptischen VR-Raum installiert und gespielt werden soll. Bei dem haptischen VR-Raum geht es darum keine Controller zur Steureung in der virtuellen Umgebung mehr zu benötigen.
Dafür wird es echte Gegenstände geben, welche in die Hand genommen werden können und mit welchen die virtuelle Welt manipuliert werden kann.
Das Tracking jener Objekte soll mittels einer Tracking-Software von [OptiTrack](https://optitrack.com/) erfolgen. Dazu werden Kameras im Raum und Marker an den Objekten platziert. Die Kameras werten dann kontinuierlich die Position und Rotation der Marker aus und geben die Daten an eine beliebige andere Software weiter. 

Ziel dieser Arbeit war nicht die Implementierung in den VR-Raum, sondern ausschließlich die Vorbereitung. Die Implementierung soll später, im Rahmen einer Bachelor-Thesis, erfolgen.


Verwendet wurde in dieser Arbeit die [Unreal Engine](https://www.unrealengine.com/en-US/?utm_source=GoogleSearch&utm_medium=Performance&utm_campaign=an*3Q_pr*UnrealEngine_ct*Search_pl*Brand_co*DE&utm_id=15913918984&sub_campaign=&utm_content=July2020_Generic_V1&utm_term=unreal%20engine) 4.27 für das erstellen des Spiels. Zum erstellen und manipulieren der verwendeten 3D Modelle wurde [Blender](https://www.blender.org/) 3.1.2 verwendet. Außerdem wird zum entwickeln sowie zum Spielen die Software von [Steam](https://store.steampowered.com/about/) und das [SteamVR Plugin](https://store.steampowered.com/app/250820/SteamVR/) gebraucht.

---

## **Konzeption**
Das Spiel ist eine Art Escape Room mit dem Ziel alle Rätsel zu lösen. Um diese Rätsel zu lösen müssen die getrackten Gegenstände im Raum benutzt werden. Da die Studienarbeit aber nicht im Raum selbst entwickelt wurde, war es nötig die Objekte zuerst mit den Controllern manipulieren zu können. Dabei wurde bei den Iteraktionen darauf geachtet dass die Aktionen später auch ohne Controller  funktionieren werden (Aufheben, Bewegen, Drehen, Ablegen).

Es spielt in einer magischen fantasie Welt über den Wolken. Das Thema _Magie_ wurde ganz bewusst gewählt. Das Thema ermöglicht es die reale Welt mit komplett fiktiven Inhalten zu ergänzen und so die Immersion zu steigern. So können Objekte vor dem Nutzer schweben, an einem anderen Ort wieder auftauchen und kreativere Spielmechaniken implementiert werden.

Geplant waren vier verschiedene Demo Rätsel welche alle unterschiedliche Möglichkeiten des haptischen VR-Raums aufzeigen sollen. Zum Zeitpunkt der Abgabe sind drei davon konzipiert und realisiert.

---

## **(Kurz-)Geschichte**
Über den Wolken befindet sich ein magisches Tor welches dazu dient alle Seelen zur **Oasis** zu bringen damit diese ihren Frieden finden können. Dieses Tor wurde zerstört und die vier Bäume des Lebens sind verwelkt. Als magischer Gelehrter ist es nun deine Aufgabe mithilfe der vier Relikte die magische Energie ins Portal zurück zu bringen und dafür zu sorgen, dass die Geister ihren wohl verdienten Ruhestand antreten können.

---
---
>## **ACHTUNG:** Es folgen **Spoiler**. Nachfolgend sind die Rätsel mit ihren Lösungen aufgelistet.
---
---

## **Solar Level**
Beim Solar Level bekommt der Nutzer ein Schwert zur Verfügung gestellt. Um ihn herum tauchen mehrere Runensteine sowie Kristalle auf. Die Kristalle dienen zur Lichtbündelung und generieren einen Lichtstrahl. Die Runensteine dienen dazu die Kristalle zu aktivieren.

Mithilfe des Schwertes können die Lichtstrahlen abgelenkt werden. Lenkt der Nutzer einen Lichtstrahl auf einen Runenstein ab lädt sich dieser auf und wechselt in einen anderen Zustand. Jeder Runenstein hat insgesamt drei Zustände. Nur in einem Zustand jedoch aktiviert dieser den nächsten Kristall. Sind alle Kristalle aktviert gilt das Level als gelöst und der Nutzer steigt weiter nach oben zum nächsten Level.

Das Level ist sehr hell gestaltet und soll einen sonnigen Nachmittag darstellen.

> Ziel dieses Levels ist das erste zurechtfinden mit den Objekten im VR-Raum. Der Nutzer kann das Level allein mit dem Bewegen und Rotieren des Schwertes lösen. Aus diesem Grund wird dem Nutzer auch keine Lösung in dem Level versteckt. Er soll einfach ausprobieren und ein Gefühl für das Objekt bekommen.

---

## **Constellation Level**
In diesem Level bekommt der Nutzer ein Buch. Außerdem tauchen Sonnen auf. Zwischen den Sonnen befinden sich wolkenartige Pfade welche anzeigen dass die Sonnen verschiedene Plätze einnehmen können. In dieser Version des Spiels folgen die Sonnen der eigenen Hand wenn diese in die Nähe kommt und fliegen immer zum letzten passierten Platz zurück sobald die Hand des Nutzers den Einflussbereich der Sonne verlässt. In der Version für den VR-Raum soll der Nutzer echte Kugeln in verschiedene Positionen bringen.

Das Buch ist in diesem Level ersteinmal Nutzlos. Das heißt es hat keine Funktion mit welcher der Nutzer das Level manipulieren kann. Erst durch genaues betrachten des Objektes findet der Nutzer auf dem Buch die Lösungen an welchen Positionen die Sonnen platziert werden müssen.

Dieses Level spielt in düsterer Umgebung und soll eine Nacht darstellen. Lediglich die Sonnen erhellen die Umgebung und zeigen durch ihr hervorstechen dem Spieler das diese Objekte wichtig zum lösen des Levels sind.

> In diesem Level geht es darum mehrere Objekte gleichzeitg in der Hand zu haben und zu koordinieren (Buch und Sonne). Außerdem wird der Spieler angehalten sich intensiver mit seinen Objekten zu beschäftigen und sie genauer anzuschauen. 

---

## **Moon Level**
Im Moon Level wird der Nutzer, ausgenommen des vor ihm schwebenden Dolches, mit leere Konfrontiert. Um ihn herum scheint ersteinmal nichts zu sein. Sobald der Nutzer mit dem Dolch eine schnelle Angrifsbewegung macht erzeugt dieser eine Energiewelle. Trift diese Energiewelle auf ein sich im Raum befindendes Objekt wird dieses für kurze Zeit sichtbar. 

Die Objekte dieses Levels sind Bruchstücke eines Mondes. Ziel ist es alle Bruchstücke zu finden und zu einem kompletten Mond zusammenzufügen. 

Auch in diesem Level umgibt den Spieler die Nacht, jedoch ist die Umgebung schon etwas heller als beim Constellation Level und spielt somit kurz vor dem Sonnenaufgang.

> Durch die Verteilung der Bruchstücke im gesamten Raum soll der Nutzer relativ viel herumlaufen. Dies erweckt den Eindruck wirklich über den Wolken zu schweben und viel Platz zu haben.

---

## **Life Level**
> TODO

---

## **Ende**
Nach jedem gelösten Level wird eine Sequenz abgespielt in welcher der zum Level gehörende Baum des Lebens wieder mit magsichen Blüten erstrahlt. 

Sind alle Bäume wiederhergestellt wird der Nutzer zum letzten Plateau geführt und es startet die Endsequenz. Hier vereint sich die Magie der vier (momentan drei) Bäume und öffnet das Portal zur **Oasis** erneut. Die Geister können nun endlich durch das Portal fliegen. 

---

## **Trailer**

![Trailer von Oasis](./ReadmeImages/Oasis%20Renderv1.m4v)

---

## **Bilder**
![Portal ungelöst](./ReadmeImages/Portal_Ungel%C3%B6st.jpg)
![Relikte](./ReadmeImages/Relikte.jpg)
![Solar Level](./ReadmeImages/Solar_Level.jpg)
![Constellations Level](./ReadmeImages/Constelaltions_Level.jpg)
![Life Level](./ReadmeImages/Life_Level.jpg)
![Portal gelöst](./ReadmeImages/Portal_Gel%C3%B6st.jpg)

---

## **Credits**

### **Musik**
Hier nochmal ein großes Dankeschön an Joshua Hank für die Komposition und Erstellung der In-Game Musik und Sounds!


### **3D Modelle**
* "Elemental stones" (https://skfb.ly/6WsSI) by Mandrake is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* "tree" (https://skfb.ly/6Zu6M) by - is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* "Golden Daïm staff" (https://skfb.ly/6RQBo) by Evie Verstappen is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* "Set Ghibli style rocks" (https://skfb.ly/oowQW) by CoFate is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* "The Altar (object №1)" (https://skfb.ly/6YDCp) by salinaforr is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* "Stone table" (https://skfb.ly/6WTwv) by DerpDelfinen is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* "Ghost Puppets" (https://skfb.ly/6XtxG) by Vera is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* "Book of Constellations" (https://skfb.ly/6zoBs) by Athikar is licensed under Creative Commons Attribution-NonCommercial (http://creativecommons.org/licenses/by-nc/4.0/).
* "Ebonchill Magic Sword" (https://skfb.ly/6AA96) by Athikar is licensed under Creative Commons Attribution-NonCommercial (http://creativecommons.org/licenses/by-nc/4.0/).
* "European and American game scence~Magic portal" (https://skfb.ly/6TJNF) by chengzijieczj is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* "Waystone" (https://skfb.ly/6WPQ6) by HenryBoadle is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* "Fantasy Sword" (https://skfb.ly/oozUW) by EliecerPinto is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* "Fey Tree house" (https://skfb.ly/YEJR) by AislingJane is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
