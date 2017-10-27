### Mathematische Notationen

Mathematische Rechnungen können auf verschiedene Arten dargestellt werden. Die verbreiteste Darstellung ist zweifelsohne die **Infix**-Notation, bei welcher das Zeichen für die Rechenoperation _zwischen_ zwei Zahlen geschrieben wird. Beispiel: $7 \cdot  5 = 35$

Bei gewissen Taschenrechnern (vor allem HP) ist die **Postfix**-Notation gebräuchlich, bei der die Rechenoperation nach der Eingabe der Zahlen erfolgt. Beispiel: $1~3~+ = 4$

Bei einigen Programmiersprachen (LISP, Scheme) wird die **Präfix**-Notation verwendet, bei welcher die Rechenoperation als erstes geschrieben wird. Beispiel: $-~7~2 = 5 $

1. Wandle die Rechnung jeweils in die anderen beiden Darstellungsformen um.
   <f3>a) $5~7~:$</f3><f3>b) $\cdot~ 1 ~4$</f3><f3>c) $1+ 4 \cdot 7$</f3>

2. Bei der Präfix-Notation werden für die einfachere Lesbarkeit für jede Rechenoperation Klammern verwendet.
Beispiel: $7 \cdot 6 + 1 :  3$ $~~~~\to~~~~$ $(+~~(\,\cdot~~7~~6)~~(\,:~~1~~3)~)$
Wandle die Rechnung in die Präfix-Notation um, und verwende dabei Klammern für jede Rechenoperation.
<f3>a) $2 \cdot (3+ 2)$</f3><f3>b) $7 -4 : 2 +1$</f3><f3>c) \[\frac{5-1}{12}  - 2\cdot(-3)\]</f3>
d) Überprüfe deine Rechnungen auf https://scheme.cs61a.org/

3. Wandle in die Präfix-Notation um, und berechne das Resultat schrittweise. Löse pro Schritt jeweils nur _eine_ Rechenoperation.
a) $2+3\cdot 4-4 :2$
b) \[\frac{2\cdot3 - 1}{10:2} + (3- 2\cdot 2)\]
c) Wie viele Schritte waren jeweils nötig um das Resultat zu berechnen?
d) In welcher Richtung werden die Rechnungen aufgelöst?


4. Für dieselbe mathematischen Operationen werden je nach Kultur- oder Fachbereich unterschiedliche Symbole benutzt. Siehe zum Beispiel https://de.wikipedia.org/wiki/Liste_mathematischer_Symbole#Rechenzeichen.
Damit eine Rechnung am Computer eingegeben werden kann, erfinde für die folgenden mathematischen Operatoren einfache Namen oder Symbole, welche sich auf unserer Tastatur finden lassen.
a) Addition: $+$
b) Subtraktion: $-$
c) Multiplikation: $\cdot$
d) Division: $:$
e) Quadrieren: $12^{2}$
f) Wurzel ziehen: $\sqrt{16}$

@import "../ab-styles.md"
