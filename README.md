# Sunrise-Bakery

Welcome to Sunrise Bakery!
Sunrise Bakery is a website for bakers, families, and food enthusiasts who wish to have a change of heart, from the usual restaurant meals, to the taste of homemade baked goods. The site is targetted to the visitors of the locale and those who wish a delivery from Sunrise Bakery. Located in Morning City, Sunrise Bakery will always be useful when it comes to keeping its customers happy by feeding them top-quality baked goods!

# Features

<strong>Navigation Bar</strong>

The Navbar features 5 locations on the website, being Home, Products, Events, Prices, and Contact.

This section will allow users to navigate through the webiste with ease at all times.

<img width="1263" height="76" alt="image" src="https://github.com/user-attachments/assets/e5aba5ea-0cdd-4390-bdff-7d67fa2f4f20" />

<strong>Home Page</strong>

The home page includes an image of the outside of the locale 'Sunrise Bakery'. It also contains the about us information and a button saying "order now!", inciting viewers to go to the prices.html page.

This section will allow users to know more about Sunrise Bakery while giving them an idea of what the place looks like. It will also tell them there is a delivery service.

<img width="1258" height="459" alt="image" src="https://github.com/user-attachments/assets/57e06867-6742-4a75-a88e-752232f2c880" />

<strong>Our Products Section</strong>

This section shows the viewers three cards with distinct cards, each having a corresponding image, card-title, and description. Furthermore, each card has a button that, when clicked, sends the viewer to the prices.html page. 

This section will allow viewers to have a general idea of what Sunrise Bakery has for sale.

<img width="1250" height="610" alt="image" src="https://github.com/user-attachments/assets/f0182fa7-b5b1-458c-bb34-c56903aeb9e2" />

<strong>Upcoming Events</strong>

This section shows the viewers the events hosted by Sunrise Bakery. It also includes the ages allowed to participate, the date, and time. Furthermore, to the left there is a carousel which is used to give the viewers an idea of what each event is about.

This section will make the viewers aware of the events hosted each month, as well as when and who can participate.

<img width="1262" height="517" alt="image" src="https://github.com/user-attachments/assets/c92a3bfa-4d73-4239-ad10-f2e9881285c5" />

<strong>Footer</strong>

This section contains all the social media pages, as well as the location and opening hours of Sunrise Bakery. Furthermore, under the table it is specified that they will be open at all events.

This will allow visitors to connect with Sunrise Bakery through social media. It will also tell the visitors when to come and gain knowledge on the events.

<img width="1261" height="372" alt="image" src="https://github.com/user-attachments/assets/f20bafcf-d4c3-4752-b493-ae7d97ee8943" />

<strong>Prices Section</strong>

This section shows the viewers various cards, each with a different product offered by Sunrise Bakery. It inlcudes the image of the product, the ingredients, the price, and a button to a form for delivery services.

This will allow viewers to see the products and price of baked goods. Furthermore, the ingredients list will warn people of possible harmful ingredients for them (such as allergies)

<img width="1251" height="639" alt="image" src="https://github.com/user-attachments/assets/872baa40-f3e5-4f2e-bca4-cf6e508f9009" />

<strong>Delivery Form</strong>

This section shows a form viewers will have to complete to have baked goods delivered to their house. It also includes messages warning the viewer to check the price of goods and make sure they have cash.

This will allow the users to use Sunrise Bakery's delivery services to get food directly to their home without having to go to the location.

<img width="1252" height="796" alt="image" src="https://github.com/user-attachments/assets/e98311c3-4cb1-4cca-ab8d-28b732341fc7" />

## Testing

<strong>Validator Testing</strong>

HTML: 
One error was found when passing through the official W3C validator
Error: It is related to JS. It will be detailed in the bugs section

CSS
No errors were found when passing through the official (Jigsaw) validator

<strong>Human Testing</strong>

Throughout the building process, viewers entered the website and noted the bugs, errors, and improvements to the website. This allowed for a more accurate building process to what was planned.

Furthermore, users used different screen sizes to view the content of the webpage and express their opinions.

<strong> Bugs </strong>

An interestig bug I found was in the cards section in the prices.html page. Whenever I edited the cards on that page, the cards on the index.html page would change as well. I had to separate classes and create a new one for the cards in the prices page.

An annoying bug I found is still in the Navbar. Whenever an item is clicked, it will stay black until another click is made, then return to its origninal colour. Why does it do this? I have no idea. I have tried changing many things and it still continued changing black.

A nice thing I learnt is the loading="lazy" for images. It helps for the performance of the webpage and makes sure the images are not loaded until they are needed. Nice little trick!

<strong> Unfixed Bugs </strong>

As previously mentioned, a bug shows on line 296 relating to a stray start tag. This has never shown until now and I have no experience on JS (JavaScript).

An annoying bug I could not fix was in the navbar. No matter what was done. Whenever a viewer clicks on products, event, or contact, the button would stay black until the user clicked on the page, then it would return to its original colour. I suspect it is a class from Bootstrap, but I have no found the class yet.


## Deployment
These are the following steps I used to deploy my project (On Github Pages):

1-) Open the repository you wish to deploy.
2-) Go to settings on the item bar on the far right.
3-) On the left dropdown list, go to "Pages"
4-) Make sure the source is "Deploy from a branch".
5-) Make sure the branch comes from "Main" and folder from "root".
6-) Save it and it has been deployed!

Link to live page: https://enrique2007s.github.io/sunrise-bakery/

If link does not work, please try this one: https://enrique2007s.github.io/sunrise-bakery/index.html

## Credits

EMMET: EMMET was an invaluable tool in the code editor. EMMET helped with code suggestions and helped resolve logic errors and simple typos. EMMET takes credit for styling the buttons in the prices.html page and finding mistakes before I could find them.

ChatGPT: ChatGPT was used as a code organizer, image generator, and helper for user stories. The only uses of ChatGPT were organizing code for better readability and mantainability. It generated the three pictures used in the carousel in the events section. It helped me organize the user stories in the projects part of PP1.

artlist.io: Artlist is an image generator used to create the Hero image, or the outside of Sunrise Bakery in the index.html page (the first image).

online image generator: Used to compress images and make them smaller to succeed in the Lighthouse testing.

iStock (by Getty Images): Used to find all the pictures used in the prices.html page.

All the icons across the page were taken from "Font Awesome".

This favicon was generated using the following font:

- Font Title: Leckerli One
- Font Author: undefined
- Font Source: https://fonts.gstatic.com/s/leckerlione/v21/V8mCoQH8VCsNttEnxnGQ-1itLZxcBtItFw.ttf
- Font License: undefined)

Google Fonts: Used for styling fonts across the webpage.

Bootstrap: Used for the carousel, the cards, and nav system.

notengoenie: Used for special characters.

https://www.youtube.com/watch?v=g9b4LjYrsUQ&pp=ygUUaG93IHRvIHVzZSBib290c3RyYXA%3D Learning how to use Bootstrap.








