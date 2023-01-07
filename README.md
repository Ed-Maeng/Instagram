# Instagram
### Fullstack Responsive MERN Social Media App

## Languages & Frameworks
- React.js, Node.js, Express.js, MaterialUI, MongoDB, Mongoose, JWT, npm

## For running server and website
1. Run server by 'nodemon index.js' in `/Instagram/server`
2. Run website by 'npm run start' in `/Instagram/client`

## Features
- Products: Title, Rating, Details, Price, and Quanitity
- Have option to Add to Cart and Buy Now
<img width="1028" alt="Screen Shot 2022-11-29 at 4 43 42 PM" src="https://user-images.githubusercontent.com/54085719/204679919-40c8ea14-4fea-4555-a957-72641f13605b.png">

- You may also like
<img width="1236" alt="Screen Shot 2022-11-29 at 4 45 16 PM" src="https://user-images.githubusercontent.com/54085719/204680105-98c0fae8-8218-47c5-b5a7-1a8226dda690.png">

- Banner: Summer Sale Item
<img width="1549" alt="Screen Shot 2022-11-29 at 4 47 26 PM" src="https://user-images.githubusercontent.com/54085719/204680316-e452c83d-6643-4571-8892-17b697cc2977.png">

- Footer: Summer Sale Item
<img width="1566" alt="Screen Shot 2022-11-29 at 4 47 52 PM" src="https://user-images.githubusercontent.com/54085719/204680361-b92a3ac9-3223-42dc-a766-85e48b6c7d25.png">

- Cart: List of selected items, Able to delete unwanted items, Subtotal, and Quantitiy
<img width="618" alt="Screen Shot 2022-11-29 at 4 45 43 PM" src="https://user-images.githubusercontent.com/54085719/204680149-8db1213a-0fbf-4a16-8af2-e872ab407558.png">

- Payment Option: using Stripe (success page for buying products)
<img width="1206" alt="Screen Shot 2022-11-29 at 4 46 46 PM" src="https://user-images.githubusercontent.com/54085719/204680249-c54524e2-7f8b-4289-be7a-e6e77ea338d3.png">

## Componenets
- Cart, Product, Navbar, Footer, FooterBanner, and HeroBanner
- Used StateContext to keep track of price, quanitity, and cart items

## Product Details
- File-based Routing and Data Fetching using Next.js
- Used methods: `getStaticProps`, `getStaticPaths`, and `getServerSideProps`

## Sanity
- Created Schema for product and banner
- Hooked up Sanity using Sanity Client

## Stripe
- Payments: Stored through Stripes Dashboard under Payments with list of items and prices
- Shipping Rates: Free Shipping ($0) and Fast Shipping ($20)
- Entire Checkout Process: https://stripe.com/docs/checkout/quickstart?client=next using Prebuilt Checkout Page in Next.js
