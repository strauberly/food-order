# Food Order App

### An application designed to practice learned concepts in React such as state management and passing state and data between components, context utilization, forwarding refs, and useEffect. Supabase is utilized for building a quick remote backend. This README serves as a dev journal until application is complete.

---

-- 20 Sept 2022 --

-Generic error handling implementation in AvailableMeals.js in case http request fails.

---

-- 19 Sept 2022 --

- Took a minute to get the syntax down but meals are now successfully loaded from a supabase API. Yay documentation!

---

-- 18 Sept 2022 --

- will utilize supabase for remote database.

---

-- 15 Sept 2022 --

- Recieved additional specs for application.
  - add checkout/order form.
  - submit orders to remote backend.
  - fetch meals data from remote backend.

---

-- 15 Aug 2022 --

- Cart icon now updates with amount of items added to the cart and displays them as desired from a cart modal.
- Amount of an item can be edited in the cart modal and the price is reflective of those changes.
- Animation added to cart button for easy visual confirmation that an item has been added to the cart.
- This concludes the current lecture set though I believe we will be using this project again later down the road,

---

-- 14 Aug 2022 --

- Cart icon now updates with amount of items added to the cart.

---

-- 13 Aug 2022 --

- Cart context created.
- Cart reducer created. Next add item to cart call

---

-- 12 Aug 2022 --

- Cart component visually available, beginning work on functionality.
- Cart modal window opens and closes as expected.
- Implemented cart context provider so that it can be accessed from multiple places in the app for updating cart with new item or deleting something we dont truly want.

---

-- 11 Aug 2022 --

- Began work on cart component.

---

-- 9 Aug 2022 --

- Created component to display meal/menu items by mapping the items to a map and accessing the properties of each item and displaying them with in a card as list items.
- Created Input component for user to specify desired amount of a food item.
- Created form component with button for adding desired items to the cart.

---

-- 8 Aug 2022 --

- Created Header component.
- Created Button component.
- Created Meals component.

---

-- 5 Aug 2022 --

Application setup and repository initialization...

---

---
