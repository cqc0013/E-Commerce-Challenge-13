# E-Commerce-Challenge-13
    

    
An E-Commerce Site Back End that utilizes a REST API to store information about the products, product categories, and product tags sold on the site.
    

    
## Installation
    
To install this API, use the attached [link](https://github.com/cqc0013/E-Commerce-Challenge-13) to clone the git repository to your local system. Then run the command `npm install`. In an integrated terminal to install the required dependencies to your system. Next, in the project directory create a `.env` file that contains the following text:

`DB_NAME='ecommerce_db'`\
`DB_USER='your_user'`\
`DB_PASSWORD='your_password'`
    
## Usage

To run this program, run the following command in an integrated terminal to create a new `ecommerce_db`.

`psql -U your_user`

Enter your postgres password when prompeted, and then run the command:

`\i ./db/schema.sql`

To optionally seed your database, run the following command:

`npm run seed`

To intialize your local systems connection to your newly created database, run the following command:

`npm start`

API calls may then be made using the following format:

`localhost:3001/api/path_parameters`