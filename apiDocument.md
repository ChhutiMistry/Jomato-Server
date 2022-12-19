>>>>> Page 0
> Welcome page
// Localhost // "localhost:1600"
// LiveUrl // "https://jomato-server.onrender.com/"

>>>>> Page 1
> List of cities
// Localhost // "localhost:1600/location"
// LiveUrl // "https://jomato-server.onrender.com/location"

// Localhost // "localhost:1600/city"
// LiveUrl // "https://jomato-server.onrender.com/city"

> List of restaurants
// Localhost // "localhost:1600/restaurant"
// LiveUrl // "https://jomato-server.onrender.com/restaurant"

> List of restaurants on the basis of city
// Localhost // "localhost:1600/restaurants?state_id=1"
// LiveUrl // "https://jomato-server.onrender.com/restaurants?state_id=1"

> List of mealtypes
// Localhost // "localhost:1600/mealtype"
// LiveUrl // "https://jomato-server.onrender.com/mealtype"

>>>>> Page 2

> List of restaurants on the basis of meal
// Localhost // "localhost:1600/restaurants?meal_id=1"
// LiveUrl // "https://jomato-server.onrender.com/restaurants?meal_id=1"

> Filter on the basis of cuisine
// Localhost // "localhost:1600/filters/6?cuisineId=1"
// LiveUrl // "https://jomato-server.onrender.com/filters/6?cuisineId=1"

> Filter on the basis of mealtype
// Localhost // "localhost:1600/filters/5"
// LiveUrl // "https://jomato-server.onrender.com/filters/5"

> Filter on the basis of cost
// Localhost // "localhost:1600/filters/2?lcost=800&hcost=2000"
// LiveUrl // "https://jomato-server.onrender.com/filters/2?lcost=800&hcost=2000"

>>>>> Page 3

> Details of restaurants
// Localhost // "localhost:1600/restaurantdetails/1"
// LiveUrl // "https://jomato-server.onrender.com/restaurantdetails/1"

> Menu on the basis of restaurants
// Localhost // "localhost:1600/menu?restaurantId=1"
// LiveUrl // "https://jomato-server.onrender.com/menu?restaurantId=1"

>>>>> Page 4

> Menu details of item selected
// (post) // "localhost:1600/menuItem"
// (body) // [1, 4, 7]

> Place orders
// (post) // "localhost:1600/placeOrder"
// (body) //
{
     "name": "Chhuti Mistry",
     "email": "chhuti246@gmail.com",
     "address": "Azad Hind Nagar",
     "phone": "+918170974173",
     "cost": "458",
     "menuItem": [1, 3, 5],
     "status": "pending"
}

>>>>> Page 5

> See all placed orders
// Localhost // "localhost:1600/viewOrder"
// LiveUrl // "https://jomato-server.onrender.com/viewOrder"

> Get order details on the basis email address
// Localhost // "localhost:1600/viewOrder?email=chhuti246@gmail.com"
// LiveUrl // "https://jomato-server.onrender.com/viewOrder?email=chhuti246@gmail.com"