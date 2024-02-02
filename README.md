# Happy Farm

- Happy Farm is a web application to moderate the product prices between producers and consumers
- The objective is to let the producers govern the price of their products and not the retailers

## Tech Stack : MERN

- User can login/signup and checkout and place orders
- Admin can add/delete/update product details and can track orders.

## Setup Locally :

- git clone "repo"
- run `npm i`
- cd client
- npm i
- cd ..
- create a file named .env in your project folder
- paste the below code in it :

```
NODE_ENV=production
CLIENT_URL=https://localhost:3000
PORT=8000
BRAINTREE_ID=your_braintree_id
BRAINTREE_PRIVATE=your_braintree_private
BRAINTREE_PUBLIC=your_braintree_public
MONGO_URI = your_atlas_db_uri
```

10. run : npm run dev
11. goto http://localhost:3000

## Project Flow

![image](https://user-images.githubusercontent.com/30918023/119221494-53cf5e00-bb0d-11eb-8304-b059320391b8.png)
