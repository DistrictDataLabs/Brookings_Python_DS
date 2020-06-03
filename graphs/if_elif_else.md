```flow
st=>start: Start
e=>end: End
c1=>condition: Condition 1
c2=>condition: Condition 2
op1=>operation: Recipe 1
op2=>operation: Recipe 2
op3=>operation: Recipe 3
st(right)->c1
c1(no)->c2
c1(yes)->op1
c2(yes)->op2
c2(no)->op3
```

