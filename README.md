# E-commerce Admin Site

This is an Admin Dashboard for an E-Commerce [Website](https://github.com/p-H-7/Customer-FrontEnd/edit/main/README.md) .

* [Next.js](https://nextjs.org/) project, [TailwindCSS](https://tailwindcss.com/) is used for styling, [MongoDB](https://www.mongodb.com/) used for backend. An Opensource [NextAuth,js](https://next-auth.js.org/) is used for Google Authentication Login.

## Getting Started
Kickstart by 
Use the `npm install` command to install dependencies.

Start the application on terminal by these two commands `yarn build` and `yarn start`

Admin has Login Authentication using Google provider from Nextjs.Auth. Can be accessed only through single mail (currenty using mine).
*  Dashboard has a display of **View Order Analytics** where list of all orders are shown.
*  ***Categories*** page where we can **Add** **delete** or **Edit** Categories and a **Sub Category**.
*  ***Products*** page where we can **Add** **delete** or **Edit** our products into a **Category** and a **Sub Category**.


Mongo DB database is divided into following collecions as "accounts", "categories", "orders", "products", "sessions", "users".
* Users and Accounts. As single user can have multiple accounts.
* User Authentication is an array of `provider`,` _id`, `access_token`, `scope`.
* Categories is an array of `category_id`, `name`, `parent`, `properties`.
* Orders is an array of `Order_id`, `date`, `total price`, `paid`.

![282325979-baef56f1-da8c-43df-bd5a-9e9ef0e494da](https://github.com/p-H-7/E-Commerce-Admin/assets/82563863/b70380b4-3c38-4633-94e0-4491c0ae2e88)


## AWS 
S3 buckets of AWS is used for file upload.
![image](https://github.com/p-H-7/E-Commerce-Admin/assets/82563863/40609a7e-f5c3-407e-b452-3dbb9de6ba37)


Below are the images of working sites.
![image](https://github.com/p-H-7/E-Commerce-Admin/assets/82563863/0cd6dc19-60da-4645-afc7-3a892594dde5)

![image](https://github.com/p-H-7/E-Commerce-Admin/assets/82563863/633674a1-6dbc-4e1c-9a76-f5a467822ef2)
![image](https://github.com/p-H-7/E-Commerce-Admin/assets/82563863/c52f8cc1-7e94-462a-abd2-2fffc5043613)
