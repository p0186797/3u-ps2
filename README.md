# 3u-ps2
---
Create a file called **teams.py** and upload it to this repo. 

A sporting organization separates teams into different leagues based on how many games they have won in an 8 game season.
If they have won 1 – 2 games inclusive they are in the “Beginner” league. If they have won 3 – 4 games inclusive they are in the “Intermediate” league. If they have won 5 – 6 games inclusive they are in the “Advanced” league. And if they have won 7 games or more they are in the championship league. If they did not win a single game – they cannot compete. Write a program that takes in 8 lines of input – either W or L and outputs what league they are in: Beginner, Intermediate, Advanced, Championship, Cannot Compete.

**Input Specifications**
```
8 lines of input – each line is either W or L.
```

**Output Specifications**
```
1 line from: Beginner, Intermediate, Advanced, Championship, Cannot Compete.
```

**Sample Input 1**
```
W
L
W
W
W
L
L
L
```

**Sample Output 1**
```
Intermediate
```
---
Create a file called **astrology.py** and upload it to this repo.

Write a program that takes in the user's year of birth and outputs their elemental zodiac. Their elemental zodiac consists of an element (Metal, Fire, Wood, Water, Earth) and an animal (Rat, Ox, Tiger, Rabbit, Dragon, Snake, Horse, Sheep, Monkey, Rooster, Dog, Pig).

To figure out your element, **look at the last digit of your birth year**.

- 0 or 1, your element is metal
- 2 or 3, your element is water
- 4 or 5, your element is wood
- 6 or 7, your element is fire
- 8 or 9, your element is earth

To figure out your zodiac animal use the below chart. The Chinese zodiac repeats every 12 years. For example, 2008 + 12 = 2020 is also the year of the rat.

|rat       |ox        |tiger     |rabbit    |dragon    |snake     |horse     |sheep    |monkey    |rooster   |dog       |pig       |
|----------|----------|----------|----------|----------|----------|----------|---------|----------|----------|----------|----------|
|2008      |2009      |2010      |2011      |2012      |2013      |2014      |2015     |2016      |2017      |2018      |2019      |

- **Input Specifications**
```
1 line of input representing the year of birth
```

**Output Specifications**
```
1 line of output: element and zodiac animal with a space in between with all lower case
```

**Sample Input 1**
```
1999
```

**Sample Output 1**
```
earth rabbit
```
