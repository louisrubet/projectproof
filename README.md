# projectproof
project exploration

```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```
<a href="https://github.com/louisrubet/projectproof/edit/master/">
  <img src="./mermaid-trial.svg" height="200">
</a>

![Alt text](./mermaid-trial.svg)
<img src="./mermaid-trial.svg">

<img src='https://g.gravizo.com/svg?
 digraph G {
   main -> parse -> execute;
   main -> init;
   main -> cleanup;
   execute -> make_string;
   execute -> printf
   init -> make_string;
   main -> printf;
   execute -> compare;
 }
'/>
