# projectproof
project exploration

![Alt text](https://g.gravizo.com/source/custom_mark10?https://github.com/louisrubet/projectproof/blob/master/README.md)
<summary></summary>
custom_mark10
 digraph G {
   main -&gt parse -&gt execute;
   main -&gt init;
   main -&gt cleanup;
   execute -&gt make_string;
   execute -&gt printf
   init -&gt make_string;
   main -&gt printf;
   execute -&gt compare;
 }
custom_mark10
</details>

```jsseq
a->b: message 1
b->a: message 2
```


