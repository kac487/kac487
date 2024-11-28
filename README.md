```mermaid
stateDiagram-v2
    [*] --> Coding
    
    Coding --> BugHunting: Error appears
    BugHunting --> Coding: Bug fixed
    BugHunting --> StackOverflow: Desperate search
    StackOverflow --> Coding: Copy & Paste solution
    
    Coding --> Hungry: Stomach growling
    Hungry --> OrderingFood: Opens food app
    OrderingFood --> Eating: Food arrives
    Eating --> FoodComa: Too much pizza
    FoodComa --> Coding: Sugar rush kicks in
    
    Coding --> Exhausted: 3AM strikes
    Exhausted --> MicroNap: "Just 5 minutes"
    MicroNap --> DeepSleep: 5 minutes become 5 hours
    DeepSleep --> PanicWake: Missed standup!
    PanicWake --> Coding: Coffee.exe launched
    
    Coding --> Coffee: Energy < 20%
    Coffee --> Coding: Energy restored
    Coffee --> Jitters: Too much coffee
    Jitters --> Coding: Types really fast
    
    Coding --> Distracted: New notification
    Distracted --> YouTube: "Quick" tutorial
    YouTube --> CatVideos: Recommended feed
    CatVideos --> Guilt: 2 hours later
    Guilt --> Coding: Back to work
    
    note right of Coding: The eternal loop
    note left of Coffee: Essential resource
    note bottom of StackOverflow: Developer's best friend
```
