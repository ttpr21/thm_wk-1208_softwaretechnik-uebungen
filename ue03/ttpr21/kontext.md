# Stakeholder und Systemkontext — Terminplaner für die THM

## Stakeholder

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Dozenten | bestimmen, wann Termine bei ihnen gebucht werden können |
| Studierende | bestimmen, welche Angaben ein Termin haben muss|
| IT-Abteilung | gibt an welche Ressourcen in welcher Form zur Verfügung stehen |
| Der Staat | bestimmt die Verarbeitung der Daten durch Gesetze |
| Die THM | entscheidet durch das Budget, den Umfang des Terminplaners |
| Das Sekretariat | will Administrationsrechte haben, um bei Fehlbuchungen umzubuchen und Studierende zu unterstützen |


## Systemkontext

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
|THM Login| System im Betrieb | Der Terminplaner soll kein eigenes Benutzer-Management betreiben, sondern auf die bestehende Authentifizierung zurückgreifen. |
|Feiertage|Ereignis|An Feiertagen darf es nicht möglich, sein Termine zu buchen|
|Raumplan|Dokument|Das System muss den Raumplan beachten, weil möglich ist Präsenztermine zu buchen.|
|Versendung von Mails als Erinnerung / Bestätigung|Prozess|Der Terminplaner soll das bestehende Mailsystem nutzen können um Mails zu versenden.|
|Semesterbetrieb|Prozess|Das System muss beachten, ob gerade Vorlesungen stattfinden, weil es sonst für die Dozenten zu Kollisionen kommt. |

## Irrelevante Umgebung

- Essensplan der Mensa — Zwar gibt es jeden Tag andere Mahlzeiten, die über die THM App eingesehen werden können, aber dies steht in keinem Zusammenhang mit den Sprechstunden.
- Moodle — Der Dateiaustausch wird nicht für die Terminbuchung gebraucht.