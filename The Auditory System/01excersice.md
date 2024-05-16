## 01 Signalerzeugung

Erzeugen und plotten Sie ein Sinussignal mit der Amplitude umax = 1V, das bei der Abtastrate fs = 20 Hz mit der Frequenz f = 1 Hz um den Gleichanteil uDC = 0.5V oszilliert und 2 s dauert.

Hinweis: Generieren Sie zunächst einen Stützstellenvektor `n = [0, . . . ,N − 1]` und dann über `ti = n[i]/fs` einen Zeitvektor. Das Sinussignal ergibt sich schließlich durch `u(t) = umax · sin (ωt) + uDC`.
