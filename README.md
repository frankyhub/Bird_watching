<a name="oben"></a>

<div align="center">

|[:skull:ISSUE](https://github.com/frankyhub/Bird_watching/issues?q=is%3Aissue)|[:speech_balloon: Forum /Discussion](https://github.com/frankyhub/Bird_watching/discussions)|[:grey_question:WiKi](https://github.com/frankyhub/Bird_watching/wiki)||
|--|--|--|--|
| | | | |
|![Static Badge](https://img.shields.io/badge/RepoNr.:-%2023-blue)|<a href="https://github.com/frankyhub/Bird_watching/issues">![GitHub issues](https://img.shields.io/github/issues/frankyhub/Bird_watching)![GitHub closed issues](https://img.shields.io/github/issues-closed/frankyhub/Bird_watching)|<a href="https://github.com/frankyhub/Bird_watching/discussions">![GitHub Discussions](https://img.shields.io/github/discussions/frankyhub/Bird_watching)|<a href="https://github.com/frankyhub/Bird_watching/releases">![GitHub release (with filter)](https://img.shields.io/github/v/release/frankyhub/Bird_watching)|
|![GitHub Created At](https://img.shields.io/github/created-at/frankyhub/Bird_watching)| <a href="https://github.com/frankyhub/Bird_watching/pulse" alt="Activity"><img src="https://img.shields.io/github/commit-activity/m/badges/shields" />| <a href="https://github.com/frankyhub/Bird_watching/graphs/traffic"><img alt="ViewCount" src="https://views.whatilearened.today/views/github/frankyhub/github-clone-count-badge.svg">  |<a href="https://github.com/frankyhub?tab=stars"> ![GitHub User's stars](https://img.shields.io/github/stars/frankyhub)|
</div>




# Bird watching 
### Nach einer Idee von [Alex Kutschera](https://github.com/vektorious)

### Story
Die Blaumeise und die Kohlmeise gehören zu den häufigsten Meisenarten in Deutschland. Sie gehen nicht nur gerne an Futterhäuschen, sondern suchen auch Nistkästen auf, in denen sie Schutz suchen und ihre Familie gründen können. Für jede Vogelart gibt es eine ideale Größe des Einfluglochs. Bei den kleinen Blaumeisen sind das 28 Millimeter Durchmesser, bei den größeren Kohlmeisen 32 und beim Star 45mm Lochgröße. Die Lightburnvorlage ist für Kohlmeisen ausgelegt.  Das Einflugloch sollte in Richtung Ost / Südost ausgerichtet sein. 

Die Kohlmeise ist ein kleiner Singvogel. Sie hat einen schwarzen Kopf, weiße Wangen und gelbes Gefieder an Brust und Bauch, sie sind etwa 11 bis 12 Zentimeter groß und wiegen zwischen 9 und 12 Gramm. Mit der CAM des ESP32 und dem WEB-Server kann man in den Nistkasten das Schlüpfen der Jungvögel beobachten. Die 4 IR-LEDs lassen sich über den WEB-Server ein/aus schalten. Der WEB-Server hat eine feste IP-Adresse: 192.160.0.177. Um den WiFi-Empfang des ESP zu verbessern, wurde die Antenne des ESP32-CAM mit 40cm Litze verlängert. In der Testphase ist mit dem Serielllen Monitor die WiFi-Verbindung und die Schaltvorgänge der IR-LEDs zu kontrollieren. Für die Spannungsversorgung ist ein 5V-Netzteil vorgesehen. Möglich ist auch eine Spannungsversorgung mit einem 18650 Akku, der von einem Solor-Panel gespeist wird.

---

### Der WEB-Server:

![Bild](pic/Bird%20watching2.png)

---

### Serieller Monitor:

![Bild](pic/serieller_monitor1.png)

---


### BOM

| Stück | Bezeichnung |
| ----- | ----------- | 
| 1        | ESP32 CAM      | 
| 1        | ESP32 CAM Shield    | 
| 4        | IR-LEDs 850 nm DC 1,5V 20mA   | 
| 4        | 75R 1/4W  | 
| 1        | 10cm Blankdraht  | 
| 1        | 40cm Litze für die Wurfantenne  | 
| 1        | Schaltdraht      |
| 1        | 5V Netzteil |
| 1        | Vogelhaus: |
| 2        | Sperrholz 4mm 300x600 |
| ----- | ----------- | 

---

[Bauanleitung](https://github.com/frankyhub/Bird_watching/wiki)

---

### Birdhouse aus dem Lasercutter:

![Bild](pic/birdhouse1.png)

### CAM-Bild

![Bild](pic/Bird%20watching4.png)

### Verdrahtung des ESP32-CAM und der IR-LEDs

![Bild](pic/Verdrahtung.png)

![Bild](pic/Dach1.png)


---

<div style="position:absolute; left:2cm; ">   
<ol class="breadcrumb" style="border-top: 2px solid black;border-bottom:2px solid black; height: 45px; width: 900px;"> <p align="center"><a href="#oben">nach oben</a></p></ol>
</div>

---


