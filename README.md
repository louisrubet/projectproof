# projectproof
project exploration

![Alt text](https://g.gravizo.com/source/custom_mark10?https://github.com/louisrubet/projectproof/blob/master/README.md)
<summary></summary>
custom_mark10
 digraph G {
   main -\> parse -\> execute;
   main -\> init;
   main -\> cleanup;
   execute -\> make_string;
   execute -\> printf
   init -\> make_string;
   main -\> printf;
   execute -\> compare;
 }
custom_mark10
</details>
