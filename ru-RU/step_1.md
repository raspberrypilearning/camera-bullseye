Модуль Python Picamera в настоящее время по умолчанию не совместим с последней версией ОС Raspberry Pi (называется **Bullseye**).

Чтобы использовать модуль Picamera, тебе необходимо включить устаревшую поддержку камеры. <iframe width="560" height="315" src="https://www.youtube.com/embed/E7KPSc_Xr24" title="Видеопроигрыватель YouTube" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen mark="crwd-mark"></iframe>

Открой окно терминала и введи следующую команду:

```bash
sudo raspi-config
```

С помощью клавиш управления курсором прокрути вниз до `Параметры Интерфейса` и нажми клавишу «Ввод».

![выбраны параметры интерфейса](images/interface-options.png)

Убедись, что выбран вариант «Включить/отключить поддержку устаревших камер», и нажми клавишу «Ввод».

![выбрана устаревшая камера](images/enable-legacy.png)

Используй клавиши управления курсором, чтобы выбрать `<Yes>` и нажми клавишу «Ввод»

Нажми «Ввод» еще раз, чтобы подтвердить

![окно с выделенным Ok для поддержки устаревшей камеры](images/ok.png)

Используй клавиши управления курсором, чтобы выбрать `<Finish>`

![финиш подсвечен](images/finish.png)

Нажми «Ввод» для перезагрузки.

![перезагрузить подсвечено](images/reboot.png)

