# TicTacToe
Softwareentwicklungsprojekt Semester 6 Nicolas Plieninger

Allgemeine Informationen:

	-Das C++ Programm (TicTacToe) funktioniert nur auf Windows
	-Das C# Programm (TicTacToeRaspberryPi) funktioniert auf Windows und mit Hilfe des "Mono Frameworks" auf dem RaspberryPi
	-Das .exe File des Programmes auf dem Raspberry Pi unter /home/"user" in diesem Fall /home/plinic ablegen

Starten des Spiels:

	-Um das Spiel zu starten auf dem Raspberry Pi das Command Terminal öffnen
	-Folgenden Befehl eingeben: mono TicTacToeRaspberryPi.exe
	-Danach öffnet sich das Spiel

Spielregeln:

	-Tic-Tac-Toe ist ein Spiel für zwei Spieler, die abwechselnd ihre Markierungen ("X" und "O") auf einem 3x3 Spielfeld setzen.
	-Das Ziel des Spiels ist es, drei Markierungen in einer horizontalen, vertikalen oder diagonalen Reihe zu platzieren.
	-Der Spieler, der dies als Erster schafft, gewinnt die Runde.
	-Wenn alle Felder belegt sind und kein Spieler gewonnen hat, endet das Spiel unentschieden.

Spielverlauf:

	-Um das Spiel zu starten, klicken Sie auf einen der leeren Buttons im Spielfeld.
	-Spieler 1 beginnt mit der Markierung "X".
	-Der aktuelle Spieler wird über dem Spielfeld angezeigt.
	-Die Spieler wechseln sich ab, um ihre Markierungen auf dem Spielfeld zu platzieren.
	-Klicken Sie auf einen leeren Button, um Ihre Markierung zu setzen.
	-Sobald ein Spieler drei Markierungen in einer Reihe hat, wird er als Gewinner angezeigt.
	-Wenn das Spiel unentschieden endet, wird eine entsprechende Meldung angezeigt.
	-Wenn ein Spiel beendet wurde, kann das Spielfeld mit dem "Reset" Button in der oberen linken Ecke resetiert werden.

Spielstand:
	
	-Nach jedem Spiel wird der Spielstand für die Spieler aktualisiert.
	-Der Spielstand kann mit dem "Reset" Button in der unteren rechten Ecke resetiert werden.

Um das Spiel zu beenden, einfach das Fenster schliessen
