1) Creat folder Structure
creat root folder as Jsamazona
add frontend and backend folder
creat src folder in frontend
create index.html with heading
run npm init in frontend folder
npm install -D live server
add start command as live-server src --verbose
run npm start.
Designing the site
==============
2) Create style.css
link style.css to index.html
create div.grid container
creat header, main and footer
style html, body
style grid-container, header, main and footer

3)Create Static Home Screen
=============
create ul.products
creat li
create div.product
add .product-image, 'pro-name, .product-price
style ul.products and internal divs
duplicate 2 times to show 3 products
4)Render Dynamic Home Screen
creat data.js
export an arry of 6 products
creat screen/ HomeScreen.js
export HomeScreen as an object with render() method 
implement render()
import data.js
link it to index.html as module
set main id to main_container
creat router() function
set main_container innerHTML to HomeScreen.render()
set load event of window to render() function.
4) Build Url Router
creat routes as route:screen object for home screen.
create utils.js
export parseRequestURL()
set url as hash address split by slash
return resource, id and verb of url
update router()
set request as perseRequestURL()
build parsedUrl and compare with routes
if route exists render it, else render Error404
create screens/Error404.js and render error message.