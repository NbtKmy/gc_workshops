---
marp: true
paginate: true
footer: "Nobutake Kamiya: Intro für den Workshop"

---
<style>
@import 'default';
/* Bootstrap */
@import url('https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css');
@import url('https://fonts.googleapis.com/css2?family=Kosugi&family=Roboto+Mono&display=swap');

:root {
  --theme-yellow: #FEDE00;
  --theme-red: #DC6027;
  --theme-blue: #0028A5;
  --theme-grey: #A3ADB7;
}
header {
  width: 100%;
  height: 80px;
  position: absolute;
  left: -1px;
}
.header_2nd {
  border-bottom: 2px solid var(--theme-grey);
}
.img_links {
  position: relative;
  left: 20px;
}
.img_rechts {
  position: relative;
  left: 800px;
}
section h1 {
  font-size: 2.65rem;
  color: white;
}
section h2 {
    color: var(--theme-blue);
}
.text_white {
    font-size: 1.65rem;
    color: white;
}
.bg_grey {
    position: relative;
    left: -80px;
    width: 1600px;
    height: 520px;
    background-color: var(--theme-grey);
    text-indent: 100px;
    line-height: 200px;
}

</style>
<header>
<img src="./uni_img/header_links.png" height=80% class="img_links"/>
<img src="./uni_img/header_rechts.svg" class="img_rechts"/>
</header>

# Hands-on Workshop
<div class="text_white"><b>Intro</b><br>
Nobutake Kamiya</div>

![bg 100%](./uni_img/hintergrund_1page.jpg)

---

<header class="header_2nd">
<img src="./uni_img/header_links.png" height=80% class="img_links"/>
<img src="./uni_img/header_rechts.svg" class="img_rechts"/>
</header>

## Was wollen wir von dem Workshop heute mitnehmen?
- Ein wenig Coding kennenlernen
- Coding ist nicht schwer und macht Spass!
- Coding an sich ist aber noch keine "Forschung"

---

<header class="header_2nd">
<img src="./uni_img/header_links.png" height=80% class="img_links"/>
<img src="./uni_img/header_rechts.svg" class="img_rechts"/>
</header>

## Zum Beginn des Workshops...
... sollen wir kurz die folgenden Themen anreissen...

- Qualität der Ergebnisse
- Copyright und Lizenzen
- Nutzung der API

---


<header class="header_2nd">
<img src="./uni_img/header_links.png" height=80% class="img_links"/>
<img src="./uni_img/header_rechts.svg" class="img_rechts"/>
</header>

## Qualität der Ergebnisse
- Anforderung für "akademische" Forschung 
- Datenmanegement für Nachvollziehbarkeit
- Open Science

Hier auch [Kodex von DFG](https://www.dfg.de/foerderung/grundlagen_rahmenbedingungen/gwp/) ([Zusammenfassung der Uni Magdeburg](https://www.fdm.ovgu.de/Gute+wissenschaftliche+Praxis+OVGU+Magdeburg.html)) nütztlich!

---

<header class="header_2nd">
<img src="./uni_img/header_links.png" height=80% class="img_links"/>
<img src="./uni_img/header_rechts.svg" class="img_rechts"/>
</header>

## Copyright und Lizenzen
- Copyright der Datensätze / Softwarelizenzen beachten und richtig zitieren
- Copyright/Datenschütz/Nutzungsrichtlinie bei KI 

---

<header class="header_2nd">
<img src="./uni_img/header_links.png" height=80% class="img_links"/>
<img src="./uni_img/header_rechts.svg" class="img_rechts"/>
</header>

## Nutzung der API
- API-Schnittstelle nicht zu sehr belasten
- Wenn möglich, zitieren!

---

<header class="header_2nd">
<img src="./uni_img/header_links.png" height=80% class="img_links"/>
<img src="./uni_img/header_rechts.svg" class="img_rechts"/>
</header>

## Google Colaboratory / Google Colab
- Webbasierte Entwicklungsumgebung
- Man braucht "nur" einen Google-Account
- ...Sonst braucht man keinen weiteren Prozess, um die Entwicklungsumgebung einzurichten.
- GPU-Anwendung möglich


---


<header class="header_2nd">
<img src="./uni_img/header_links.png" height=80% class="img_links"/>
<img src="./uni_img/header_rechts.svg" class="img_rechts"/>
</header>

## Google Colaboratory / Google Colab - Erster Schritt
1. Bei Google einloggen
1. [Diese Einführungsseite](https://colab.research.google.com/notebooks/intro.ipynb) besuchen 
1. "File" > "New notebook" klicken
1. Dem neuen Notebook einen Namen geben und speichern
1. Das Notebook ist jetzt im Ordner "Colab Notebooks" in Google Drive zu finden

--- 


<header class="header_2nd">
<img src="./uni_img/header_links.png" height=80% class="img_links"/>
<img src="./uni_img/header_rechts.svg" class="img_rechts"/>
</header>

## Google Colaboratory / Google Colab - Ausprobieren!
1. Code- und Text-Zeile
1. Im Text-Feld kann man mit [Markdown](https://daringfireball.net/projects/markdown/) schreiben
1. Im Code-Feld kann man Python-Code schreiben, aber man kann auch Shell-Befehl ("!" vorne) oder Magic-Befehl ("%" vorne) ausführen

__Lass uns einfach ausprobieren!__