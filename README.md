# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid
classDiagram
  class UserInput{
        - maxInput int
        + get_input() string
  }
  class TypeAccuracyChecker{
        - words vector~string~
        + get_random_word() string
        + compare_accuracy(string, string)
  }
  class TypeSpeedChecker{
        + get_speed() float
  }
```
