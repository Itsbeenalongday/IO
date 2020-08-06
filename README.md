# IO

+ 언어별 IO방법
+ [참조 링크](https://www.acmicpc.net/help/language)

<br/>

## java
```JAVA
  import java.util.*;
  public class Main{
	public static void main(String args[]){
		Scanner sc = new Scanner(System.in);
		int a, b;
		a = sc.nextInt();
		b = sc.nextInt();
		System.out.println(a + b);
	}
}
```
<br/>
## python3

```python
a, b = map(int, input().split())
print(a+b)
```
<br/>
## node.js

```javascript
var fs = require('fs');
var input = fs.readFileSync('/dev/stdin').toString().split(' ');
var a = parseInt(input[0]);
var b = parseInt(input[1]);
console.log(a+b);
```
<br/>
## PHP

```PHP
<?php
fscanf(STDIN,"%d %d",$a,$b);
fprintf(STDOUT,"%d",$a+$b);

```
<br/>
## BASH

```bash
read a b
echo $(($a+$b))
```
