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

3.

## Description

This css code allows you to center items.

### Long line of code

```
.container {
    display: flex;
    justify-content: center;
    align-items: center;
}
```

### One-liner

```
.container {
    display: grid;
    place-items: center;
}
```

---

4.

## Description

This code is a shorthand for the four inset properties, top, right, bottom and left in one declaration.

### Long line of code

```
.card{
    position: fixed;
    top:0;
    right:0;
    bottom:0;
    left: 0;
}
```

### One-liner

```
.card{
    position: fixed;
    inset: 0;
}
```

---

5.

## Description

This code is a shorthand for applying same styling to multiple tags in one declaration.

### Long line of code

```
header p:hover{
    color:red;
    cursor:pointer;
}

main p:hover{
    color:red;
    cursor:pointer;
}

footer p:hover{
    color:red;
    cursor:pointer;
}
```

### One-liner

```
:is(header, main, footer) p:hover {
  color: red;
  cursor: pointer;
}
```

---

6.

The CSS :has selector helps you select elements that contain elements that match the selector you pass into the :has() function.

### Long line of code

```
h2,
.subtitle {
  margin: 0 0 1.5rem 0;
}
```

### One-liner

```
.header-group:has(h2):has(.subtitle) h2 {
  margin: 0 0 0.2rem 0;
}
```

---

7.

This code is shorthand for applying flex-box properties in one line.

### Long line of code

```
.container{
    display:flex;
    flex-wrap: wrap;
    justify-content:center;
}
```

### One-liner

```
flex:1 1 160px;

```

---

8.

This code is shorthand for applying grid property in one line.

### Long line of code

```
.grid-1 {
  display: grid;
  grid-template-rows: 100px 300px;
  grid-auto-flow: column;
  grid-auto-columns: 100px;
}
```

### One-liner

```
.grid-1 {
  display: grid;
  grid: 100px 300px / auto-flow column 100px;
}
```

---

9.
This code is shorthand for applying background property in one line.

### Long line of code

```
body {
  background-color: #ffffff;
  background-image: url("img_tree.png");
  background-repeat: no-repeat;
  background-position: right top;
}

```

### One-liner Code

```
body {
  background: #ffffff url("img_tree.png") no-repeat right top;
}

```

10.
This code is shorthand for applying animation property in one line.

### Long line of code

```
.animation {
  animation-name: animation_name;
  animation-duration: 4s;
  animation-timing-function: ease-in-out;
  animation-delay: 3s;
  animation-iteration-count: 1;
  animation-direction: reverse;
  animation-fill-mode: alternate;
}

```

### One-liner Code

```
.animation {
  animation: animation_name 4s ease-in-out 3s 1 reverse alternate;
}

```
