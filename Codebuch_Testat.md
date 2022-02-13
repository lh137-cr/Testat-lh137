# CODEBUCH

## Datenerhebung
Die Daten wurden erhoben von: 
https://www.bundestag.de/dk
https://www.wikipedia.de/
https://www.fdp.de/
https://www.spd.de/
https://www.gruene.de/
https://www.bundestag.de/webarchiv
https://www.bundestag.de/abgeordnete
https://www.facebook.com/lindnermdb/
https://www.instagram.com/tobias.lindner.mdb/?hl=de
https://gruene-rlp.de/personen/tobias-lindner/
https://www.auswaertiges-amt.de/de/aamt/leitung/staatsminister-lindner/1698158
https://www.gruene-bundestag.de/abgeordnete/infos-zur-person/tobias-lindner
https://www.tobias-lindner.de/
https://www.youtube.com/channel/UCPKVP45qWygTLMztFVMtLFg
https://www.instagram.com/rischwasu/?max_id=1636461084789390075&hl=uk
https://twitter.com/rischwasu
https://www.facebook.com/schwarzeluehrsutter/
https://www.bmuv.de/ministerium/leitung/rita-schwarzeluehr-sutter/lebenslauf-der-parlamentarischen-staatssekretaerin-rita-schwarzeluehr-sutter
https://www.spdfraktion.de/abgeordnete/schwarzeluehr-sutter
https://xn--schwarzelhr-sutter-u6b.de/
https://www.youtube.com/channel/UC9qmo_oUU5i7sRSxSsJ4asQ
https://twitter.com/fbrantner?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor
https://www.facebook.com/fbrantner/
https://www.instagram.com/franziska.brantner/?hl=de
https://www.youtube.com/user/floriantoncar
https://www.instagram.com/floriantoncar/?hl=de
https://twitter.com/florian_toncar?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor
https://www.facebook.com/FlorianToncarMdB/
https://www.fdp.de/person/florian-toncarhttps://www.bundesfinanzministerium.de/Content/DE/Standardartikel/Ministerium/Leitung/Staatssekretaere/florian-toncar.html
https://www.toncar.de/
https://www.bmwi.de/Redaktion/DE/Dossier/Visitenkarten/Brantner/lebenslauf.html
https://www.franziska-brantner.de/ueber-mich/vita/
https://www.bundestag.de/abgeordnete
https://www.bundestag.de/webarchiv
https://www.abgeordnetenwatch.de/
https://www.fdp.de/person/jens-brandenburg
https://www.linkedin.com/in/jens-brandenburg/?originalSubdomain=de
https://www.abgeordnetenwatch.de/profile/jens-brandenburg
https://www.instagram.com/jens.brandenburg/?hl=de
https://twitter.com/JBrandenburgFDP?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor
https://www.bmbf.de/bmbf/de/ueber-uns/die-leitung-des-hauses/dr-jens-brandenburg/dr-jens-brandenburg.html
https://www.bundestag.de/webarchiv/abgeordnete/biografien19/B/518586-518586
https://www.jens-brandenburg.de/
https://www.gruene-bw.de/wahlen/bundestagswahl-2021/landesliste-fuer-den-bundestag-2021/
https://www.facebook.com/christian.kuehn.tuebingen
https://www.instagram.com/christian.kuehn.tuebingen/?hl=de
https://www.gruene-tuebingen.de/partei/gruene-im-bundestag/
https://twitter.com/ChrisKuehn_mdb?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor
https://www.gruene-bundestag.de/abgeordnete/infos-zur-person/chris-kuehn
https://chriskuehn.de/
https://www.michaeltheurer.eu/mensch-michael/vita/
https://www.instagram.com/michael_theurer/?hl=de
https://www.facebook.com/michael.theurer/
https://twitter.com/eutheurer?lang=de
https://www.fdp.de/person/michael-theurer
https://www.michaeltheurer.eu/
https://www.facebook.com/Cem/
https://www.instagram.com/cem.oezdemir/?hl=de
https://whoswho.de/bio/cem-oezdemir.html
https://www.bmel.de/DE/ministerium/minister/bm-oezdemir.html
https://www.bundesregierung.de/breg-de/bundesregierung/bundeskanzleramt/bundeskabinett/1974064-1974064
https://www.gruene-bundestag.de/abgeordnete/infos-zur-person/cem-oezdemir
https://twitter.com/cem_oezdemir?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor
https://www.oezdemir.de/
https://benjamin-strasser.de/files/Sonstiges/CV-Strasser_Homepage.pdf
https://www.youtube.com/channel/UCljyb8eqt_obrYszd1SGLIA
https://www.instagram.com/bstrasser/?hl=de
https://twitter.com/bstrasser?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor
https://www.facebook.com/strasser.fdp/
https://www.bundestag.de/abgeordnete/biografien/S/strasser_benjamin-858068
https://benjamin-strasser.de/home
https://twitter.com/tobiaslindner?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor

## Edgelist
Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).

*from* definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort

*to* definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc.

*relationship*definiert die Art der Beziehung: 

1 = Achtung: Regierung umfasst auch Staatsekretäre und das Bundeskanzleramt, etc. hier sollte als Knoten das entsprechende Ministerium angegeben werden.

2 = aktuelle und ehemalige politische Funktionen in politischen Ausschüssen, Gremien und der Partei. etc. Das können auch frühere Stationen gewesen sein, z.B. Geschäftsführer:in einer Partei, etc.

3 = umfasst alle Mitgliedschaften in NGOs, Stiftungen, Gedenkstätten, etc: werden im Bundestagsprofil als Körperschaften öffentlichen Rechts bezeichnet.

4 = Beteiligung an Unternehmen durch Mandate, etwa Aufsichtsratsmandate, Gremien, etc.

5 = erhalten Stipendien (egal wann), etwa Deutsche Studienstiftung, Parteinahe Stiftungen, Internationale Organisationen im In- und Ausland etc.

6 = ausgeübte Berufstätigkeiten, falls vorhanden

7 = Studien- bzw. (längere) Aufenthaltsort(e) in In- und Ausland"

*year* Bezieht sich auf das Jahr, in dem die Variable relationship erhoben wurde

## Nodelist
Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.

*id* eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird. Wird als Initialen des Vor- und Nachnamen erfasst; bei Organisationen eine sinnvolle Abkürzung 

*name_short* Nachname der Person / Name der Organisation

*name* Vollständiger Name

*type* 0=Person, 1=Organisation/Ort/Verband

*sex* Geschlecht: 0=divers, 1=weiblich, 2=männlich

*birth* Geburtsjahr (Personen) 

*position* jetzige Position: 0=parlamentarischer StaatssekretärIn , 1= Staatsminister , 2=Bundesminister

*education* höchster Bildungsabschluss: 0= 2. Staatsexamen, 1=Promotion, 2=Magister, 3=Diplom, 4=Doktor

*subject* Fachrichtung bei Studium/PRomotion: 0= Rechtswissenschaften, 1=Politikwissenschaften, 2=Reformfähigkeit der Vereinten Nationen, 3=Betriebswissenschaften, 4= Wirtschaftswissenschaften 5=Sozialpädagogik, 6=Volkswirtschaft"

*party* Parteizugehörigkeit: 1=SPD, 2=Grüne, 3=FDP

*religion* Religion: 0=katholisch, 1=evangelisch, 3=muslimisch

*kids* Anzahl der Kinder

*twitter* Anzahl der follower auf Twitter

*instagram* Anzahl der Follower auf Instagram

*facebook* Anzahl der Follower auf Facebook

*youtube* Anzahl der Abonnenten auf YouTube
