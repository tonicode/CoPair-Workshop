#### Start

```
function berlinClock(time) {
  //good Luck!
}
```

#### Tests

```
Test.assertSimilar(berlinClock("12:56:01"),
"O\nRROO\nRROO\nYYRYYRYYRYY\nYOOO")

Test.assertSimilar(berlinClock("00:00:00"),
"Y\nOOOO\nOOOO\nOOOOOOOOOOO\nOOOO")

Test.assertSimilar(berlinClock("22:32:45"),
"O\nRRRR\nRROO\nYYRYYROOOOO\nYYOO")
```