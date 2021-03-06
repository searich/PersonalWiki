## How to analyse an algorithm	[Back](./../AlgorithmnMenu.md)

###Overview
- Main **thoughts** of designing algorithms

	- [**DC**](./DC/DC.md)
	- [**DP**](./DP/DP.md)
	- [**Greedy**](./Greedy/Greedy.md)
	- [**Search**](./Search/Search.md)
	- [**Random**](./Random/Random.md)

<img src="./thoughts.png">

- Sometimes, the **performance** of an algorithm matters so much, when the size of a problem **n** is so big.

<img src="./overhead.png" width="75%">

- But it's not always true for high performance, when an algorithm depends on what is more important like the following items:
	- modularity(模塊性)
	- correctness(正確性)
	- maintainabillity(可維護性)
	- functionality(功能性)
	- robustness(健壯性)
	- user-friendliness(用戶友好性)
	- programmer time(編程效率)
	- simplicity(簡潔度)
	- extensibility(可擴展性)
	- reliability(可靠度)

- **Three** kinds of analysis
	- Worst-case(考慮該類問題的最優解, 關注最壞情況下的最好情況)
	- Average-case
	- Best-case(虛假的)

- **Three** notations of **time**
	- ***θ***

	<img src="./theta.png"> (drop **low-order** terms, and ignore **leading** constants)

	<img src="./example.png">

	- ***Ω***

	<img src="./Omega.png">

	- ***O***

	<img src="./O.png">

### Recursive Algorithmn
- Substitution: 猜想 (通常通過畫Recursive Tree來給出猜想) 並證明
	- guess
	- verify

		<img src="./example1.png">
		=====
		<img src="./example2.png">
	- solve
- Recursive Tree: 通過畫出遞歸樹來求解開銷

<img src="./recursive_tree.png" width="80%">

<img src="./recursive_expression.png">

- Master:

	<img src="./master.png">
	
	- <img src="./master1.png">

	- <img src="./master2.png">

	- <img src="./master3.png">
