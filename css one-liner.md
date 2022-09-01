1.
## Description
The css code allows you to combine the use of more than one css pseudo class.

### Long line of code

```
a:hover,
a:focus{
    color: #000000;
}
```

### One-liner

```
a:where(:hover, :focus){
    color: #000000;
}
```

---

2. 
## Description
The css code allows you to set max-width and width on a container(or selector).

### Long line of code

```
.container {
    max-width: 900px;
    width: 70%;
}
```

### One-liner

```
.container {
    width: min(900px, 70%);
}
```

---