# Restaurant Server
*Server for David Chu's China Bistro (Menu API)*
[heroku](https://git.heroku.com/trianglium-jhu.git)

## Short Summary of the APIs
### All categories
[https://davids-restaurant.herokuapp.com/categories.json](https://davids-restaurant.herokuapp.com/categories.json)

### Menu items for a particular category
The format of the endpoint is `https://davids-restaurant.herokuapp.com/menu_items.json?category=CATETORY_NAME`.

For example, "Lunch" category, i.e., "L":
[https://davids-restaurant.herokuapp.com/menu_items.json?category=L](https://davids-restaurant.herokuapp.com/menu_items.json?category=L)

### Single menu item
The format of the endpoint is `https://www.davidchuschinabistro.com/menu_items/SHORT_NAME.json`

For example, for "L16" as the `SHORT_NAME`
[https://www.davidchuschinabistro.com/menu_items/L16.json](https://www.davidchuschinabistro.com/menu_items/L16.json)
