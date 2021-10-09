In this project, let's build a **Nxt Trendz - Cart Features**.
### Set Up Instructions

<details>
<summary>Click to view</summary>

- Download dependencies by running `npm install`
- Start up the app using `npm start`
</details>

<details>

The app have the following functionalities

- When an _unauthenticated user_ tries to access the **Cart** route, the page should be navigated to Login Route

- Following are the features need to implemented

- Feature 1

  - When an authenticated user tries to add the same product multiple times
    - The quantity of the product should be updated accordingly, and the count of the cart items in the header should be remained same

- Feature 2

  - The total amount and number of items in the cart should be displayed in the Cart Route

- Feature 3

  - In each cart item in the cart
    - The quantity of the product should be incremented by one when the plus icon is clicked
    - The quantity of the product should be decremented by one when the minus icon is clicked
    - When the quantity of the product is one and the minus icon is clicked, then the respective product should be removed from the cart
    - Based on the quantity of the product, the product price and the Cart Summary, i.e the total cost should be updated accordingly

- Feature 4

  - When an _authenticated user_ clicked on the remove button, Cart Item should be removed from the CartList

- Feature 5

  - When an _authenticated user_ clicked on the **Remove all** button, all the Cart Items should be removed from the cart and [EmptyCartView](https://assets.ccbp.in/frontend/content/react-js/nxt-trendz-cart-features-empty-cart-view.png) should be displayed



- Prime User credentials

  ```
   username: rahul
   password: rahul@2021
  ```

- Non-Prime User credentials

  ```
   username: raja
   password: raja@2021
  ```

