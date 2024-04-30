# CriCom Circuit Simulations

Dieses Dokument stellt eine Ergänzung zu den in der Vorlesung vorgestellten Schaltungen dar. Es soll zum besseren Verständnis der Elektrotechnik Grundlagen beitragen und zum Experimentieren mit verschiedensten Schaltungen dienen. 

Dabei bieten wir eine fertige Schaltung an, die in *CircuitJS1* gebaut wurde und möchten mit zwei bis drei Fragen das Verständnis vertiefen. Dabei kann mit den Schaltungen experimentiert werden und Parameter nach Belieben geändert werden. 

Gerne können auch weitere Schaltungen erstellt werden und in einem Github Repository bei SEEMOO hinterlegt werden. Sollte uns Fehler unterlaufen sein können diese unter [kontakt@seemoo.de(?)]() gemeldet werden. 

Tobt euch aus :) 



## CircuitJS1

CircuitJS1 ist ein Simulator für elektrische Schaltungen entwickelt von Falstad. Das Tool ermöglicht es einem beliebige Schaltungen zu bauen und zu testen. Neben einigen [Beispielen](http://falstad.com/circuit/e-index.html), gibt es auch einen Abschnitt über [Elektrotechnik Bascis](http://falstad.com/circuit/directions.html) und ein kurzes [Manual](https://www.memphis.edu/et/publications/index.php). Es gibt eine  [Online Version](http://falstad.com/circuit/) und auch eine [Standalone Oflfine Version](http://falstad.com/circuit/offline:). Welche Ihr gerne verwendet bleibt euch überlassen. 

In subdirectory `/circuits` findet ihr alle in diesem Dokument gebauten Schaltungen als `.txt`-Datei, die ihr online sowie offline importieren könnt, um mit Schaltungen zu experimentieren.



## Schaltungen aus Kapitel 2: Grundlagen Elektrotechnik

- slides 13, 14 als einstieg (kurzschluss, aber warum?) -> high potentials 
- slide 27 Frage #7 
- slide 29 stromteiler
- slide 38 schaltungssimulation zu [Strom-/Spannungsteiler](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBMcUHYMGZIA4UA2ATmIxEO2QpRAQFMBaMMAKADdwxbtC8vaAFn6QoIQaLCjpUaAlYB3AeP4oJKqKwBOINaOG71aEcnjbDo4xZC8TUs0pY8+125oDy1q7kG784TSU9DUFsIRFFVxdQ5widGJCw8BQ7eEhzBO5+BKtJNIykqxy8VLN4wpLxJLc8s09MlPFiQmT+CHT6wv9BZr82jyraFOze4YD0oA)
- slide 45 [Beispiel Kondensator](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcA2aYDMZIA5nrzgEzYCcICk55lCApgLRhgBQAbiCciOvh18gBYowgTWGUYCZgGUQhBFzACh8-kMoQAZgEMANgGdawwswDufEILmjL65gGM5C8MqddV42HDAlff-wHY4NCEvgDsCNgC2BhRgiTqXiwATm5pHjxcEmhmFplp+ZC5GbyilIXMqYRhhLYgZXUahEVgyLUNVg35tQAmtDoArroALvS6tD3g4lCwLAD23ODEIpC+VDBwmPLGi+jM6EHoIABiENnwcAFXATPekBCMIADC2gAO2vYAlsPaAHb2tGYQA) frage #9
- slide 49 kondensator [DC](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcA2aYDMZIA5nrzgEzYCcICk55lCApgLRhgBQAbiCciOvh18gBYowgTWGUYCZgGUQhBFzACh8-kMoQAZgEMANgGdawwswDufEILmjL6s3IDshWyFGUrke25feeXTwDGcgrgysFcquKwcGAkcfEJidhy0AgCyCQCDulYCNgChOgMWFDRLABO4VWRfsJYnuac3Lw1vA1Vtb5tzAD2VGDEIpBxpZDoJJDI8qNw45PTlM5I6MzoyUgAYhAS0fCJ+4kzWBCMIADC2gAO2gEAlgAu2gB2AbTMABZyluTMQA) & [AC](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcAWaAmAzAgbBjB2BSfZBNBADhASVsmoFMBaMMAKADdx9sRzewPEBXr0IyeklFRoCNgCduvESDzLpYEWwDGqjOr29+UGfEgY0ATms3bto9GxoKmfZstgMyQflOR2AO5KfDiGIbyQbAD2fCDYyCYS1tSmUrFoqmwYVBkAYhCisGYFRf7+ICwgAMIAhgAONdoAlgAuNQB22gxsQA) (kondensator-dc.circuit.txt, kondensator-ac.circuit.txt)
- slide 55 spule [DC](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcA2aYDMZIA5nrzgEzYCcICk55lCApgLRhgBQAbiCciOvh18gBYowgTWGUYCZgGUQhBFzACh8-kMoQAZgEMANgGdawwswDufEILmjL65gCcLPLqu68Noh3IVuuoys7CSpBmcgDshLYg-lEh5jFWMYEhut6Kymm+wujg0CSkJCRhuNgIpfiQYQxgkSEA9iBh4MQikIVQsGAkCJjyHfBtYcgKfZSRTejM6NiNIABiEBrgEIwgAJIAdgAmAK4AxgAu2ht7tMxAA) & [AC](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcAWaAmAzAgbBjB2BSfZBNBADhASVsmoFMBaMMAKADdx9sRzewPEBXr0IyeklFRoCNgCduvESDzLpYEWwDuSvjlUZe-KGwA2h9Zf29RskExiQwATkzECFFwjDPICfFMAe1UQbGQoEAkXF3A7SHJItFCMNgwqDBAAMQg7CARoCBYQAEkAOwATAFcAYwAXAEMymoY2IA) (spule-dc.circuit.txt, spule-dc.circuit.txt)



### Aufgabe: LED + Widerstand 

- Frage slide 27 einfügen
- [Schaltung](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBMcUHYMGZIA4UA2ATmIxAUgoqoQFMBaMMAKADdwNCRs1PuwxFFBEAWWiKowELAE79wQnnlGLhVMPBZhCw7CrXLVvKsIAmdAGYBDAK4AbAC4N7dM+ElRYrAO5GefGBcAVIsQA)
- 

### 





## Schaltungen aus Kapitel 3: Elektrotechnik, Filter und Dioden

- slide 17 rc-tiefpass abgebildet, wie sieht rc-hochpass aus? 

  - versucht es selbst zu bauen, lösung siehe link 

- slide 21 [bandsperre](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcsDMYBM6EA4GTClgOwBsJIeFFkFApgLRhgBQATiFuStgCwg8k+3PjTCRmAd36CQwkCXRDeUNvMWzlCviQTlR8ZgGNpSvgLMBOPVFjx8HaD0gIBYlCgv5PI2ywA2JvxWgTrWMHYQ4fgoCBboVvGKJHHo2HqSatq6IdniUuby2ZyF6QDmHNmhFeQk2NhQKgBu1Rp8xVWi1FQ0PdAIzAD2HPIi4O5gZtAWeDxEYhZ1RNy1SFH2NOjDKMxAA) (`bandsperre-50Hz-Netzbrummen.circuit.txt`)

- slide 22 [rc-tiefpass](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBMcUHYMGZIA4UA2ATmIxAUgoqoQFMBaMMAKAHMQUFCQ8AWPJ2688VMexCEUfXgMnSRYqCwBuQnv0FcehYVQiVkUYzAQsATusnCpM3TyrZckFgGN5dmws3G+0DPCBQXB8jIIMxNB4CHxg3JAoeMSilOQwcKwAHpx85GCQYCgUCHkFSDIKaABUADYA9mwA+vkAFBgAagD0+e0AlAA6AM79AI4AfkMM2AAmAELtLNnSMvkIRYQYgqvlOSAAXtCz0ABcQwBmjWxDo0NgnSgADgCWVdjQCADWAPIAFgC2VT4xAAdgAxa4jIbERIACT2LCAA), [rl-tiefpass](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcBmWBOA7AFjA5AmMSADjGIDYIFIQlraBTAWjDACgAPWsLETX4mmJ8MGEL3wTIAKgA2AewDmAfSIAKDADUA9EU0BKADoBHJsgAmAIU2GAzgFcAdooYAzACcALAE5sAbrRYAmDkgbzkklDgtDREUTQwCGyKfGD4IKShaGkZWMIJyWEZIUXEefGcIOT0ecggosJ5oRK8AEoAMkwAKgCWbgAOAIa2tmzeqemZE1WRNMho8GyyRRG82emr8dDkwkww8CRgyFj45MjYaJIIlFBs8lXg+PkoyDxQsAhYotfkkBjkX3+CHysDgEBoGxAyDYQA), [tiefpassvergleich](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcBmWBOA7AFjA5AmMSADjGIDYIFIQlraBTAWjDACgAPEfYtcSNBBx8iaLCHH5xAMwD6AcwA6AZ0UBHFdUgAJAF5sAbiGLEaGSOJM0EYfFHC0aRezRgI288FOIhz421g+GMjkLh7Gpr4WEWYhYVxYaDTIGBBo5BggKeKS4gBKAMJMACoAlgzSAA4AhsqqygbK0Cp5ADIl5VW19Y3Nyq1FZRU1dWwATl6BUf7etLb2RJBsADYxc3YBPjZ2rrDIyCBMMAI2qcQ2xBj4CBjk+1Dh+FLT3M-Boa7hCGh2frQ-vjinyMT3Ef1B6wWjn4Lig0HcqwQ5BoxAIIB+PlROzh9yOsDAPwwqQwxB4YECJFuD08SKckGetP4SLCngx-GebKIzOBtGR7PEjKxUPozlccPcAGN-r9ot87NsXLB4JACGg1eqNRrMmh4WAzhcrjdKAdjpB2BMIQq5ZC6UsAPLSyHkZkKpxsB2bSFgZDzV0PKVsqzonj8hbQfDMTJMYjQNWsclqrAZZAWcSm9gAd2DmMigbRSyzgciRCwKMiSwmJbLdNLoZoWHMbCzVdDnPpafd-FrQdY+GrYQA9uBQvmvPgkujY0nyCZnT9CFh7qazfYDnr7PgTSBCmwgA) (hier mit parametern spielen und auswirkungen in diagramm sehen), [lc-bandpass](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWEAWaAmBayQBxvpAGxoDsAnCApJZdQgKYC0YYAUAO4hlo4g47VuvHAGY0UVgGMuPPgJm9saZFCiwCEUWWj8cCEi0gjkZZBBhw2AN0qFqSlQjt8xqiFXDUvahKwDmCp7KgdhOqpD+tvaQwU7RYV6sADZRLuJCaeGwEIwkMGZkuCJkCMgIYAUSAB4ghCRIeSo4YBR5JCggwQAyAMIAOgDOAEIAhgB2ACYADiMDA6wA8oGi4ti4mYkA9iDt4vZoaIU7SjrIhGCEZ2aHKhaWbqxAA), [rc-hochpass vs -tiefpass](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWcMBMcUHYMGZIA4UA2ATmIxAUgoqoQFMBaMMAKAHMQUFCQ8AWPJ2688VMexCEUfXgMnSRYqCwBuQnv0FcehYVQiVkUYzAQsATusnCpM3TyrZckFgGN5dmws3G+0DPCBQXB8jIIMKNBgCBh8scSQCNLYeNEOsJCsAB6ccchgKBQx+UgyCmgAVAA2APZsAPpgkAAUGABqAPRNbQCUADoAzn0AjgB+gwzYACYAQm0sOdIyTUmSGIIrpbkgAF7QM9AAXIMAZvVsgyODYB0oAA4AlhXY0AgA1gDyABYAthV8xAAdgAxS7DQbEFB4AASO1UskEPh89mMBn0SjErwkBTAGjkOI0ohMEiRciRRPE7mRwgJ1gcUAycAgTFeTRQxEIeGwfBQUJI5BgTIs4BQuLpIrFPnRcAWFD4VD42EKeF0IEVWwUACUAMIMAAqDzoJzuAEMBkMBioBtBBjqGNCaq4vqbzSwgA), [LC Bandsperre](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3YBMBWEzaIMyIOyMQJwAcOkRRYqykaaNyApgLRhgBQAxiAYkdwCz9uvcJERCaMeHFwgmMMJABsOJZjD9eeHP2RhMUWJHYA3NEpqLx5mkWxRwIFPFEPJ0ZGwDmwvlaE8fpDISm7eNqLWIZbBoZJsAB4gKqikQnahpDggQtYAMgDCADoAzgBCAIYAdgAmJQAODABOTQxsAPK+IHaIomTd9vFNET1dozSYBGwANl0EgmODhtJEvfLQ4tg6KPNK-Ori2ZBsAPa0EDQJdsYGYNCkmMgEBJj7ypq4F0bGDhAXbEA),

- slide 47, 48 [Einweggleichrichtung ohne/mit ladekondensator](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3YBMBWEAWZ0DsY1pwMyIBsAHAJyTkjKQ013ICmAtGGAFBjGLql1ZSaEMSy9Bw3gBMmAMwCGAVwA2AFxbKmU8FF0xInAM4ixICSH4ChekAuWGmHAE4nx10b3J5dYeBwDGFnBm1pYgXsJ0+vAQiNCIlJRIgpAE+GDU0ZwA7kF0Ea7h3pAcAOY0WMRFwsiV4XVRHLke1RVVBSW5te3eaPytJQDyfFbCfQIEVY3DLeazk3ocAB7oGCYQ5DwmYyCIwgCiAJYAdtlMpaWah-4AFk7XN6qKx6UAOoYAtoeqAPQA9jdjkx3gAZeQyADWf2OMmOhnkqj+Tg4ADcRiExv0Ojo0IwbDBkBw-hZdsgpugqKRwtByLS6bSsARyN0INEDLpPFAOEA) (`Einweggleichrichtung-mit-ohne-Kondensator.circuitjs.txt`)

  - was passiert wenn sich die kapazität des kondensators ändert? (Frage #20)

    geringer -> nähert sich Schaltung ohne Kondensator an, also schneidet Spannung unter 0V ab

    höher    -> sägezahnmuster, fällt nie unter 0V  



### LC Tiefpass

Spielt mit den Parametern der Spule und des Kondensators um ein stabiles Signal zu bekommen. (`LC-Bandpass.circuit.txt`, [Schaltung](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3BWEAWaAmBayQBxvpAGxoDsAnCApJZdQgKYC0YYAUAO4hlo4g47VuvHAGY0UVgGMuPPgJm9saZFCiwCEUWWj8cCEi0gjkZZBBhw2AN0qFqSlQjt8xqiFXDUvahKwDmCp7KgdhOqpD+tvaQwU7RYV6sADZRLuJCaeGwEIwkMGZkuCJkCMgIYAUSAB4ghCRIeSo4YBR5JCggwQAyAMIAOgDOAEIAhgB2ACYADiMDA6wA8oGi4ti4mYkA9iDt4vZoaIU7SjrIhGCEZ2aHKhaWbqxAA))

Ausgangsparameter: L = 10mH, C = 1µF -> verrauschtes Signal

Lösung: L = 10mH, C=150µF



#### LC Bandsperre

Hier sind mehrere Schaltungen, wie z.B. die [LC Bandsperre mit AC Sweep](http://falstad.com/circuit/circuitjs.html?ctz=CQAgjCAMB0l3YBMBWEAWZ0DsY1pwMyIBsAHAJyTkjKQ013ICmAtGGAFADGI5ipvPL37hIiNFCix4BMFhCJs5AnizI1xMGJxSEHAObCBW8UdHJikyBwDyZ0kVGQBDxFY4AnEKTjfHfF0c6LWs5Oh9wxzU3VxACBTpiRilkDgAbe38RciE6GFQWGEgwIgswUnVkJH5SeWsADxAsYnisFWEJNvkJUwAZAGEAHQBnACEAQwA7ABNhgAcmDw8mDgB7dAULSTQqAXJoAjgCC0gCWoJyLEg66WLJNwl4gEtJtYVNyzod8hdsJLbaqQUIg+MhqEUEOBwG86ChLPFvsYwNBNLJat9EGpyDldJC3PFUMl4lxxnNxlwngAXVYeN6oOHbXbgAjQNCISDEZAVcjIZAoOTg24QNxuVDPGYAVy41NpQA) (`LC-Bandsperre-AC-Sweep.circuitjs.txt`)



## Schaltungen aus Kapitel 3: Elektrotechnik, Transistoren und Oszillatoren

- slide 15 
- slide 33 ff. basisvorspannung nachbauen? 
- slide 55 probleme bei hohen frequenzen
- slide 63 555 timer IC 
- 



## Zusatz

### Pong

Wen es interessiert findet [hier](https://www.falstad.com/pong/index.html) eine Simulation des 1972 von Atari erfundenen Spiels Pong. 