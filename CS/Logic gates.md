### 8.4.2 == (NOT(A not B) OR (NOT A))) OR (A AND B)

 | B   | A   |  Output     |
 | --- | --- | ----- |
 | 0   | 1   | ==> 1 |
 | 0   | 0   | ==> 0 |
 | 1   | 1   | ==> 1 |
 | 1   | 0   | ==> 0 |
 
 ### 8.4.3 == ((A NOR B) NAND (NOT C)) AND (NOT C)
 
| C   | B   | A   | Output |
| --- | --- | --- | ------ |
| 0   | 0   | 0   | ==> 0  |
| 0   | 1   | 0   | ==> 1  |
| 1   | 0   | 0   | ==> 1  |
| 1   | 1   | 0   | ==> 0  |
| 0   | 0   | 1   | ==> 1  |
| 0   | 1   | 1   | ==> 0  |
| 1   | 0   | 1   | ==> 0  |
| 1   | 1   | 1   | ==> 1  |

### 8.4.7 ==
![[Pasted image 20201202184210.png]]
 
| C   | B   | A   |    Output   |
| --- | --- | --- | ----- |
| 0   | 0   | 0   | ==> 1 |
| 0   | 0   | 1   | ==> 1 |
| 0   | 1   | 0   | ==> 1 |
| 0   | 1   | 1   | ==> 0 |
| 1   | 0   | 0   | ==> 1 |
| 1   | 0   | 1   | ==> 0 |
| 1   | 1   | 0   | ==> 1 |
| 1   | 1   | 1   | ==> 0 |

### 8.4.8 ==
![[Screenshot from 2020-11-28 17-07-50.png]]

| S   | R   | T   |    Output   |
| --- | --- | --- | ----- |
| 0   | 0   | 0   | ==> 0 |
| 0   | 0   | 1   | ==> 0 |
| 0   | 1   | 0   | ==> 0 |
| 0   | 1   | 1   | ==> 0 |
| 1   | 0   | 0   | ==> 0 |
| 1   | 0   | 1   | ==> 1 |
| 1   | 1   | 0   | ==> 1 |
| 1   | 1   | 1   | ==> 1 |