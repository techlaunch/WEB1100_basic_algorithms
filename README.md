# WEB1100_basic_algorithms
Basic examples of algorithms

## Sort by word case
```
var fruits = ["BANANA", "orange", "apple", "MANGO"];
fruits.sort(function(a, b){
	if(a == a.toLowerCase()) return -1;
	if(b == b.toUpperCase()) return 1;
	return 0;
});
```
