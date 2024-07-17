# Project "New Interior" 🪑
<div style="display: flex; justify-content: center;">
  <img src="./assets/img/bilder-fuer-readme/desktop.jpg" alt="Project Screenshot">
</div>
<br/>

## Inhaltsverzeichnes
- [Worum Gehts?] <!-- (#Worum-Gehts?) -->
- [Womit und Wie habe ich gearbeitet?]
    - [Programm und Sprachen]
    - [HTML Aufbau]
    - [Meine Wahl im CSS]
- [Erklärung meines Abweichens von der Vorlage]
- [How to Run?]
- [Wobei gab es Schwierigkeiten?]

## Worum Gehts?






## Womit und Wie habe ich gearbeitet?
### Programms und Sprachen
**Markup:**  
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) 
<br/>

**Styling:**  
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
<br/>

**IDE:**  
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)  
<br/>

**Version Control:**  
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)  
<br/>

**Design:**  
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
[link zur Figma-Vorlage:](https://www.figma.com/design/MPdohVt4vXayZ3hI6QEIEV/css_vertiefung_projects_level_3_7-(Copy)?node-id=0-1&t=otjKWbbmrTYyjcn8-0)


### HTML Aufbau
Hier ist eine Stichpuntartige Erklärung zu meinem HTML Aufbau:
1. Ich habe den Header ausgelassen, da sich die "Navigation" (in dem Falle dieser Website auch nur Dargestellt und nicht Funktionsfähig) in der erste section, der Hero-section befindet.
2. Sections haben alle eine Id, diese Id Namen sind später auch die Unterteilung für die CSS. Falls ich es noch geschafft hätte meine idee einer ausklappbaren Navigation zu erstellen, hätte ich die IDs zu eine scroll-Navigation Verwendet und alles verlinkt
3. fürs vereinfachte Styling habe ich Clases erstellt, die sich darauf beziehen in den Kategorien:
    -  Flex: Hier gibt es drei Classes 1. flex_row 2.flex_column und 3. flex_space_between. diese habe ich den einzelnen Divs zugeteilt und kannte sie damit schnell Stylen.
    - Buttons: Hier gibs ein mal den btn_white und den btn_gray um die beiden Buttenarten schnell Stylen zu können und auch allen einen einheitlichen hover effekt zu geben
    - Schriften: hier hat die H2 noch mal eine weiße Class bekommen. das P-tag lies sich auch ohnew class in den sections ansprechen, die h2 leider nicht, somit gab es hier noch eine extra class. zudem habe ich auch 2 IDs vergeben (da sie beide nur im hero vorkommen) für den Titel und den Claim, um ihnen die Spezielle Font zu geben, die nirgendwo anders auftaucht (das bemengelt der Designer-Monk in mir schon die ganze Zeit, das ist eigentlich nicht der Way-to-go beim Design, da es eine schnelle Wiedererkennbarkeit vermindert. Ich weiß, das sollte mich bei der Umsetztung eigentlich nicht Interresieren, aber ich kann  mir das einfach nicht verkneifen). 
    - Parallax und Transparenz: Für die 3. 5. und 7. Section habe ich die classes Paralax verteilt, um nur jeweils die Background-images einfügen zu müssen und nicht jeder diese Sections diesen effekt zu geben, genauso auch bei den Semitransparenten divs, diese haben die class transparent erhalten.  
### Meine Wahl im CSS
Ich habe mich für das klassische  CSS entschieden, da ich mich damit bisher am sichersten fühle, mich sehr drüber freue, dass ich nun (nach einem Monat Code-learning) flüssig arbeiten kann, ohne durchgängig die Codes nachzuschlagen. SCSS hatte ich auch in den betracht gezogen, aber da ich gerne an meinem Windows-Rechner arbeiten wollte und wir die Installation nur auf dem Mac hatten, wollte ich zu dem Anschlussprojekt von Module 1 keine Experimente Wagen, die mir nachher den Kopf kosten könnten.

**Aufbau**
Der Aubau startet mit den eingebetteten Fonts und den Allgemeinen Styles für die ganze Website. Hier gits die Kategorien der Schriften-Styles,  und der sich wiederfindenden classes, zusammengefasst in Parallax, Buttons und Flex-box. Danach folgen die Seperaten section und am ende der Footer. die einzelenen bereiche habe ich mit kommentierten Überschriften gekennzeichnet.

Flex-Box habe ich sehr viel verwendet. Daduruch, dass wir am Montag dieser Woche erst eine Projektarbeit zu dem Thema Flex-Box hatten und das heutige Projekt direkt im Anschluss folgte (Dienstag-Mittwoch), war ich noch sehr darin, alle objekte in Flex zu denken. Zudem war es mit dem flex-warp auch super easy und schnell die passenden Media-Querys zu erstellen.

## Erklärung meines Abweichens von der Figma-Vorlage
Wie oben schon angedeutet, fand ich das Layout ion Figma in manchen Details nicht ganz optimal

bei den Media Queries habe ich beim Tablet die gallerie in zwei spalten angeordnet, alles wie bei der desktop ansicht war sehr klein, also hab ich es so angeordnet

<div style="display: flex; justify-content: center;">
  <img src="./assets/img/bilder-fuer-readme/aenderung_ipad.jpg" alt="Project Screenshot">
</div>
<br/>


mbeim moblie habe ich ein paar schriftgrößen nicht wie in der Vorlage, damit sie mit ihren umlaufenden objekten genügen freiraum haben

<div style="display: flex; justify-content: center;">
  <img src="./assets/img/bilder-fuer-readme/aenderung_mobile.jpg" alt="Project Screenshot">
</div>
<br/>

<div style="display: flex; justify-content: center;">
  <img src="./assets/img/bilder-fuer-readme/auf_iphone1.jpg" alt="Project Screenshot">
</div>
<br/>

## How to Run?
- **Demo:** [Demo-Website: Project-New-Interior](https://anne-sophienehls.github.io/Project_New_Interior_2024-07-16_17/?#hero)
Hier ist ein Mal die Demo meiner Website, um sich diese im Browser anzeigen zu lassen. Um die Codes aber für sich selbst zu bekommen, solle die Repository geklont werden:



## Wobei gab es Schwierigkeiten?