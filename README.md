# projectproof
project exploration

![Alt text](https://g.gravizo.com/source/custom_mark10?https://github.com/louisrubet/projectproof/edit/master/README.md)
<summary></summary>
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

![Alt text](https://g.gravizo.com/source/my_graph?https://github.com/louisrubet/projectproof/edit/master/README.md)
<summary></summary>
</detail>
my_graph
 digraph G {
   A[HVACR] -->|3-phase| B(STM32)
   A-->|PT100| B(STM32)
   B --> C
   C(OPI0)-->|RS485 / ModBus|A
   C -->|Ethernet / MQTT| D[platform cloud]
 }
my_graph
</details>
