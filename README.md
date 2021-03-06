# Currency Exchanger

#### An application that allows users to convert U.S. dollars to another currency using ExchangeRate-API

#### By Araceli Valdovinos

![Converter_image](currency_image.png)
_[Currency Converter Live Site](https://aracelivaldovinos.github.io/js-currency-converter/)_

## Technologies Used

* _HTML_
* _CSS/Bootstrap_
* _JavaScript/jQuery_
* _Webpack_
* _Node Package Manager_


## Description
_A currency exchange application that allows a user to type in an amount (in U.S. dollars) and then choose which currency it should be converted to (Euro, Yen, Australian Dollars, Canada Dollars, Pounds). To determine the most recent exchange rate, your application will make an API call to the following exchange rate API: [ExchangeRate-API](https://www.exchangerate-api.com/). The application must do the following:_
* _A user should be able to enter an amount (in U.S. dollars) and then specify another currency (such as the South Korean won). The user should then see the total amount they entered in converted currency. In the example above, a user might enter 10 dollars and then see that amount in South Korean won._
* _Users should be able to convert U.S. currency into at least 5 other types of currency._
* _If the API call results in an error (any message not a 200 OK), the application should return a notification to the user that states what the error is. (That means the error should show up in the DOM, not in the console.)_
* _If the query response doesn't include that particular currency, the application should return a notification that states the currency in question doesn't exist. (Note: Even if you use a dropdown menu to specify currencies instead of a form field, you'll still need to add this functionality to your code.)_


## Setup/Installation Requirements

* _Clone the repository to desktop using "git clone" in terminal._
* _Open cloned folder in text editor of your choice._
* _Create an '.env' file in the project root directory._
* _Register for a free API by visiting the [ExchangeRate-API](https://www.exchangerate-api.com/) site . Input your email address and click the "Get Free Key" button._
* _Complete registration for a key then copy and paste API key in the .env file._
* _In the .env file, add the API key in place of  [Your API KEY] in the "API_KEY=[Your API KEY]" template._
* _Add ".env" in the .gitignore file in order to hide .env file from the public._
* _Run "npm install" in the terminal or command line to download dependencies._
* _Run "npm run start" in terminal._

## Known Bugs/Goals

* _Add API tests._
* _Round counversion output_

## License
_[MIT](https://opensource.org/licenses/MIT) (c) 2021 Araceli Valdovinos_


## Contact Information
_Araceli Valdovinos araceli.valdovinos@outlook.com_