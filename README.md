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

