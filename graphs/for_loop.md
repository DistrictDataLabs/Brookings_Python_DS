```flow
st=>start: Start with list
in1=>inputoutput: First element
op=>operation: Your recipe
cond=>condition: Done with elements?
act=>inputoutput: Next element
e=>end

st->in1->op->cond
cond(no)->act
act(top)->op
cond(yes)->e

```

