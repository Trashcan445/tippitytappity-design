# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid
classDiagram
class UserInput{
      - username string
      - history vecotr~TypingTest~
      + get_input() string
}
class TypingTest{
  + compare_accuracy(string, string) float
  + get_speed()
}
class WordBank{
        - words vector~string~
        + get_random_word() string
}
```
