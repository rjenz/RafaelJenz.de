:::gallery
<a href="#frostline-engine-und-uncounted-isles"><img src="img/projects/frostline.webp?h={hash}" loading="lazy"><p>FrostLine Engine und Uncounted Isles</p></a>
<a href="#longdays-rollenspielsystem"><img src="img/projects/longdays.webp?h={hash}" loading="lazy"><p>LongDays Rollenspielsystem</p></a>
<a href="#password-manager"><img src="img/projects/pw.webp?h={hash}" loading="lazy"><p>Password Manager</p></a>
<a href="#homelab-und-workstation"><img src="img/projects/homelab.webp?h={hash}" loading="lazy"><p>HomeLab und Workstation</p></a>
<a href="#portfolio"><img src="img/projects/portfolio.webp?h={hash}" loading="lazy"><p>Portfolio</p></a>
<a href="#raycaster"><img src="img/projects/raycaster.webp?h={hash}" loading="lazy"><p>Raycaster</p></a>
<a href="#sharpchip8"><img src="img/projects/chip8.webp?h={hash}" loading="lazy"><p>SharpChip8</p></a>
<a href="#tombs-of-horror"><img src="img/projects/toh.webp?h={hash}" loading="lazy"><p>Tombs of Horror</p></a>
<a href="#software-3d-rendering-auf-dem-gba"><img src="img/projects/s3dr.webp?h={hash}" loading="lazy"><p>Software 3D-Rendering auf dem GBA</p></a>
<a href="#dustyroads-minecraft-server"><img src="img/projects/dustyroads.webp?h={hash}" loading="lazy"><p>DustyRoads Minecraft Server</p></a>
:::

***

## FrostLine Engine und Uncounted Isles

Meine eigene Game-Engine mit DX11 3D-Rendering in C#.

Aufbauend auf einer Entity-Component-System Architektur ist diese Engine ein leichtgewichtiges System für die Data-Driven Game-Entwicklung. Dieses Projekt wurde ursprünglich entwickelt, um mehr über die Entwicklung einer Game-Engine zu lernen. Für einen einfachen Zugriff auf low-level APIs, wie DirectX, wird das [Monogame-Framework](https://www.monogame.net/) verwendet. Kritische Engine System, wie z. B. Physically Based Rendering und Physic-Engine, wurden von Grund auf neu implementiert, um mein Verständnis über die verschiedenen Disziplinen in der Entwicklung zu vertiefen. Für Benutzeroberflächen werden wird ein eigenes UI System verwendet mit Maus / Tastatur sowie Gamepad unterstützung.

Mehr über Uncounted Isles, das Spiel welches auf der FrostLine Engine aufbaut, findest du auf der [Projekt Webseite](https://uncountedisles.com) oder [Steam](https://store.steampowered.com/app/2012030/Uncounted_Isles/). Veröffentlichung des spieles ist geplant Q2 2023.

:::gallery
<img alt="FrostLineEngine Logo" src="img/gallery/FrostLine-1.jpg?h={hash}" loading="lazy">
<a href="img/gallery/UncountedIsles-1.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Tageslichtszene in FrostLine" src="img/gallery/UncountedIsles-1_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/UncountedIsles-2.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Godrays in FrostLine" src="img/gallery/UncountedIsles-2_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/UncountedIsles-3.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Shadows und SSAO in FrostLine" src="img/gallery/UncountedIsles-3_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/UncountedIsles-4.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Nachtlichtszene in FrostLine" src="img/gallery/UncountedIsles-4_thumb.jpg?h={hash}" loading="lazy"></a>
:::

***

## LongDays Rollenspielsystem

Ein Pen & Paper Rollenspielsystem, wie [Dungeon & Dragons](https://dnd.wizards.com/).

Zusammen mit Jan Rüger habe ich dieses Rollenspielsystem für meine persönlichen Pen & Paper Gruppen und für meine Videospiele entwickelt. Als einsteigerfreundliches Regelwerk erlaubt es LongDays einem neuen Spieler, innerhalb von wenigen Minuten an fantastischen Abenteuern teilzunehmen. Dabei war es uns jedoch wichtig, dem Erschaffen eines Klischees von (Super)Heldencharakteren vorzubeugen. Dafür haben wir Boni für die Unzulänglichkeiten einer Spielfigur eingebaut, um es für einen Spieler interessant zu machen, sich auf Talente zu spezialisieren. Das Regelwerk wurde für einen postapokalyptischen Schauplatz geschrieben, eine Anpassung für Fantasy-Welten bis zur Sci-Fi Space Opera ist jedoch ohne großen Aufwand möglich. In 2022 habe ich das fertiggestellte Regelwerk zum eigenen Einsatz in einer kleinen Auflage drucken lassen. Character Illustrationen von [Valencia Ayala](https://www.artstation.com/koialamode).

:::gallery
<img alt="LongDays Logo" src="img/gallery/LongDays-1.jpg?h={hash}" loading="lazy">
<a href="img/gallery/LongDays-2.jpg?h={hash}" onclick="openLightbox(event);"><img alt="LongDays Maskottchen Larry und Ana cosplay als Drache und Zauberer" src="img/gallery/LongDays-2_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/LongDays-3.jpg?h={hash}" onclick="openLightbox(event);"><img alt="LongDays Regelwerk Buchcover in Affinity Publisher" src="img/gallery/LongDays-3_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/LongDays-4.jpg?h={hash}" onclick="openLightbox(event);"><img alt="LongDays Regelwerk Seite 'Dice' in Affinity Publisher" src="img/gallery/LongDays-4_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/LongDays-5.jpg?h={hash}" onclick="openLightbox(event);"><img alt="LongDays Regelwerk gedruckte Exemplare" src="img/gallery/LongDays-5_thumb.jpg?h={hash}" loading="lazy"></a>
:::

***

## Password-Manager

Mein persönlicher Passwort-Manager, der Passwörter nicht abspeichert.

Ein Projekt, welches mich fast schon während meiner gesamten Entwicklerlaufbahn begleitet. Mein Passwort-Manager verwendet Hash-Algorithmen in Kombination mit Domain Namen, um mir sicherer und einmalige Passwörter bereitzustellen. Dieses Vorgehen erlaubt es, dass keine Daten auf der lokalen Festplatte oder einem Server gespeichert werden müssen. Aktuell ist der Passwort-Manager eine progressive Web-App, die in Java-Script in Kombination mit VueJS und Vuetify geschrieben ist. Die Installation auf einem neuen Gerät ist damit so einfach, wie das Scannen eines QR-Codes und wird von allen großen Plattformen unterstützt.

Fakt am Rande ist dieses Tool mein persönliches "Hallo Welt". Beim Ausprobieren neuer Programmiersprachen implementiere ich gerne die Algorithmen des Managers sowie eine kleine Benutzeroberfläche, um den Standard einer Programmiersprache ausloten zu können.

:::gallery
<a href="img/gallery/PW-1.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Generieren eines Kennworts mit Password Manager" src="img/gallery/PW-1.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/PW-2.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Seite Einstellungen von Password Manager" src="img/gallery/PW-2.jpg?h={hash}" loading="lazy"></a>
:::

***

## HomeLab und Workstation

Jeder Systemadministrator hat seinen Spielplatz.

Zum Zeitpunkt des Schreibens verwende ich einen Server mit [Unraid](https://unraid.net/) und 32TB HDD speicher. Für das Netzwerk werden [Unifi](https://www.ui.com/) Switches und Wlan Access Points eingesetzt. Mithilfe von [Tailscale](https://tailscale.com/) kann ich jederzeit auf die, in Docker Containern, laufenden Dienste wie [GitTea](https://gitea.io/en-us/) oder [Syncthing](https://syncthing.net/) zugreifen. Das Monitoring für alle meine Dienste im Intra- sowie Internet wird durch [Uptime Kuma](https://github.com/louislam/uptime-kuma) abgedeckt. Dank Offsite Backup auf eigener Hardware und [AWS S3 Glacier](https://aws.amazon.com/s3/storage-classes/glacier/) wird die [3-2-1 Regel](https://www.veeam.com/blog/321-backup-rule.html) eingehalten. Email Server und öffentlich zugängliches Hosting werden aus Sicherheitsgründen über Internet Dienstleister geregelt.

Für die Entwicklung meiner Privaten Projekte verwende ich meine selbstgebaute Wassergekühlte Workstation.

:::gallery
<a href="img/gallery/homelab-1.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Test des Homelab Servers" src="img/gallery/homelab-1_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/homelab-2.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Workstation" src="img/gallery/homelab-2_thumb.jpg?h={hash}" loading="lazy"></a>
:::

***

## Portfolio

Diese Webseite ☝️ sowie die [Uncounted Isles](https://uncountedisles.com).

Meine Portfolio-Website bot mir eine Möglichkeit zur Entschleunigung und auf die Wurzeln der Web-Entwicklung zurückblicken zu können. Kein Backend, kein PHP / NodeJS, kein Sass / Scss, der Focus auf HTML und CSS mit minimalem JavaScript.
Alle Daten liegen auf AWS S3 und sind über AWS CloudFront für das SSL-Zertifikat erreichbar. Texte werden in Markdown geschrieben und bei einem Commit auf Git mithilfe einer kleinen DevOps Pipeline konvertiert und hochgeladen.

***

## Raycaster

Ein Raycaster-Videospiel, inspiriert von den klassischen 3D-RPGs aus den 1990er Jahren.

Als Wochenendprojekt in 2021 und Experiment, ob meine Engine [FrostLine](#frostline-engine-und-uncounted-isles-spiel) flexibel genug für einen anderen Grafikstil ist, wurde dieses Spiel auch der erste Entwurf meines Rollenspiel-Systems [LongDays](#longdays).

:::gallery
<a href="img/gallery/RayCaster-1.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Raycaster, Bäume und NPCs" src="img/gallery/RayCaster-1_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/RayCaster-2.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Raycaster, Ansicht von drinnen nach draußen" src="img/gallery/RayCaster-2_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/RayCaster-3.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Raycaster, einen Feuerball werfen" src="img/gallery/RayCaster-3_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/RayCaster-4.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Raycaster, Menü und Charactersheet" src="img/gallery/RayCaster-4_thumb.jpg?h={hash}" loading="lazy"></a>
:::

***

## SharpChip8

Eine Implementierung von [Chip-8](https://de.wikipedia.org/wiki/CHIP-8).

Eine kleine Herausforderung, die Programmiersprache und virtuelle Maschine Chip-8 in C# an einem Wochenende in 2019 zu implementieren. Mein persönliches Ziel war es, mein Wissen über Byte-Operationen wiederaufzufrischen. Für die Implementierung wurden lediglich die öffentlich verfügbare Spezifikation von Chip-8 zu Rate gezogen.

:::gallery
<img alt="Sharp Chip-8 Logo" src="img/gallery/CHIP-8-1.jpg?h={hash}" loading="lazy">
<a href="img/gallery/CHIP-8-2.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Ein Chip-8 breakout clone" src="img/gallery/CHIP-8-2_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/CHIP-8-3.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Ein Chip-8 snake clone" src="img/gallery/CHIP-8-3_thumb.jpg?h={hash}" loading="lazy"></a>
:::

***

## Tombs of Horror

Ein Prototyp für ein Abenteuer-Kartenspiel.

Tombs of Horror ist ein kleiner Prototyp für ein Abenteuer-Spiel erstellt in 2016, in welchem der Spieler durch einen Dungeon geführt wird, mit dem Ziel, möglichst viel Gold zu ergattern. Dabei wird dem Spieler sein Abenteuer anhand von Spielkarten erzählt. Nach jeder Karte hat der Spieler die Möglichkeit, sein Gold zu sichern und den Dungeon zu verlassen. Das Spiel wurde in [Unreal Engine 4](https://www.unrealengine.com/) für den PC und Smartphones entwickelt, hat aber die Prototypenphase aus mehreren Gründen nie verlassen.
Ursprüngliches Spiel-Konzept von Lukas Pleger.

:::gallery
<a href="img/gallery/TOH-1.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Hauptmenü von Tombs of Horror" src="img/gallery/TOH-1.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/TOH-2.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Einstellungen von Tombs of Horror" src="img/gallery/TOH-2.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/TOH-3.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Kartentisch in Tombs of Horror" src="img/gallery/TOH-3.jpg?h={hash}" loading="lazy"></a>
:::

***

## Software 3D-Rendering auf dem GBA

Software 3D-Rendering auf dem [Nintendo Gameboy Advance](https://de.wikipedia.org/wiki/Game_Boy_Advance).

Ein Experiment und ein älteres kleines Projekt von mir, um einen in C geschriebene Software Renderer auf den Nintendo Gameboy Advance zu portieren. Der Code läuft sowohl in einem Emulator als auch auf der Original-Hardware und kann ein einfaches Dreieck in Perspektive darstellen. Das Ziel war es in 2016, die Plattform für ein Spiel-Projekte auszuloten. Auch wenn es eine spannende Herausforderung ist, mit den Limitationen des Gameboy Advance zu arbeiten, so habe ich mich schlussendlich dafür entschieden, die Idee für Windows umzusetzen.

:::gallery
<a href="img/gallery/S3DR-1.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Dreieck Rendering" src="img/gallery/S3DR-1.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/S3DR-2.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Dreieck Rendering" src="img/gallery/S3DR-2.jpg?h={hash}" loading="lazy"></a>
:::

***

## DustyRoads Minecraft Server

Eine Multiplayer [Minecraft](https://www.minecraft.net/) Modifikation, um das Gamedesign von [DayZ](https://dayz.com/) zu analysieren und zu reproduzieren.

Dieses mehrjährige Projekt war mein bis dato größtes Kreativprojekt im Bereich der Spiele-Entwicklung, mit einem Spitzenwert von 125 Spielern, die gleichzeitig die von meinem Team und mir erschaffene und mit Spielmechaniken gefüllte Welt erkundeten. Mit 15000 einzigartigen Spielern ist DustyRoads mein erstes erfolgreiches Projekt im Bereich der Spiele-Entwicklung. Auch war dieses meine erste echte Erfahrung in den Bereichen der Teamführung und Systemadministration. Ein Team aus ca. 10 Freiwilligen hielt unsere erbaute Welt auf drei Linux Root Servern für unsere Spieler am Laufen. Die Server wurden 2015 abgeschalten.

:::gallery
<img alt="DustyRoads Logo" src="img/gallery/DustyRoads-1_thumb.jpg?h={hash}" loading="lazy">
<a href="img/gallery/DustyRoads-2.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Szene eines eingestürzten Apartmentgebäudes" src="img/gallery/DustyRoads-2_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/DustyRoads-3.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Szene einer überwucherten Brücke mit einer Stadt im Hintergrund" src="img/gallery/DustyRoads-3_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/DustyRoads-4.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Szene eines alten Schwimmbades" src="img/gallery/DustyRoads-4_thumb.jpg?h={hash}" loading="lazy"></a>
<a href="img/gallery/DustyRoads-5.jpg?h={hash}" onclick="openLightbox(event);"><img alt="Überblick über einen Flughafens" src="img/gallery/DustyRoads-5_thumb.jpg?h={hash}" loading="lazy"></a>
:::