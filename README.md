# TicTacToe – jwviis
Prosty skrypt w JavaScript umożliwiający grę w kółko-krzyżyk dla dwóch graczy na planszy 3x3.

# Jak grać?
Po uruchomieniu skryptu wyświetli się plansza złożona z 9 pól. Gracze na zmianę klikają na pola, umieszczając swój symbol: X lub O.
Po wygranej jednego z graczy pojawi się komunikat o zwycięstwie, a wygrywająca kombinacja zostanie oznaczona czerwoną linią. Możliwy jest też remis.

# Główne funkcje:
createBoard() – Generuje planszę do gry.

handleCellClick(event) – Obsługuje ruchy graczy: dodaje symbol, sprawdza wynik i zmienia turę.

checkWin() – Weryfikuje, czy któryś z graczy wygrał.

drawWinningLine() – Rysuje linię wskazującą zwycięskie pola.

resetGame() – Czyści planszę i rozpoczyna nową grę.

# Wykorzystywane zmienne globalne:
board – Element HTML z planszą.

messageTur – Element pokazujący aktualną turę lub wynik.

resertBtn – Przycisk do resetowania gry.

currentPlayer – Aktualnie grający gracz (X lub O).

gameBoard – Tablica reprezentująca aktualny stan planszy.

winningCombo – Zbiór wszystkich możliwych kombinacji wygranych.

gameOver – Flaga informująca, czy gra została zakończona.

