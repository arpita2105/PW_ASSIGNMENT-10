# SOLUTION

### **grid-auto-row**

The `grid-auto-rows` property in CSS Grid Layout is used to specify the size of implicitly created rows in a grid. This is particularly useful when you have grid items that don't explicitly specify a row size. 

```html
<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
  <div class="grid-item">5</div>
  <div class="grid-item">6</div>
  <div class="grid-item">7</div>
  <div class="grid-item">8</div>
</div>
```

```css
.grid-container {
    display: grid;
    grid-template-columns: 100px 100px;
    grid-auto-rows: 50px; /* Set the height for implicitly created rows */
    grid-gap: 10px;
  }
  .grid-item {
    background-color: #3498db;
    color: #ffffff;
    padding: 20px;
  }
```

In this example, the `grid-auto-rows` property sets the height for implicitly created rows to 50px. Any grid items that do not explicitly define a row size will automatically have a height of 50px. The `grid-gap` property is used to create space between the grid items.

Output :
![solution 3 row](https://github.com/arpita2105/PW_ASSIGNMENT-10/assets/136358528/6aea2031-84be-49e2-b296-6c9f00db3d26)

### **grid-auto-column**
The `grid-auto-columns` property in CSS Grid Layout is used to specify the size of implicitly created columns in a grid. This property is particularly useful when you have grid items that don't explicitly specify a column size. 

```html
<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
  <div class="grid-item">5</div>
  <div class="grid-item">6</div>
</div>
```

```css
.grid-container {
    display: grid;
    grid-template-rows: 100px 100px;
    grid-auto-columns: 100px; /* Set the width for implicitly created columns */
    grid-gap: 10px;
  }
  .grid-item {
    background-color: #3498db;
    color: #ffffff;
    padding: 20px;
  }
```

In this example, the `grid-auto-columns` property sets the width for implicitly created columns to 100px. Any grid items that are not explicitly placed in the grid with a specific column size will automatically have a width of 100px.

Output:
![solution 3 column](https://github.com/arpita2105/PW_ASSIGNMENT-10/assets/136358528/0a96d6fe-28e9-4d4a-9a22-754a79587861)
