Das Python-Picamera-Modul ist derzeit standardmäßig nicht mit der neuesten Version von Raspberry Pi OS (genannt **Bullseye**) kompatibel.

Um das Picamera-Modul verwenden zu können, musst du die Legacy-Unterstützung für die Kamera aktivieren. <iframe width="560" height="315" src="https://www.youtube.com/embed/E7KPSc_Xr24" title="YouTube-Videoplayer" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen mark="crwd-mark"></iframe>

Öffne ein Terminalfenster und führe den folgenden Befehl aus:

```bash
sudo raspi-config
```

Scrolle mit den Cursortasten nach unten zu `Interface Options` und drücke die Eingabetaste.

![interface options ausgewählt](images/interface-options.png)

Stelle sicher, dass „Legacy Camera Enable/disable Legacy Camera Support“ ausgewählt ist und drücke die Eingabetaste.

![Legacy-Kamera ausgewählt](images/enable-legacy.png)

Wähle mit den Cursortasten `<Yes>` und drücke die Eingabetaste

Drücke zur Bestätigung erneut die Eingabetaste

![Fenster mit markiertem "Ok" für die Unterstützung älterer Kameras](images/ok.png)

Wähle `<Finish>` mit den Cursortasten

!["Finish" markiert](images/finish.png)

Drücke die Eingabetaste, um neu zu starten.

![Neustart ausgewählt](images/reboot.png)

