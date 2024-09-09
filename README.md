# Shopify Reorder Carousel Snippet
This snippet allows the customer to see their previously ordered items and quickly add them to the cart.
This code loops through a customer's orders and displays each line item as part of the carousel. 
Each item is displayed with Product Image, Product Title, Exact variant option, Price, and a quick add to cart button. 

### Wireframe:
![Screenshot 2024-09-09 at 1 40 33 PM](https://github.com/user-attachments/assets/25dfc5e4-9ebe-4670-b19e-4aebd55da14d)

### How To:
From your theme code editor navigate to your snippets folder. Click 'Add a new snippet', name it whatever you please, and copy/paste the snippet from the liquid file in the repository.
Congratulations! You may now render this snippet anywhere on your website using:
```
{% render 'your-snippet-name' %}
```

### Note:
Depending on use case, you might want to only display this if a customer is logged in with order history.
For this use case wrap the snippet code with the following:

```
{% if customer.orders_count > 0 %}
  {% render 'your-snippet-name' %}
{% endif %}
```

### Reminder!
Don't forget to add your CSS! Happy Coding!

