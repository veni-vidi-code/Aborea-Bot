# Befehlsliste
Eine Liste aller bisherigen Befehle
## Allgemein
- ```$install$``` erstellt die notwendigen Channels und Rollen
- ```!help``` zeigt dir die Hilfsseite an
- ```!help dungeonmaster``` Befehle für Dungeonmaster
- ```!help Player``` Befehle für Spieler
- ```d Nummer``` Würfelt einen Nummer seitigen Würfel
- ```online?``` Gibt an ob der Bot online ist
-```!randomname``` Schlägt dir einen Namen vor (experimentell, nutzt aktuell https://github.com/skeeto/fantasyname)


## Player
- ```!joingame NAMEDESSPIELS``` Lässt dich einem Spiel beitreten (du solltest in der Anzeige sehen welche Spiele aktiv sind)
- ```!leavegame``` Hiermit verlässt du ein Spiel (Nur für Zuordnungen. Dein Character bleibt gespeichert)
- ```!me``` Gibt dir die notwendigen Infos zu deinem Character aus. Funktioniert nur in Spielchannels in denen du einen Character hast
- ```!lookup @SPIELER``` Zeigt dir die Informationen über den getaggten Spieler an. Nur im Spielchannel
- ```!Fertigkeiten``` Gibt dir eine Liste aller deiner Fertigkeiten an (Kaufen kannst du Fertigkeiten nur direkt nach der Charactererstellung oder einem Levelaufstieg)
- ```!attributekaufen"``` Erlaubt es dir übrige EP Auszugeben
- ```!money @SPIELER``` Zeigt dir den Inhalt deines Geldbeuutels/wenn ein Spieler angegeben wird des Spielers. Hat im Chat des Spieles mit dem Character durchgeführt zu werden
- ```!Inventar @Spieler``` Zeigt das Inventar des Spielers im Gamechannel an/des eigenen Characters sofern dieser zu dem Spiel existiert und @Spieler nicht angegeben wird


## Dungeonmaster
- ```!creategame NAMEDESSPIELS``` Erstellt ein neues Spiel mit dem entsprechendem "
                                      "Namen", inline=True)
- ```!expadd ANZAHL ANWEN``` Hiermit können Dungeonmaster die entsprechenden exp verteilen. Nur im Channel des Spiels möglich. An wen erfolgt über Erwähnungen
- ```!lookup @SPIELER``` Zeigt dir die Informationen über den getaggten Spieler an. Nur im Spielchannel
- ```!Fertigkeiten @SPIELER```  Gibt dir eine Liste aller Fertigkeiten eines Spielers an
- ```!money @SPIELER``` Zeigt dir den Inhalt des Geldbeutels eines Spielers an. Nur im Spielchannel
- ```!money add/remove MENGE WÄHRUNG @SPIELER``` Fügt dem Kontostand des Spielers die Menge der Währung (Mögliche Währungen: MU, KL, TT, GF (Müssen komplett groß geschrieben werden))
- ```!tp MENGE @SPIELER```Fügt für positive Zahlen dem Spieler TP hinzu und zieht für negative welche ab. Hat im Spielchannel durchgeführt zu werden (nicht über maximal hinaus)
- ```!mp MENGE @SPIELER```Fügt für positive Zahlen dem Spieler MP hinzu und zieht für negative welche ab. Hat im Spielchannel durchgeführt zu werden (nicht über maximal hinaus)
- ```!item hinzufügen/entfernen NAMEDESITEMS ANZAHL @Spieler``` value="Fügt dem Inventar das Item hinzu/entfernt es. Ist ANZAHL leer wird sie als 1 angenommen
- ```!Inventar @Spieler``` Zeigt das Inventar des Spielers im Gamechannel an
- ```!sheetsheet``` Zeigt dir Spielhilfen an
- ```!ST / !GE / !KO / !IN / !CH WERT @SPIELER``` Fügt dem betroffenen Spielern den WERT dem jewailigen Attribut hinzu / zieht ihn ab (benutze 0 um den Wert zu sehen anstatt die Boni die du in /lookup siehst
- ```!gottpunkte WERT @SPIELER``` Fügt dem Spieler di Anzahl an Gottpunkten zu
- ```!overwritefertigkeit WERT @SPIELER``` Addiert den Wert auf das Level der Fertigkeit des Spielers
- ```!overwritespruchlisten WERT @SPIELER```  Addiert den Wert auf das Level der Spruchliste des Spielers solange dieser diese Berufsbedingt erlernen darf
- ```!overwritewissen WERT @SPIELER``` Addiert den Wert auf das Level dieses Wissens des Spielers (Hierzu ist es empfehlenswert sich vorher anzuschauen, was dieser bereits erlernt hat. Insbesondere ist Groß/Kleinschreibung relevant!)
