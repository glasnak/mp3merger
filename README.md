# mp3merger
Utility to merge multiple mp3 files into one.

Examples:
```
./mp3merger Track1.mp3 Track2.mp3 Track3.mp3 > All.mp3

./mp3merger ~/Music/PopularBand/*.mp3 > All.mp3

find . -type f -name "A*.mp3" | tr '\n' '\0' | xargs -n1 -0 ~/path/to/mp3merger > A_Songs.mp3
```


Requirements:
  - sh
  - cat
