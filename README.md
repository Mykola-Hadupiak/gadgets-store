# [Gadgets store](https://mykola-hadupiak.github.io/gadgets_store/)

This is a full-fledged store that has product categories, product cards, sliders, pagination, carousel, breadcrumbs, cart, search and favorites.

It has 5 main pages (home page, pages of different products, product details page, favorites page, cart page), and it also has additional pages such as Page Not Found or errors.

It adapts to different devices as much as possible. 

Also on the whole page there are animations (on hover or on click) that are made using SCSS or Swiper.

# The main technologies that were used:
* React (tsx), React Router, Redux toolkit (inc. thunk), Swiper
* HTML, SCSS, JS, TS, debounce, API, fetch, localStorage
* Google fonts
* Grid, flexbox, BEM, webkit
* Media queries, mixins, @for, scss variables

# About the project

** **
* **Home page** is the main page where you are greeted with a beautiful carousel, sliders and product categories.

** **
* **Category page** (phones, tablets, accessories).
On this page you can also see breadcrumbs, the ability to sort products and select the number of products on the page, and also, you see product cards with pagination. Also, you can use the search and search for products by their name. Of course, you can click on the product card and you will be taken to a page with detailed information about it.

** **
* **Product details page**. On this page you can see complete information about the product, as well as all the photos that you can switch between. Also, on this page you can select the appropriate product for you (color, memory capacity, etc.). Well, of course, you can add the product to your cart or favorites. Also, at the very bottom, you can see a selection of the most suitable products for you.

** **
* **Favourites page.** As soon as you click on the favorites button, you will add the product to your favorites list, which is saved in your local storage, where you can also use the search or go to the product to look at it again. Of course, if your favorites list is empty, you will see the corresponding message.
* 
** **
* **Cart page.** On this page you can see all the products you have added to your cart. Also, you can increase or decrease the quantity of goods, after which you can click on the checkout button (this function is not currently implemented, but you will see the corresponding payment window)

  
# Demo:
[DEMO LINK](https://mykola-hadupiak.github.io/gadgets_store/)
