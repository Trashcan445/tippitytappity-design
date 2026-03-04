# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid
classDiagram
class User{
      - username string
      - history vector~TypingTest~
      + get_input() string
}
class TypingTest{
  - bank WordBank
  + compare_accuracy(string, string) float
  + get_speed()
}
class WordBank{
        - words vector~string~
        + get_random_word() string
}
User-->TypingTest
TypingTest-->WordBank
```
