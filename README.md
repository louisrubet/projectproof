# projectproof
project exploration

![Alt text](https://g.gravizo.com/source/custom_mark10?https://raw.githubusercontent.com/TLmaK0/projectproof/master/README.md)
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

```jsseq
a->b: message 1
b->a: message 2
```


<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

![Alt text](https://g.gravizo.com/source/HVACR_general?https://raw.githubusercontent.com/TLmaK0/projectproof/master/README.md)
<summary></summary>
HVACR_general
A[HVACR] -->|3-phase| B(STM32)
A-->|PT100| B(STM32)
B --> C
C(OPI0)-->|RS485 / ModBus|A
C -->|Ethernet / MQTT| D[platform cloud]
HVACR_general
</details>
