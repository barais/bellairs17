## The Kevoree project

- Concrete implementation of distributed Model@Runtime

- Based on a <span class="kevOrange">*component* model</span> and software industry best practices

```java
@ComponentType
public class LCDDisplay
    extends AbstractArduinoComponent {

    @Intput
    void input(){...}
     /*...*/ }
```

<img src="resources/modelview.png" style="border-radius:5px; position:absolute;right:50px;top:320px;width:220px;" />

- High level *DSL* to write distributed system adaptations

```
add host4.monitorAgent : Agent
move host4.monitorAgent to host5
```

----

## DSPL
- Dynamic Software Product Line at the application level
- Concrete links between CVL models and Software architecture model
- Notion of Aspect at the model level (architecture model fragment)

<img src="resources/ddas.svg" width="50%">
