### Перелік індивідуальних завдань до Лабораторної роботи №6 **Конфігурування PID-регулятора **



| № Вар. | № PID-рег. | Type | measure | Conversion | Set point | Corrector type | Кр    | Ті   | Td   | sampling period | Action | manual mode | Bit address | Output | Analog Output |
| ------ | ---------- | ---- | ------- | ---------- | --------- | -------------- | ----- | ---- | ---- | --------------- | ------ | ----------- | ----------- | ------ | ------------- |
| 1      | PID 0      | PID  | %MW10   | 0-100      | 50        | PID            | %MW20 | 10   | 15   | 1               | Direct | bit address | %m0         | %MW30  | %MW30         |
| 2      | PID 1      | PID  | %MW20   | 0-100      | %MW20     | PI             | 5     | 15   | -    | 2               | Revers | bit address | %m1         | %MW40  | %MW40         |
| 3      | PID  2     | PID  | %MW30   | 0-100      | 60        | PID            | %MW21 | 20   | 20   | 3               | Direct | bit address | %m2         | %MW50  | %MW50         |
| 4      | PID  3     | PID  | %MW40   | 0-100      | %MW30     | PI             | 6     | 25   | -    | 4               | Revers | bit address | %m3         | %MW60  | %MW60         |
| 5      | PID  4     | PID  | %MW50   | 0-100      | 20        | PID            | %MW22 | 30   | 16   | 5               | Direct | bit address | %m4         | %MW70  | %MW70         |
| 6      | PID  5     | PID  | %MW60   | 0-100      | %MW21     | PI             | 7     | 35   | -    | 6               | Revers | bit address | %m5         | %MW80  | %MW80         |
| 7      | PID  6     | PID  | %MW70   | 0-100      | 60        | PID            | %MW23 | 40   | 21   | 7               | Direct | bit address | %m6         | %MW90  | %MW90         |
| 8      | PID  7     | PID  | %MW80   | 0-100      | %MW31     | PI             | 8     | 45   | -    | 8               | Revers | bit address | %m7         | %MW100 | %MW100        |
| 9      | PID  8     | PID  | %MW90   | _-50-200   | 0         | PID            | %MW24 | 50   | 17   | 9               | Direct | bit address | %m8         | %MW110 | %MW110        |
| 10     | PID  9     | PID  | %MW100  | _-50-200   | %MW22     | PI             | 9     | 55   | -    | 10              | Revers | bit address | %m9         | %MW120 | %MW120        |
| 11     | PID  10    | PID  | %MW110  | _-50-200   | 25        | PID            | %MW25 | 60   | 22   | 1               | Direct | bit address | %m10        | %MW130 | %MW130        |
| 12     | PID  11    | PID  | %MW120  | _-50-200   | %MW32     | PI             | 10    | 65   | -    | 2               | Revers | bit address | %m0         | %MW140 | %MW140        |
| 13     | PID  12    | PID  | %MW130  | _-50-200   | 45        | PID            | %MW26 | 70   | 18   | 3               | Direct | bit address | %m1         | %MW150 | %MW150        |
| 14     | PID  13    | PID  | %MW140  | _-50-200   | %MW23     | PI             | 11    | 75   | -    | 4               | Revers | bit address | %m2         | %MW160 | %MW160        |
| 15     | PID  0     | PID  | %MW150  | _-50-200   | 20        | PID            | %MW27 | 80   | 23   | 5               | Direct | bit address | %m3         | %MW170 | %MW170        |
| 16     | PID  1     | PID  | %MW160  | _-50-200   | %MW33     | PI             | 12    | 85   | -    | 6               | Revers | bit address | %m4         | %MW180 | %MW180        |
| 17     | PID  2     | PID  | %MW170  | _-50-200   | 100       | PID            | %MW28 | 90   | 19   | 7               | Direct | bit address | %m5         | %MW190 | %MW190        |
| 18     | PID  3     | PID  | %MW180  | _-50-200   | %MW24     | PI             | 13    | 95   | -    | 8               | Revers | bit address | %m6         | %MW200 | %MW200        |
| 19     | PID  4     | PID  | %MW190  | _-50-200   | 35        | PID            | %MW29 | 100  | 24   | 9               | Direct | bit address | %m7         | %MW210 | %MW210        |
| 20     | PID  5     | PID  | %MW200  | 0-1000     | %MW34     | PI             | 14    | 105  | -    | 10              | Revers | bit address | %m8         | %MW220 | %MW220        |
| 21     | PID  6     | PID  | %MW210  | 0-1000     | 40        | PID            | %MW30 | 110  | 20   | 11              | Direct | bit address | %m9         | %MW230 | %MW230        |
| 22     | PID  7     | PID  | %MW220  | 0-1000     | %MW25     | PI             | 15    | 115  | -    | 1               | Revers | bit address | %m10        | %MW240 | %MW240        |
| 23     | PID  8     | PID  | %MW230  | 0-1000     | 25        | PID            | %MW31 | 120  | 25   | 2               | Direct | bit address | %m0         | %MW250 | %MW250        |
| 24     | PID  9     | PID  | %MW240  | 0-1000     | %MW35     | PI             | 16    | 125  | -    | 3               | Revers | bit address | %m1         | %MW260 | %MW260        |
| 25     | PID  10    | PID  | %MW250  | 0-1000     | 150       | PID            | %MW32 | 130  | 21   | 4               | Direct | bit address | %m2         | %MW270 | %MW270        |
| 26     | PID  11    | PID  | %MW260  | 0-1000     | %MW26     | PI             | 17    | 135  | -    | 5               | Revers | bit address | %m3         | %MW280 | %MW280        |
| 27     | PID  12    | PID  | %MW270  | 0-1000     | 70        | PID            | %MW33 | 140  | 26   | 6               | Direct | bit address | %m4         | %MW290 | %MW290        |
| 28     | PID  13    | PID  | %MW280  | 0-1000     | %MW36     | PI             | 18    | 145  | -    | 7               | Revers | bit address | %m5         | %MW300 | %MW300        |
| 29     | PID 0      | PID  | %MW290  | 0-1000     | 80        | PID            | %MW34 | 150  | 22   | 8               | Direct | bit address | %m6         | %MW310 | %MW310        |
| 30     | PID 1      | PID  | %MW300  | 0-1000     | %MW27     | PI             | 19    | 155  | -    | 9               | Revers | bit address | %m7         | %MW320 | %MW320        |

 