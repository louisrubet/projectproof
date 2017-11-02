# projectproof
project exploration

## DOT example 5
![Alt text](https://g.gravizo.com/source/mark5?https://raw.githubusercontent.com/louisrubet/projectproof/master/README.md)
<summary></summary>
<details>
mark5
 graph ethane {
     C_0 -- H_0 [type=s];
     C_0 -- H_1 [type=s];
     C_0 -- H_2 [type=s];
     C_0 -- C_1 [type=s];
     C_1 -- H_3 [type=s];
     C_1 -- H_4 [type=s];
     C_1 -- H_5 [type=s];
 }
mark5
</details>

## DOT example 6
![Alt text](https://g.gravizo.com/source/mark6?https://raw.githubusercontent.com/louisrubet/projectproof/master/README.md)
<summary></summary>
<details>
mark6
digraph g {
	node [shape=plaintext];
	A1 -> B1;
	A2 -> B2;
	A3 -> B3;
	
	A1 -> A2 [label=f];
	A2 -> A3 [label=g];
	B2 -> B3 [label="g'"];
	B1 -> B3 [label="(g o f)'" tailport=s headport=s];

	{ rank=same; A1 A2 A3 }
	{ rank=same; B1 B2 B3 } 
}
mark6
</details>

