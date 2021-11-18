<div id="top"></div>  

[![License](https://img.shields.io/badge/Licence-MIT-brightgreen?style=plastic)](#licence)  
  
<br>

# E-COMMERCE BACK END (ORM)  
<br>

## Table of Contents
  
  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Licence](#licence)
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [Links](#links)
  * [Questions](#questions)
  
<br>

## Description  
The back-end application demonstrates the use of MySQL and relational mapping within database tables.  
<br>
<p align="right">(<a href="#top">back to top</a>)</p>
  
  
## Installation  
The application requires the following modules to be installed:  
 * node.js  
 * mysql2.js  
 * sequalize.js
 * express.js  
 * dotenv.js
The above packages can be installed using npm insall at the command prompt.  

<br>
<p align="right">(<a href="#top">back to top</a>)</p>
  
## Usage
You will need to initialise the MySQL databse as follows:  
After logging into MySQL (mysql -u (username) -p enter the command >source db/schema.sql;  
After the database is initialised you can enter >npm run seed to seed the database.  
Then start the application >npm run start  
  
Using Insomnia or similar software, enter the routes as follows to interrogate the database:
localhost:3001/api/categories/  
localhost:3001/api/products/  
localhost:3001/apt/tags/  
GET will get all associated data  
If you add an id numer then only that ID will be displayed  
POST will create a new entry  
PUT to update an entry  
DELETE with an id number to delete the entry  
Use the following JSON formats for creating and updating
for Categorys:  
{  
   "category_name": "Coats"  
}  
for Products:  
{  
   "product_name" : "Business Shirt",  
   "price": 200.00,  
   "stock": 3,  
   "category_id":1,  
   "tagIds": [1, 2, 3, 4]  
}  
for Tags:  
{  
   "tag_name" : " Zebra Stripes"  
}  
<br>
<p align="right">(<a href="#top">back to top</a>)</p>
  
## Licence
Copyright 2021 Stuart Simmons  
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files  
(the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:  
    
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.  
    
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,  
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
<p align="right">(<a href="#top">back to top</a>)</p>
  
## Contributing
When contributing to this repository, please first discuss the change you wish to make via email  
  with the owners of this repository before making a pull request<br>
<p align="right">(<a href="#top">back to top</a>)</p>
  
## Tests
No test files yet, check again soon<br>
<p align="right">(<a href="#top">back to top</a>)</p>
  
## Links
Operational Video Link: https://drive.google.com/file/d/1h4qNv9zqjRKv7ol8i7EF1rsmLlZO4t2v/view?usp=sharing  
Github Link: https://github.com/Pilot67/e-commerce-back-end  
<p align="right">(<a href="#top">back to top</a>)</p>
  
## Questions
Please direct any questions my Github profile or diret email.  
My github profile, Pilot67, can be found [here](https://github.com/Pilot67)  
If you would like to contact me directly please email me at developer@simmons1.net  
<p align="right">(<a href="#top">back to top</a>)</p>  
