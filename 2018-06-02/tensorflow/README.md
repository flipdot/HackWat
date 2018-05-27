# Einführung in TensorFlow

Zur Einrichtung der Python-Umgebung ist
[Anaconda](https://www.anaconda.com/download/) empfehlenswert. Nach dem Setup
von Anaconda kann TensorFlow in der Regel mittels `pip install tensorflow`
einfach installiert werden. Für GPU Support und plattformspezifische Details
sei auf https://www.tensorflow.org/install/ verwiesen.

Die Notebooks können verwendet werden, indem in diesem Verzeichnis `jupyter
notebook` ausgeführt wird. Der Browser öffnet sich, die Datei `examples.ipynb`
kann in Jupyter ausgewählt werden. Über das Menü `Kernel -> Restart & Run All`
können sämtliche Beispiele ausgeführt werden. Dadurch werden Logs im
Verzeichnis `logdir` erzeugt, die von TensorBoard angezeigt werden können.

Das TensorBoard kann nun mittels `tensorboard --logdir=logdir` gestartet
werden.
