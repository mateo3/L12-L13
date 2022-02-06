# L12-L13
L12-L13
Program przedstawia transfer stylu opraty na sieciach neuronowych.Projekt polega na wygenerowaniu obrazu o takiej samej treści jak obraz bazowy, lecz w stylu innego obrazu.Osiąga się to poprzez optymalizację funkcji straty, która składa się z 3 elementów: „utrata stylu”, „utrata treści” i „całkowita utrata zmienności”.Utrata stylu to miejsce, w którym utrzymuje się głębokie uczenie — jest ono definiowane za pomocą głębokiej, splotowej sieci neuronowej. Dokładniej, składa się z sumy odległości L2 między macierzami Grama reprezentacji obrazu bazowego i obrazu odniesienia stylu, wyodrębnionych z różnych warstw sieci konvnet (uczonej na ImageNet). Ogólną ideą jest uchwycenie informacji o kolorze / teksturze w różnych skalach przestrzennych (dość duże skale - zdefiniowane przez głębokość rozważanej warstwy).
Oryginał:

![rolnictwo-zielony-natura-lato](https://user-images.githubusercontent.com/1881832/152684954-9488528e-6ab0-446e-a149-23864e6929ed.jpg)


Styl:

![11117098195f3d9modern_art_or_toddle](https://user-images.githubusercontent.com/1881832/152684947-a51862d3-054a-47be-ba86-b19de1ae351a.jpg)


Obraz przetworzony:

![NST](https://user-images.githubusercontent.com/1881832/152684909-a793c313-96b8-4383-85bf-eaa904362540.png)


Źródło kodu: https://keras.io/examples/generative/neural_style_transfer/
