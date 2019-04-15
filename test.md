![Alt text](https://g.gravizo.com/svg?
  digraph G {
    aize ="4,4";
    main [shape=box];
    main -> parse [weight=8];
    parse -> execute;
    main -> init [style=dotted];
    main -> cleanup;
    execute -> { make_string; printf}
    init -> make_string;
    edge [color=red];
    main -> printf [style=bold,label="100 times"];
    make_string [label="make a string"];
    node [shape=box,style=filled,color=".7 .3 1.0"];
    execute -> compare;
  }
)

![Alt text](https://g.gravizo.com/source/custom_mark10?https%3A%2F%2Fraw.githubusercontent.com%2FTLmaK0%2Fgravizo%2Fmaster%2FREADME.md)

<details> 
<summary>Развернуть</summary><p>
### Heading 3
With some paragraph text and code:
```java
public class TestClass {
   private Integer id;
}
```
</p></details>

## collapsible markdown?
<details><summary>CLICK ME</summary>
<p>
#### yes, even hidden code blocks!
```python
print("hello world!")
```
</p>
</details>
