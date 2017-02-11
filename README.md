**OMNICLAD**
Designed for Discord

**Discord**
Discord is a user friendly voice and text chat designed specifically for gamers. It provides free secure service and works on mobile, desktop, and in web.

 **Omniclad**
 Omniclad is a bot designed with user in mind. Gamers are diverse and many, located all over the world. Cue in language barriers. Language barriers make for a less pleasant gaming experience. Just imagine trying to play Counter Strike or other games requiring strategy and not being able to communicate with part of you team which speaks Russian/Spanish/Chinese.

You may try to communicate through chat because you don't speak those languages, but by the time you pull out google translate and figure out what was being communicated, you've been shot, the bomb was diffused, and your team lost.

*Omniclad* is designed to integrate the translating straight into Discord, whether for use between gamers, or between users and tech support.

![Alt text](https://g.gravizo.com/g?
@startuml;
actor Valeriy;
actor Carl;
Valeriy -> Carl: Иди сюда!;
Note right of Carl: Carl translates, time wasted, game lost;
@enduml
)


```
With *Omniclad*, the situation would go more like this:
```


![Alt text](https://g.gravizo.com/g?
@startuml;
actor Valeriy;
participant "Chat" as A;
actor Carl;
activate A;
Valeriy -> A: Иди сюда!;
A -> Carl: Come here!;
Note right of Carl: Carl gets message, helps Valeriy, wins game;
A <- Carl: We won!; 
A -> Valeriy: Мы победили!;
deactivate A;
@enduml
)



> Written with [StackEdit](https://stackedit.io/).
