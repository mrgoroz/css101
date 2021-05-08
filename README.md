# css101
### vanilla css float side by side

```css

.block{
	float:left;
	width:33.3%;
	border:1px solid #ccc;
	padding:10px;
	box-sizing:border-box;
}
```

### position father relative > son absolute

```css
.p-box h1{
	position:absolute;
	top:100px;
	left:200px;
}
```

### center element 

```css
.p-box h1{
	margin:auto;
}
```

### hide overflowing text outside container (for scrollbar put auto)
  
  ```css
.p-box h1{
  overflow: hidden;
}
```

### flexbox

 ```css
.flex-container {
  display: flex;
  flex-direction: column; /* this is for vertical. default is horizontal */
  justify-content: ... /* pushes the boxes to the sides or put margins between them or around them*/
  .box2{
  	flex:1; /* will give it 1 unit out of the sum of its brothers flex */
	width/flex-basis: /* does the same */
	flex-wrap: wrap; 
  }
}
```

### grid

 ```css
.grid-container {
  display: grid;
  grid-template-columns: 80px 200px auto 40px; /* widths can use fr like fractions*/
  grid-column-gap: 50px; /* seperate all. same with row */
  grid-auto-rows: minmax(100px, auto); /*same heights to all*/
  justify-items: ... /* pushes the boxes to the sides or put margins between them or around them*/
  align-items: ... /* pushes the boxes vertically*/
  .box{
  	align/justify - self /* box handles itself*/
	grid-column/ row: 1/3 /* handles self width */
  }
}
```

### vars

 ```css
:root {
  --main-bg-color: brown;
}
element {
  background-color: var(--main-bg-color);
}
```
