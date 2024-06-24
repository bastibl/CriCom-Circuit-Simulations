# CriCom Circuit Simulations

Dieses Dokument stellt eine Ergänzung zu den in der Vorlesung vorgestellten Schaltungen dar. Es soll zum besseren Verständnis der Elektrotechnik Grundlagen beitragen und zum Experimentieren mit verschiedensten Schaltungen dienen. 

Dabei bieten wir eine fertige Schaltung an, die in *CircuitJS1* gebaut wurde und möchten mit zwei bis drei Fragen das Verständnis vertiefen. Dabei kann mit den Schaltungen experimentiert werden und Parameter nach Belieben geändert werden. 

Gerne können auch weitere Schaltungen erstellt werden und in einem Github Repository bei SEEMOO hinterlegt werden. Sollte uns Fehler unterlaufen sein können diese unter [kontakt@seemoo.de?]() gemeldet werden. 

- Ein Einstieg in Schaltungen und ET-Gundlagen
- zum selbst ausprobieren bauen und verstehen
- kennenlernen des Circuit Simulators von Falstad
  - interessantes Tool um Schaltungen jeglicher Art zu bauen und ein besseres Verständnis von Elektrotechnik zu bekommen



## Schaltungen aus Kapitel 2: Grundlagen Elektrotechnik

### Schaltungssimulation: Strom- & Spannungsteiler

Der hier dargestellte Strom- und Spannungsteiler ist von Folie 38 aus Kapitel 02: Grundlagen Elektrotechnik. Die Schaltung findet ihr in: `spannungsteiler.circuitjs.txt`

![Spannungsteiler](/Users/joshua/university/M.Sc.IT Security/CricomTutor/circuit simulation (1cp)/cricom-circuit-simuations/gfx/Spannungsteiler-labeled.png)

**Fragen:**

1. Sucht euch die Formel raus und berechnet den Spannungsabfall an jedem Widerstand. 
2. Überprüft eure Berechnung mit der Simulation und probiert gerne noch ein paar Werte aus. 
3. Was stellt Ihr fest, wenn Ihr den Plot betrachtet? Wie viel Ampere ist jeweils an den Punkten A1, A2 und A3? 



### Beispiel: Kondensator

Auf Slide 45 findet ihr ein Beispiel zu Kondensatoren der auf dem Breadboard nachgebaut werden kann. Die Schaltung findet ihr in `kondensator-frage9.circuitjs.txt`

![Kondensator Beispiel](/Users/joshua/university/M.Sc.IT Security/CricomTutor/circuit simulation (1cp)/cricom-circuit-simuations/gfx/Kondensator Beispiel.png)

1. Welchen Einfluss hat die Kapazität des Kondensators auf die Leuchtdauer der LED? 



### Spule DC

- slide 55 spule [DC](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcA2aYDMZIA5nrzgEzYCcICk55lCApgLRhgBQAbiCciOvh18gBYowgTWGUYCZgGUQhBFzACh8-kMoQAZgEMANgGdawwswDufEILmjL65gCcLPLqu68Noh3IVuuoys7CSpBmcgDshLYg-lEh5jFWMYEhut6Kymm+wujg0CSkJCRhuNgIpfiQYQxgkSEA9iBh4MQikIVQsGAkCJjyHfBtYcgKfZSRTejM6NiNIABiEBrgEIwgAJIAdgAmAK4AxgAu2ht7tMxAA) & [AC](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcAWaAmAzAgbBjB2BSfZBNBADhASVsmoFMBaMMAKADdx9sRzewPEBXr0IyeklFRoCNgCduvESDzLpYEWwDuSvjlUZe-KGwA2h9Zf29RskExiQwATkzECFFwjDPICfFMAe1UQbGQoEAkXF3A7SHJItFCMNgwqDBAAMQg7CARoCBYQAEkAOwATAFcAYwAXAEMymoY2IA) (spule-dc.circuit.txt, spule-dc.circuit.txt)
- Die Schaltung findet Ihr in `spule-dc.circuitjs.txt`

![spule-dc](gfx/spule-dc.png)

**Fragen:**

1. Wie wirkt sich die Induktivität der Spule auf Spannung und Strom aus, wenn der Schalter links liegt? Also beim "laden" der Spule. 
2. Wie wirkt sich die Induktivität der spule auf Spannung und Strom aus, wenn der Schalter rechts liegt? Also beim "entladen" der Spule.



### Spule AC

Datei: `spule-ac.circuitjs.txt`

![spule-ac-high-low-inductance](gfx/spule-ac-high-low-inductance.png)

**Fragen:**

1. Wie wirkt sich die Induktivität der Spule auf Spannung und Strom aus, wenn der Schalter links liegt? Also beim "laden" der Spule. 
2. Wie wirkt sich die Induktivität der spule auf Spannung und Strom aus, wenn der Schalter rechts liegt? Also beim "entladen" der Spule.



### Kondensator AC

In dieser Schaltung möchten wir herausfinden wie sich der Kondensator bei Wechselspannung verhält. Ladet dazu die Schaltung `kondensator-ac.circuitjs(1).txt`. 

![Kondensator AC](gfx/Kondensator AC.png)

1. Wie wirkt sich die Kapazität des Kondensators bei Wechselspannung auf den Strom aus? 
2. Wie wirkt sich die Kapazität des Kondensators auf die Spannung aus?



## Schaltungen aus Kapitel 3: Elektrotechnik, Filter und Dioden

### Bandsperre

Auf slide 21 findet ihr eine Aufgabe zum Entfernen des 50-Hertz-Netzbrummen. Öffnet die [Schaltung](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcsDMYBM6EA4GTClgOwBsJIeFFkFApgLRhgBQATiFuStgCwg8k+3PjTCRmAd36CQwkCXRDeUNvMWzlCviQTlR8ZgGNpSvgLMBOPVFjx8HaD0gIBYlCgv5PI2ywA2JvxWgTrWMHYQ4fgoCBboVvGKJHHo2HqSatq6IdniUuby2ZyF6QDmHNmhFeQk2NhQKgBu1Rp8xVWi1FQ0PdAIzAD2HPIi4O5gZtAWeDxEYhZ1RNy1SFH2NOjDKMxAA) `Aufgabe-Bandsperre.circuitjs.txt` und findet mit den Slidern einen möglichen Wert für die Spule und Kondensator, sodass bei *out* nur noch ein minimales Brummen zu vernehmen ist. (Lösung: C = 1.0132mF, L = 10mH)

![Aufgabe-Bandsperre](gfx/Aufgabe-Bandsperre.png)

### Anwendung: Gleichrichtung

Auf Folien 47 und 48 findet ihr ein Anwendungsbeispiel eines [Einweggleichrichtung mit und ohne Ladekondensator](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3YBMBWEAWZ0DsY1pwMyIBsAHAJyTkjKQ013ICmAtGGAFBjGLql1ZSaEMSy9Bw3gBMmAMwCGAVwA2AFxbKmU8FF0xInAM4ixICSH4ChekAuWGmHAE4nx10b3J5dYeBwDGFnBm1pYgXsJ0+vAQiNCIlJRIgpAE+GDU0ZwA7kF0Ea7h3pAcAOY0WMRFwsiV4XVRHLke1RVVBSW5te3eaPytJQDyfFbCfQIEVY3DLeazk3ocAB7oGCYQ5DwmYyCIwgCiAJYAdtlMpaWah-4AFk7XN6qKx6UAOoYAtoeqAPQA9jdjkx3gAZeQyADWf2OMmOhnkqj+Tg4ADcRiExv0Ojo0IwbDBkBw-hZdsgpugqKRwtByLS6bSsARyN0INEDLpPFAOEA) (`Einweggleichrichtung-mit-ohne-Kondensator.circuitjs.txt`). 

![Einweggleichrichtung mit-ohne Kondensator](gfx/Einweggleichrichtung mit-ohne Kondensator.png)

1. Welchen Einfluss hat der Kondensator in der Schaltung? 
2. Was passiert, wenn sich die Kapazität des Kondensators ändert? 



### Filter

Im folgenden sind einige Beispiele und Simulationen von Filtern. Jede Schaltung ist online aufrufbar und kann als text-Datei in CircuitJS geladen werden. 

Man erkennt anhand der Plots gut wie die Input Frequenz im output gefiltert wird. 



#### RC Tiefpass Filter

Bei dem [RC Tiefpass Filter](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcAWaAOZYDMYEE4xIAmBAdgDZyIFIQka6BTAWjDACgBzEco5EUhh58QaMOShR2AJxDJy-cggm9FyyVhqR2AY2FqVIwf1qo8LNCGapxpLArjkskZFjx4osSBwAecyBJ4RJZOHng4cuCWRJAAVAA2APacAPqEABSkAGoA9IRZAJQAOgDORQCOAH6lzFgAJgBCWex+yN4geKSkAkTdeGimUSAAXtAN0ABcpQBmKZylFaVgOUQADgCWsVjQCADWAPIAFgC2sch4AHYAYgvlpUFoABLD7GCkpgo86pgq6lh0tBicDong4+30Xwk7wMkm0rXwdAQ-3wtAQ3xAIgASgBhUoAFXWjGmqwAhiUSuxEiCsERJG1+jwdkiJDB4BBAdTKTwQDS6ZAGXhoG95N5OqQ+N4KJ42eBwOwgA) erkennt man gut, wie die Spannung sinkt, wenn die Frequenz steigt. Ladet die Schaltung (`rc-tiefpass.circuitjs.txt`) und probiert mit den Werten für Widerstand und Kondensator aus, um bessere Ergebnisse zu erzielen. 

![rc-tiefpass](gfx/rc-tiefpass.png)

#### RL Tiefpass

Den [RL Tiefpass Filter](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcAOaAmA7MgnGB-kA2MAFgwTRAUiqpoQFMBaMMAKAA8RDISRlW-bJQF8+YZCDSQAVABsA9gHMA+mEgAKDADUA9Ou0BKADoBHJgGYAJgCFtxgM4BXAHZKGAMwAnACwBObEogGISShAiEwaHcyJI0kJzc1CAkyBbBWClEKVJ8AEoAMkwAKgCWngAOAIYODmx+UWERjVQkfDQScGxySZEIbS397eBQsJBohCRwhJOQCHgYIZEJYBg04X0DPJJDIOnSUvC0MOwA8oMDaZS78WwKtBaUNFPYktjQ2J9fr69TZEgweAQGjXPZ3bh7J4pSCvEDvL4vbAWDAWZEIZDtMaQCA4thAA) findet ihr in `rl-tiefpass.circuitjs.txt`

![rl-tiefpass](gfx/rl-tiefpass.png)

#### Tiefpassvergleich

Datei: `tiefpassvergleich.circuitjs(1).txt`

Beim [Tiefpassvergleich](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcBmWBOA7AFjA5AmMSADjGIDYIFIQlraBTAWjDACgAPEfYtcSNBBx8iaLCHH5xAMwD6AcwA6AZ0UBHFdUgAJAF5t5-KSHLGix8gnJQonWuWISC-LEizI33cQCUAwkwAVAEsGaQAHAENlVWUAN2VoFW8AGUCQ8KiY+MTlZP9g0MjotgAnI3FTcXNxBDB8GyJINgAbEEF62vrq2jqbGEhkMmQQJn6PMEHyDAw0MWISfHqmwwQ0esraNZMrPpbt6wxicUPjo77oQcdR2EgEDEWKBCOsDAR8Q6WDEBO2jAOzxqOGhNADGm3WxlWHV6wJu8EuIFQtWQUzQpjA5EEswQ4n6kHYZSw5BqvShPSW-CaAHlweT9nSaOwad1OvxiI5WcC2GCfsRnD9MNYaKgyMwMCMENAppQ+aw0QgrKwoDd2AB3b5nPn1H4-Jrq3nOXjWLW2MpGkAm82ChrwNjqq1-DXia3Ui1oi3Oa0mrlgDA0Ikk+pYOB04b4RnwWjK9i+mjtOlHDm9MMRkNIGAxv30n5kn4pyk0dPQdgAe34iIpwbQjjQ0DQKPlgj9WGIGAgePxNmGSsZ4povhLAFsAEZBAB2DAAJioqQBXAAuYQXyjYZbIFZsVY5ytu4G44EcyDYQA) vergleichen wir drei Tiefpass-Filter. Der linke Plot stellt den Output der drei Filter kombiniert dar, während rechts die Input-Frequenz zu sehen ist. Hier könnt ihr die Werte der verschiedenen Teile einstellen und mit anderen Filtern vergleichen. 

![Tiefpass Vergleich](gfx/Tiefpass Vergleich.png)





#### LC Bandpass

Datei: `lc-bandpass.circuitjs.txt`

Hier ist eine einfache Version des [LC Bandpass Filters](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWECAstIIEwDZsHZNJ8MAOZSZc5AUwFowwAoAYxBIGZM243O2SKg9BDABOWHhSiwJHOxSzUKKMMYBzXlxIDNIaV0GMANiDyRlAihy08hkCJmiYU2FOzyiMLzKLxRGAB4g+EhmFmKmkH7KziAAMgDCADoAzgBCAIYAdgAmAA4ZKSmMYGaRFjzYCNjcFOwghA3wlDBMAPK6lnpgNoL+APYgynwUKJCiZOKi09NgY+wIeCQu9TDwEBRcw4yDSCND42Rg5tAkizVrcCLgjEA). 

![lc bandpass](gfx/lc bandpass.png)

#### RC Hochpass vs. RC Tiefpass

Datei: `rc-tiefpass-vs-hochpass.txt`

HIer ein Vergleich von [RC Hochpass und RC Tiefpass](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWEAmZ0FmQdgCw4QgBz4LZIKQjmUICmAtGGAFADmIOcIhYAbB12KEoUZgCcUCfrykDKM-pTCFIzAMZyQCzT0VRY8CDByowAZj5MAnMh48++uCwAeKHFnCRMVBB7BekHDcUSAAqABsAe1YAfX8ACiwANQB6fySASgAdAGcsgEcAP1z6MwATACEk5ldkPE9SLSxhfwIOYIAvaAroAC5cgDMY1lyC3LAU5AAHAEtQs3QAawB5AAsAW1CcKwA7ADFR-NybQgAJDrZuB10r-iERVQ1eQmFtG+1KGHgvEAXfM14cEIz1IBCwSC+XnEty0shuN0oZjMNV+YCsVGQ0nqpHRQTqIAASgBhegAFRmtAGUwAhjk8jkAG45aC5Yn0U6RNSrGl05hgLCUZCybT86SyMwhTxcCHQFj8+QvWHSfHaCXIJTwKj6FjLTTaHC8IIfUS695wlRKh7MSIgdFmZAiThWYRWaBWd0e92EBDuXgOyE-QW236Eknkyk8+kASR2UwArgAXa3gCD2x2QZ0cN3OlS8JEUFRWXCOJwiCBs8NU2n05aJ+NJm3+X7+gSZ3joBAAks-CAOpsStkcrmR3Ix+vJ7xpyhO4QLbDPbsQJeh9mc7nV3K1hPjoA). 

![rc-hochpass-vs-tiefpass](gfx/rc-hochpass-vs-tiefpass.png)



#### LC Bandsperre 

Datei: `lc-bandsperre.circuitjs.txt`

Hier findet ihr die [LC Bandsperre](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBMcUHYMGZIA4UA2ATmIxAUgpABYqEBTAWjDACgAbEbQvcFPjz4oUNKFGhIYcGmRw8E2UsVkJCUNgGNuvECLFDuacdPjYw5GHkhg8NGmASYwNvHmIS47AE561-QV0wAXEXSDYAeR0+YL4abBQAkzYAc2ijKkNsJ2SLKhR-WL1RJOw9fPhqGHYADz0eEEJ1JXISWj0xABkAYQAdAGcAIQBDADsAE36ABwZvbwY2AHtqBPE6Yj4pWHgyQjUC8USkMoBLUaXuIzXIDeRPHYw9wgOICEWAVwAXNgALcFC2EA). Mit der dargestellten Einstellung greift die Sperre bei ca. 900Hz. 

![lc-bandsperre](gfx/lc-bandsperre.png)

### Weitere Filter

Falstad selbst bietet einige Schaltungen zu passiven Filtern an. Diese sind unter *Circuits -> Passive Filters* zu finden. Hier hat man die Möglichkeit eine *Cutoff Frequency* einzustellen und sieht wie sich die Werte der Bauteile anpassen. Neben Erklärungen zu Funktion der Schaltung, gibt es einen *Frequency Response Graph* bei dem man den Breakpoint bei 3dB erkennen kann. 

Hier ist eine Liste der interessantesten Filter: 

- [High-Pass Filter (RC)](https://www.falstad.com/circuit/e-filt-hipass.html)
- [High-Pass Filter Response](https://www.falstad.com/circuit/e-filt-hipass-af.html)
- [Low-Pass Filter (RL)](https://www.falstad.com/circuit/e-filt-lopass.html)
- [High-Pass Filter (RL)](https://www.falstad.com/circuit/e-filt-hipass-l.html)
- [Low-Pass Filter (RL)](https://www.falstad.com/circuit/e-filt-lopass-l.html)
- [Band-Pass Filter](https://www.falstad.com/circuit/e-bandpass.html)
- [Notch Filter](https://www.falstad.com/circuit/e-notch.html)



### Dioden

Oben haben wir schon einen Einweggleichrichter gesehen. Hier setzen wir das selbe mithilfe von Dioden um. 

- [Spannungsbegrenzer](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWEDoE4DMAWATKhl0A2AdnVW0gA5lJkbkBTAWjDACgA3cTTEdBbN15geUcCEy0ktGdARsATkOXoiy2mDhsA7nzUjemQsNGRFE48qO9+gjfB0WbAvpWd3H6N3xfZig2yhHPwCXAx8PAGc9QhU1bEkxWgAzAEMAG0iGT3jEkJAEmRzYwtdeUrMAEwL-ArzawMFKhjSAV3SAFzZqr3cyutomltT2roB5J2UBanCigA8C7HQQYmIJF0pact4AZQAHVIA7Q9bDgHNIgCMGM4UGQ4AvBgU2AHsxSy3IVGppaAhaMtAeAPEA) (`spannungsbegrenzer.txt`)
  - Wie funktioniert der Spannungsbegrenzer? 
  - Wie wirkt sich der Widerstand auf die Spannung aus? 
- [Halbwellengleichrichter](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcBmWBOA7AFjA5AmMSADjGIDYIEkbIQEBTAWjDACgA3cMfEAu1rzTko4EFjpI606AjYAncWBHClI-qPIS2AE25CROFSN46GAMwCGAVwA2AFzYB3fX3x0jb6WwD2mrKISaGj0ULA8UiC8dMi+YlqBkMGhMJARYrwQsUA) (`halbwellengleichrichter.circuitjs.txt`)
  - Wie unterscheiden sich Halbwellen und Vollwellengleichrichter? 
- [Brückengleichrichter](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBMcUHYMGZIA4UA2ATmIxAWwosgoFMBaMMAKADdxDbsEVPbCAFijgQg2klpToCFgHd+IISFzDlkeSshrhq8CjxQWAEy3CwBlYUNhifPsboAzAIYBXADYAXE2ZAoEQisbO38QR1dPH1MUcXBQvQtDB2d3b19Y2ls+PQCglMj0hVzAvx4+DWLtFV5FcqMFTPj7OINDSuDmsTAg7Ib-VrxDQR7-IaMAJ27e0JH88ay4FgAPMUIqWMMEOH8ECGE0EA8AexdjFmORdTFIUmoYSEkw7gv9JWFacTvJWCQIPgsKhYQA) (`brueckengleichrichter.circuitjs.txt`) und [mit Filter](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcBmWBOA7AFjA5AmMSADjGIDYIEkbIQEBTAWjDACgA3cMfEAu1rzTko4EFjpI606AjYAncWBHClI-qPIS2AE25CROFSN46GAMwCGAVwA2AFzYB3fX3x0jb6WwD2mrKISaGj0ULA8UiC8dMi+YlqBkMGhMJARYrwQsUA)
  - Welchen Vorteil bietet der Gleichrichter mit Filter? 
- Weitere Beispiele an Dioden-Schaltungen findet ihr unter *Circuits -> Diods*





## Schaltungen aus Kapitel 3: Elektrotechnik, Transistoren und Oszillatoren

- slide 15 
- slide 33 ff. basisvorspannung nachbauen?
- slide 55 probleme bei hohen frequenzen
- slide 63 555 timer IC 
- 



## Zusatz

### Pong

Wen es interessiert findet [hier](https://www.falstad.com/pong/index.html) eine Simulation des 1972 von Atari erfundenen Spiels Pong. 