# beads-vector-notation

Vector of positive integers separated by'o'  

Commentary by author:  

📖 [数珠玉記数法 (Beads Nested Number Notation)](https://crieit.net/posts/Beads-Nested-Number-Notation)  

# Install

```shell
pip install beadsvec
```

# Explanation

## Cons

* It's eccentric  

## Pros

* Fits in a [0-9A-Za-z]  

## Examples

👇 Tree structure. Normal notation  

```plaintext
1. Food

1.1. Fruits

1.1.1. Apple

1.1.2. Banana

2. Vehicle

2.1. Ship

2.2. Train

2.3. Car

2.3.1. Police car
```

👇 Beads vector notation  

```plaintext
1. Food
1o1. Fruit
1o1o1. Apple
1o1o2. Banana
2. Vehicle
2o1. Ship
2o2. Train
2o3. Car
2o3o1. PoliceCar
```

"o" is ignore case.  

The O looks like zero.  
The o looks like point.  
