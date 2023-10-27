# SOLUTION

### Difference between justify-items and justify-self

#### **justify-items**
- The `justify-items` property in CSS Grid Layout is used to align all grid items within the grid cells along the inline (row) axis.
- The property is applied to the container, and all items within the container will be aligned according to the specified value.

Example:

```html
<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
</div>
```

```css
.grid-container {
  display: grid;
  grid-template-columns: 100px 100px;
  justify-items: center; /* Aligns all grid items in the center */
  grid-gap: 10px;
}

.grid-item {
  background-color: #3498db;
  color: #ffffff;
  padding: 20px;
}
```
In this example, the `justify-items` property is set to center, which aligns all the grid items within the grid cells to the center.


#### **justify-self**
- The `justify-self` property in CSS Grid Layout is used to align individual grid items within their respective grid cells along the inline (row) axis. 
- The property is applied to each item individually, allowing different items within the same container to have different horizontal alignments.

Example :

```html
<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
</div>
```
```css
.grid-container {
  display: grid;
  grid-template-columns: 100px 100px;
  grid-gap: 10px;
}

.grid-item {
  background-color: #3498db;
  color: #ffffff;
  padding: 20px;
  justify-self: end; /* Aligns the individual grid items to the end within their respective cells */
}
```

In this example, the `justify-self` property is set to end, which aligns the individual grid items to the end within their respective cells.




