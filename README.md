# Product List

**Project: Product List**

*Description*: Develop a product listing page with the ability to filter products by category.

**Step-by-Step Instructions**:
1. Set up a React app.
2. Create a component called "ProductList" that manages a list of products in its state.
3. Design a product card component.
4. Render a list of products using the product card component.
5. Add filter buttons for different product categories.
6. Implement an event handler to filter products based on the selected category.
7. make sure you style your app.

**CSS code**

```
/* ProductList.css */
.product-list {
  display: flex;
  flex-wrap: wrap;
}

.product-card {
  width: 250px;
  margin: 1rem;
  padding: 1rem;
  border: 1px solid #ccc;
  border-radius: 5px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.filter-buttons {
  margin: 1rem 0;
}

.filter-button {
  background-color: #007bff;
  color: #fff;
  border: none;
  padding: 0.5rem 1rem;
  margin-right: 0.5rem;
  cursor: pointer;
}

.filter-button:hover {
  background-color: #0056b3;
}
```

