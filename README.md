# Country-Capital-API
Enter the capital city - get the country name.


## Table of contents
* [Description](#description)
* [Technologies](#technologies)
* [Usage](#usage)

## Description
This ia an API, written in Python and Flask, which return the country name when a capital city is provided.
	
## Technologies
Project is created with:
* Python version :3.6+
* Flask 
* uvicorn server 

	
## Usage

**User Endpoints**

* **URL**
https://example.com/country-capital/<query-params>
  
* **Method:**
  'GET'

* **Success Response:**
  * **Code:** 200 <br />
    **Content:** `{ id : 12, name : "Michael Bloom" }`

* **Error Response:**

  * **Code:** 404 NOT FOUND <br />
    **Content:** `{ error : "No such country" }`
  
