# Basic Guessing Game Flowchart

``` mermaid
flowchart TD
 Start([Start]) --> Generate[Generate Random Number]
 Generate --> Ask["What is the Random Number?"]
 Ask --> Validate {Is Input Valid?}
 Validate --> |No| Invalid[Display Error Messsage]
 Invalid --> Ask 
 Check --> |Too High| High[Display "Too High!"]
 Check --> |Too Low| Low[Display "Too Low!"]
 Check --> |Correct| Correct[Display "Correct!"]
 High --> Ask
 Low --> Ask 
 Correct --> End([End])
