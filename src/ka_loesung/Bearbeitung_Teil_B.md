Buchen - Teilnehmender
Feststellung der Kardinatität (mengenmäsige Zusammenhang)
--> Eine Sätze unbedingt anwenden 2-seitige Betrachtung
1. Ein Teilnehmender kann eine oder mehrere Buchungen vornehmen (haben) (N)
--> Eine Buchung wirde von genau einem Tielnehmer vorgenommen (1)

Merke:
Im Faller einer 1:N Beziehung landet das Primärschlüsselattribut des Entitätstyp mit der Kardinalität 1 (idTeilnehmer) als Kopie im Entitätstyp mit der Kardinalität N (Buchungen)


Kurse - Termine
1. Ein Kurs werden ein oder mehrere Termine zugeordnet (N) 
2. Ein Termin kann einem oder mehreren Kursen zugeordnet werden (M)

Merke im Falle einer N:M (viele : viele) wird die Komplixität des Sachverhalten aufgelöst indem zusätzliche Datenbanktabelle (Entitätstyp) einfügt wird. Diese Zusammenhangstabelle ergasst die Kopie der fremdschlüseel werte in Kombination erfasst. Die Kombination ist eindeutig (identifizierend) in der Zusammenhangstabelle (Kurse_hatTermine) und bildet dort einen kombinierten Primärschlüssel. Das ist immer so bei einer N:M Beziehung (Kardinalität) Aus N:M wird immer 1:N und N:1

Kurse - Lehrkraefte
Eine Lehrkraft kann einen oder mehrere Kurse betreuen. (N)
Ein Kurs kann im Team von einem oder mehreren Lehrkräften betreut werden.(M)



Kurse - Buchungen
1. Eine Buchung wird einem Kurs zugeordnet (1)
2. Einem Kurs werden mehrere Buchungen zugeordnet (N)