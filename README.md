# projectproof
project exploration

![Alt text](https://g.gravizo.com/source/custom_mark10?https://raw.githubusercontent.com/louisrubet/projectproof/master/README.md)
<summary></summary>
<details>
custom_mark10
 digraph G {
   main -> parse -> execute;
   main -> init;
   main -> cleanup;
   execute -> make_string;
   execute -> printf;
   init -> make_string;
   main -> printf;
   execute -> compare;
 }
custom_mark10
</details>

![Alt text](https://g.gravizo.com/source/mark2?https://raw.githubusercontent.com/louisrubet/projectproof/master/README.md)
<summary></summary>
<details>
mark2
graph G {
     size="1,1";
     a [label="Foo"];
     b [shape=box];
     a -- b -- c [color=blue];
     b -- d [style=dotted];
}
mark2
</details>
