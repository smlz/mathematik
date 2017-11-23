## Rechnen mit Variablen

Das Lösen einer quadratischen Gleichung mit der a-b-c-Formel

$$a \cdot x^2 + b \cdot x + c = 0 ~~~~~~\Rightarrow~~~~~~ x_{1,2} = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

##### Beispiel:
$$x^2 + 2 \cdot x - 3 = 0 ~~~\Rightarrow~~ x_{1,2} = \frac{-2 \pm \sqrt{2^2 - 4\cdot 1\cdot(-3)}}{2\cdot 1} = \frac{-2 \pm \sqrt{16}}{2} = -1 \pm 2$$
$x_1 = 1,~~~~$ $x_2 = -3$

####Die Sprache
##### Folgende Operationen werden unterstützt:
  * `+`: Addition
  * `-`: Substraktion
  * `*`: Multiplikation
  * `/`: Division
  * `sqrt`: Wurzel

##### Es gibt zwei Special Forms:
* `begin`: Führt mehrere Rechnungen hintereinander aus.
* `define`: Speichert einen Wert unter einem Namen ab

#### Der Code
Die folgende Rechung in Präfix-Notation mit Klammern berechnet die Lösungen einer quadratischen Gleichung, und speichert die Resultate unter den Namen `x1` und `x2` ab.
```
(begin
  (define a 1)
  (define b 2)
  (define c -3)

  (define d (- (* b b) (* (* 4 a) c)))

  (define x1 (/ (- (- 0 b) (sqrt d)) (* 2 a)))
  (define x2 (/ (+ (- 0 b) (sqrt d)) (* 2 a)))
)
```

##### Bemerkungen:
1. Die drei Variablen `a`, `b` und `c` definieren.
1. Als Zwischenresultat `d` den Wert unter der Wurzel berechnen.
1. Die beiden Schlussresultate `x1` und `x2` berechnen.

@import "../ab-styles.md"
<style>
hr {
  margin-bottom: 32px !important;
}
p {
  margin-bottom: 0 !important;
  /*adding-bottom: 0*/
}
h5 {
  margin-top: 0px !important;
  margin-bottom: 0 !important;
}
ol > li:before {
  content: counter(item) ".";
  font-weight: normal;
}
</style>
