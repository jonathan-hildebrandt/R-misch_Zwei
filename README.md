# Requirements Engineering - Gruppe II - Use Case Übung + Diagramm

## Anforderung 1

| Abschnitt | Inhalt/Erläuterung |
| --- | --- |
| Name | Medikamenten zum Medikamentenplan des Patients hinzufügen |
| Akteur  | Pflegekräfte, Ärzte |
| Auslöser | Zu einem Medikamentenplan soll ein neues Medikament hinzugefügt werden. |
| Vorbedingung | Ein Arzt verordnet ein Medikament  |
| Fachliche Beschreibung | Ein verordnetes Medikament soll einem Medikantenplan hinzufügt werden. |
| Hauptszenario | Ein/e Pflegekraft/Arzt öffnet den Medimentenplan eines Patienten und wählt aus einer Liste das zu verabreichenden Medikament (mehr Details) |
| Fehlerszenario | Der Medikamentenplan kann nicht abgerufen werden. | 
| Nachbedingung | Medikament wurde hinzugefügt und wird dem Nutzer als Rückmeldung angezeigt. |
| Nachbedingung (Fehlerszenario) | Fehlermeldung, Benachrichtigung des Arztes |

## Anforderung 2

| Abschnitt | Inhalt/Erläuterung |
| --- | --- |
| Name | Einsehen von Patientendaten |
| Akteur  | Ärzte, Pflegekräfte |
| Auslöser | Die Option "Medikamentenpläne" wird im Hauptmenü des Systems gewählt. |
| Vorbedingung | Die Pflegekraft befindet sich in der Nähe von dem Patienten und stellt über das System eine Abfrage für die Patientendaten. |
| Fachliche Beschreibung | Die Daten zu den Patienten werden von den System abgefragt und auf dem Tablet angezeigt. |
| Hauptszenario | Die Patientendaten der nahen Patienten werden zur Auswahl auf dem Tablet angezeigt. Die Pflegekraft wählt den entsprechenden Patienten aus. Eine Abfrage wird an das System gesendet, verarbeitet und schickt die Daten an das Tablet. |
 | Fehlerszenario | Die Patientendaten der nahen Patienten werden zur Auswahl auf dem Tablet angezeigt. Die Pflegekraft wählt den entsprechenden Patienten aus. Eine Abfrage wird an das System gesendet kann aber nicht verarbeitet werden. |
| Nachbedingung | Die Daten werden auf dem System angezeigt. |
| Nachbedingung (Fehlerszenario) | Auf dem System wird eine Fehlermeldung angezeigt und das System bietet die Möglichkeit die Abfrage für die Patientendaten erneut zu senden.|

## Anforderung 3

| Abschnitt | Inhalt/Erläuterung |
| --- | --- |
| Name | Einsehen des Belegungsplans |
| Akteur  | Pflegekräfte/Arzte |
| Auslöser | Pflegekraft/ Arzt möchte den aktuellen Belegungsplan einsehen  |
| Vorbedingung | Der Nutzer wählt im Hauptmenü den Belegungsplan aus. |
| Fachliche Beschreibung | Die Daten der Zimmerbelegungen werden aus dem System abgefragt. |
| Hauptszenario | Eine Abfrage für Daten des Belegungsplanes wird erstellt und an den Server gesendet. Die Abfrage wird verarbeitet und an das Sytsem zurück gesendet. |
| Fehlerszenario | Eine Abfrage für Daten des Belegungsplanes wird erstellt und an den Server gesendet. Die Abfrage kann nicht verarbeitet werden. |
| Nachbedingung | Der Belegungsplan wird angezeigt. |
| Nachbedingung (Fehlerszenario) | Es wird eine Fehlermeldung angezeigt und den Nutzer wird angeboten die Anfrage erneut zu senden. |

## Use Case Diagramm

![Alt text of the image](https://github.com/jonathan-hildebrandt/R-misch_Zwei/blob/main/image.png)
