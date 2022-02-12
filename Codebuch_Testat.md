CODEBUCH,
"Im Codebuch definieren Sie, wie und nach welchen Kriterien erfasst werden.",
Achtung: das Codebuch wird immer als eigene Datei in Github gesetzt. Beispiel siehe hier.,
Wert,Kommentar
edgelist,Grundregel: Die Edgelist darf pro Spalte immer nur einen Wert enthalten. Bis auf die ID idealerweise numerisch codiert (als Zahl).
from,"definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, nur ein Wort"
to ,"definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. Keine Sonderzeichen, etc. "
,
relationship,"definiert die Art der Beziehung: 1 = Achtung: Regierung umfasst auch Staatsekretäre und das Bundeskanzleramt, etc. hier sollte als Knoten das entsprechende Ministerium angegeben werden.

2 = aktuelle und ehemalige politische Funktionen in politischen Ausschüssen, Gremien und der Partei. etc. Das können auch frühere Stationen gewesen sein, z.B. Geschäftsführer:in einer Partei, etc.

3 = umfasst alle Mitgliedschaften in NGOs, Stiftungen, Gedenkstätten, etc: werden im Bundestagsprofil als Körperschaften öffentlichen Rechts bezeichnet.

4 = Beteiligung an Unternehmen durch Mandate, etwa Aufsichtsratsmandate, Gremien, etc.

5 = erhalten Stipendien (egal wann), etwa Deutsche Studienstiftung, Parteinahe Stiftungen, Internationale Organisationen im In- und Ausland etc.

6 = ausgeübte Berufstätigkeiten, falls vorhanden

7 = Studien- bzw. (längere) Aufenthaltsort(e) in In- und Ausland"
year,"Bezieht sich auf das JAhr, in dem die Variable relationship erhoben wurde"
nodelist,Grundregel: die IDs der Nodelist müssen mit den IDs der Edgelist komplett übereinstimmen. Ausprägungen der Attribute in der Regel numerisch definieren.
id,"eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird. Wird als Initialen des Vor- und Nachnamen erfasst; bei Organisationen eine sinnvolle Abkürzung "
name_short,Nachname der Person / Name der Organisation
name,Vollständiger Name
type,"0=Person, 1=Organisation/Ort/Verband"
sex,"Geschlecht: 0=divers, 1=weiblich, 2=männlich"
birth,Geburtsjahr (Personen) 
position,"jetzige Position: 0=parlamentarischer StaatssekretärIn , 1= Staatsminister , 2=Bundesminister"
education,"höchster Bildungsabschluss: 0= 2. Staatsexamen, 1=Promotion, 2=Magister, 3=Diplom, 4=Doktor"
subject,"Fachrichtung bei Studium/PRomotion: 0= Rechtswissenschaften, 1=Politikwissenschaften, 2=Reformfähigkeit der Vereinten Nationen, 3=Betriebswissenschaften, 4= Wirtschaftswissenschaften 5=Sozialpädagogik, 6=Volkswirtschaft"
party,"Parteizugehörigkeit: 1=SPD, 2=Grüne, 3=FDP"
religion,"Religion: 0=katholisch, 1=evangelisch, 3=muslimisch"
kids,Anzahl der Kinder
twitter,Anzahl der follower auf Twitter
instagram,Anzahl der Follower auf Instagram
facebook,Anzahl der Follower auf Facebook
youtube,Anzahl der Abonnenten auf YouTube
