```mermaid
stateDiagram-v2       
    Koding --> Hungry: Stomach growling
    Hungry --> OrderingFood: Opens food app
    OrderingFood --> Eating: Food arrives
    Eating --> FoodComa: Too much pizza
    FoodComa --> Koding: Sugar rush kicks in
    
    Koding --> Exhausted: 3AM strikes
    Exhausted --> MicroNap: "Just 5 minutes"
    MicroNap --> DeepSleep: 5 minutes become 5 hours
    DeepSleep --> PanicWake: Missed standup!
    PanicWake --> Koding: Coffee.exe launched
    
    Koding --> Coffee: Energy < 20%
    Coffee --> Koding: Energy restored
    Coffee --> Jitters: Too much coffee
    Jitters --> Koding: Types really fast
    
    Koding --> Distracted: New notification
    Distracted --> YouTube: "Quick" tutorial
    YouTube --> CatVideos: Recommended feed
    CatVideos --> Guilt: 2 hours later
    Guilt --> Koding: Back to work
```
