# 3D-Visualisierung-von-Kariesl-sionen-aus-Nahinfrarotaufnahmen

## Motivation

Bei einer zahnärztlichen Vorsorgeuntersuchung beschreiben die Zahnärzte bei einer Sichtprüfung
den gesundheitlichen Zustand der Zähne, während die zahnärztlichen Fachangestellten diese
Befunde in einem standardisierten Zahnschema dokumentieren. Zahnärztliche Befunde können
sowohl analog als auch digital archiviert werden. In jedem Fall stellt diese Dokumentation
eine massive Datenreduktion dar, da die zahnmedizinische Fachangestellten die Befunde nicht
wortwörtlich, sondern in Form von Kürzeln und Farben festhalten. Beispielsweise wird ein als nicht
erhaltungswürdig diagnostizierter Zahn mit dem Buchstaben „x“ und ein kariöser Zahn mit dem
Buchstaben „c“ notiert. Eine genaue Begründung, warum der Zahn nicht erhaltungswürdig ist oder
eine örtliche Beschreibung, wo sich die Karies befindet und wie fortgeschritten die Erkrankung des
Zahnes ist, wird in dem von den Krankenkassen vorgesehenen Befundschema nicht festgehalten.
Selbst wenn das Standardbefundsystem um die betroffenen Zahnflächen erweitert wird, fehlen genaue
Ortsinformationen sowie Aussagen zum Schweregrad der kariösen Erkrankung der Zahnfläche.
Ein Problem der rein visuellen Befundung stellen Bereiche dar, die der direkten Sicht nicht
zugänglich sind. Das gilt besonders für den sogenannten Approximalbereich, d. h. dem Bereich
einer Zahnreihe, an dem zwei Zähne in direktem Kontakt sind. Durch Röntgenaufnahmen ist es
zwar möglich, Defekte im Approximalbereich aufzuzeigen, jedoch selbst diese sind aufgrund von
Artefakten und dem Informationsverlust, der durch die zweidimensionale Projektion von sich
überlagernden Strukturen entsteht, oft nicht eindeutig.
Eine vielversprechende Alternative zu den zweidimensionalen Röntgenaufnahmen, die ohne die
ionisierende Strahlung auskommt, ist die Illumination oder die Transillumination mittels NIR. Dabei
wird der Zahn mit nicht sichtbarem Licht in einem Wellenlängenbereich zwischen 0, 78µm bis 2, 0µm
angestrahlt bzw. durchleuchtet. Hierbei dringt das Licht (abhängig von der Wellenlänge
des NIR) nahezu ohne Streuung durch den gesunden Zahnschmelz. Bei kariösen Läsionen wird das
Licht aufgrund des erhöhten Porenvolumens, das bei der Auflösung der Zahnhartsubstanz durch
Stoffwechselprodukte von Bakterien entsteht, stark gestreut. Somit ergeben sich unterschiedliche
optische Eigenschaften, die über eine Nahinfrarotkamera digital als Aufnahme sichtbar gemacht
werden können.
Mehrere Aufnahmen mit NIR aus verschiedenen Blickwinkeln haben das Potential, dass die Tiefe
und die genaue Position der Karies bestimmt werden können. Durch die Möglichkeit,
die Aufnahmen aus verschiedenen Blickwinkeln machen zu können, können dabei approximale
Kariesläsionen mit hoher Wahrscheinlichkeit und ohne schädigende Nebenwirkungen erkannt
werden.
Die Illumination mit NIR ist demnach potentiell eine geeignete und vor allem nichtinvasive Methode,
um die Diagnose der Zahnärzte zu unterstützen. Durch eine Archivierung dieser Aufnahmen bei der
Diagnose (beispielsweise bei der halbjährlichen Vorsorgeuntersuchung) könnte der Datenreduktion
entgegengewirkt werden. Durch die Archivierung wäre es zudem möglich, den Krankheitsverlauf
der Karies zu dokumentieren und auf diese Weise die Kariesaktivität zu bestimmen, die ihrerseits
Einfluss auf die Wahl des richtigen Zeitpunkts einer invasiven Kariestherapie hat.
Im Rahmen einer Therapie können heute Füllungen und Kronen computergestützt hergestellt
werden. Zur Digitalisierung der Zahndaten stehen für diese computergestützte Therapie intraorale
3D-Scanner zur Verfügung, mit denen die Zahnoberflächen digitalisiert und als 3D-Modell ebenfalls
abgespeichert werden können. Durch eine Kombination der NIR-Aufnahmen mit einem solchen
erstellten 3D-Modell wäre es zudem möglich, die Vorzüge einer dreidimensionalen Darstellung der
NIR-Aufnahmen bei der Archivierung zu nutzen.

## Ziele der Arbeit

In dieser Arbeit soll gezeigt werden, dass Nahinfrarotaufnahmen als eine geeignete Methode zur
Unterstützung der zahnmedizinischen Diagnostik eingesetzt werden könnte. Ziel der Arbeit ist es,
eine prototypische Implementierung einer Software für die 3D-Visualisierung von Kariesläsionen
aus Nahinfrarotaufnahmen zu entwickeln. Die Software soll als anschauliche Grundlage dienen, um
die Hypothese zu fundieren. Dabei soll der aktuelle Stand der Forschung untersucht und reflektiert
werden.
Die Arbeit entsteht in Kooperation mit der Ludwig-Maximilians-Universität München (LMU
München) und beabsichtigt, deren Ergebnisse und entwickelte Technologien der Forschungsarbeit
in diesem Bereich zu nutzen und auf diesen aufzubauen.
Für die Arbeit sollen ausschließlich frei verfügbare Technologien eingesetzt werden.

