# Basic Guessing Game Flowchart

``` mermaid
flowchart TD
<<<<<<< HEAD
Start([Start]) --> Generate[Generate Random Number]
Generate --> Ask{"What is the Random Number?"}
Ask --> Validate {Is Input Valid?}
Validate --> |No| Invalid[Display Error Messsage]
Invalid --> Ask 
Check --> |Too High| High[Display "Too High!"]
Check --> |Too Low| Low[Display "Too Low!"]
Check --> |Correct| Correct[Display "Correct!"]
High --> Ask
Low --> Ask 
Correct --> End([End])
=======
 Start([Start]) --> Generate[Generate Random Number]
 Generate --> Ask["What is the Random Number?"]
 Validate --> |No| Invalid[Display Error Messsage]
 Invalid --> Ask 
 Check --> |Too High| High[Display "Too High!"]
 Check --> |Too Low| Low[Display "Too Low!"]
 Check --> |Correct| Correct[Display "Correct!"]
 High --> Ask
 Low --> Ask 
 Correct --> End([End])
>>>>>>> 512045e42da87c79afc95f48bb3140bc48aa9941
