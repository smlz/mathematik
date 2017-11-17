### Präfix-Notation

1. Ergeben sind die beiden Notationen ('normal' und präfix) das gleiche Resultat?
a) `(* 4 2)` $\stackrel{?}{=} ~~  4 \cdot 2 $
b) `(- (+ 4 3) 1)` $\stackrel{?}{=} ~~  4 + 3 - 1$
c) `(* 2 (- (+ 1 2) 3))` $\stackrel{?}{=} ~~  3 * (1 + 2 - 3)$
d) `(+ 1 (+ 2 (+ 3 4)))` $\stackrel{?}{=} ~~ 1 + (2 + 3) + 4$
e) Bei welchen beiden Rechnungen kommt zufällig das gleiche Resultat heraus?
f) Bei welchen beiden Rechnungen sind bis auf die die unterschiedliche  Reihenfolge der einzelnen Rechenschritte identisch?
g) Welche beiden Rechnungen sind absolut identisch?

2. a) Schreibe zwei Rechnungen in normaler Infix-Notation welche, bis auf die Reihenfolge der Rechenschritte identisch sind.
Beispiel: $1 + 2 + 3$ und $1 + (2 + 3)$
_Hinweis_: Verwende mindestens 4 Zahlen und zwei verschiedene Operationen.
b) Übersetzte die beiden Rechnungen in die Präfix-Notation.

3. Welche der folgenden Rechnungen ist eine korrekte Rechnung in der Präfix-Notation mit Klammern? Was ist jeweils das Ergebnis?
(_Hinweis_: Für Rechnungen in der Päfix-Notation sind die Leerzeichen mit `␣` angegeben.)
a) `(*␣3␣(/␣16␣2))`
b) `(-3␣3)`
c) `(␣-␣␣3␣␣␣3␣␣)`
d) `(*␣2␣(-␣(+␣1␣2)␣3)`
e) Überprüfe deine Ergebnisse auf https://scheme.cs61a.org/

### Lösungen

1. a) Absolut identisch
   b) Absolut identisch
   c) Zufällig gleiches Resultat
   d) Gleiche Rechung, aber unterschiedliche Reihenfolge

2. a) $7:6 - 1 \cdot 2+4 = 4 - 2 \cdot 1 + 7:6$
   b) `(+ (- (/ 7 6) (* 1 2)) 4)` = `(+ (- 4 (* 2 1)) (/ 7 6))`
3. a) Korrekte Rechnung. Resultat: $24$
   b) Inkorrekte Rechnung. `-3` ist keine Funktion. Es fehlt wahrscheinlich das Leerzeichen zwischen `-` und `3`.
   c) Korrekte Rechnung. Zu viele Leerzeichen spielen keine Rolle. Resultat: $0$
   d) Inkorrekte Rechnung. Es fehlt eine schliessende Klammer.

@import "../ab-styles.md"
<style>
hr {
  margin-bottom: 32px !important;
}
</style>
