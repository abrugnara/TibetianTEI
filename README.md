# TibetianTEI Albert Brugnara
Dieses Repository ist Teil des Lehrmaterials für die Lehrveranstaltungen und BA- und MA-Arbeiten des Institut für Südasien-, Tibet- und Buddhismuskunde [(ISTB)](https://stb.univie.ac.at/)
Das Repository enthält Darstellungen von TEI-kodierten diplomatischen Ausgaben von tibetischem Unicode-Text in einem Browser. Die Markierungen sind so konfiguriert, dass auch tibetischer Text mit Faksimile-Bildern im traditionellen Pecha-Format angezeigt werden. Das in den editionen angewandte TEI-Kodierungsschema wurde in Übereinstimmung mit den TEI P5-Richtlinien für die Kommentierung besonders tibetischer historischer Werke, Kolophone oder Textauszüge auf diplomatische Weise mit nur einem einzigen Textzeugen entwickelt. Allerdings wurde dieser Textzeuge mit anderen abgeglichen und notwendige Korrekturen markiert. Die Kodierung deckt die Markierung grundlegender redaktioneller Merkmale, historischer Einheiten und Daten sowie übersetzter Teile und Fachterminologie ab, Ebenso die tibetische Syntax (siehe Dokumentation zur Markierung unten).

Die aktuelle Anpassung ist inspiriert von der Online-TEI-bp-Ausgabe von James Beresfords Übersetzung der Aeneis von Virgil, kodiert und digital veröffentlicht von William Dorner, University of Central Florida. Die Funktion "Übersetzung anzeigen/ausblenden" ist der Textansicht von W. Dorner nachempfunden. Die Faksimile-Anzeige oberhalb des Textes ist inspiriert von einem Blogbeitrag von Charles Riondet, TEI Boilerplate: Anzeige eines Faksimiles neben einer Transkription.
Dies wurde nun weiterentwickelt nach den Mustern der österreichischen Nationalbibliothek der Notitzbücher von Peter Handke https://edition.onb.ac.at/context:hnb


Grundlegendes TEI-Markup für tibetische historische Texte (diplomatische Editionen) /br

    divisions: <div>...</div>
    paragraphs: <p>...</p>
    line breaks: <lb/> 
    lines: <l>...</l>
    line groups: <lg>...</lg>
    headings: <head>...</head>

    gaps: <gap></gap>; e.g. <gap extent="4" unit="letters"></gap>
    unclear sections: <unclear>...</unclear>
    translation part: <div type="translation"><p xml:lang="de">...</p></div>; e.g. <p xml:lang="whylie">...</p>
    special terminology in the translation (Sanskrit or Tibetan): <term>...</term>; e.g. <term>pravrajyā</term>
    corrections: <choice><sic>...</sic><corr>...</corr></choice>; e.g. བསམ་<choice><sic>གྱི་</sic><corr>གྱིས་</corr></choice>མི་ཁྱག་་་་
    regulations: <choice><orig>...</orig><reg>...</reg></choice>

    annotations (by the author/scribe): <gloss>...</gloss>
    dates: <date>...</date>; e.g. <date when="1446">མེ་ཕོ་སྟག་གི་ལོ</date>
    persons: <persName>...</persName>; e.g. <persName type="BUDA" key="P3183">རྡོ་རྗེ་གདན་པ་ཀུན་དགའ་རྣམ་རྒྱལ་དཔལ་བཟང་པོ</persName>
    places: <placeName>...</placeName>; e.g. <placeName type="BUDA" key="G2800">ལྷ་ས</placeName>
    work titles: <title>...</title>; e.g. <title type="RKTS" key="3219">བྱང་ཆུབ་སེམས་དཔའི་སྤྱོད་པ་ལ་འཇུག་པའི་ལེགས་པར་སྦྱར་བ</title>།"
    
    Annotation für tibetische Syntax
    komplexe Sätze
    Wortarten
    Suffixe / Partikel
    Erklärungen
    
