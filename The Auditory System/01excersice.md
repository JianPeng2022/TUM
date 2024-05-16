## 01 Signalerzeugung
Erzeugen und plotten Sie ein Sinussignal mit der Amplitude umax = 1V, das bei der Abtastrate $f_s$ = 20 Hz mit der Frequenz $f$ = 1 Hz um den Gleichanteil $u_{DC}$ = 0.5V oszilliert und 2 s dauert.
Hinweis: Generieren Sie zunächst einen Stützstellenvektor `n = [0, . . . ,N − 1]` und dann über `$t_i$ = n[i]/$f_s$` einen Zeitvektor. Das Sinussignal ergibt sich schließlich durch `u(t) = $u_{max}$ · sin (ωt) + $u_{DC}$`.

These parameters are observable in the plot clearly. For instance, the DC value of the signal should be 0.5 V and it has a maximum of 1.5 V ( = max(sin) + dc = 1 + 0.5). The signal has 2 cycles within 2 seconds. The signal is plotted either from 0 to 1.95 s or from 0.05 to 2 s but not from 0 to 2 s.

