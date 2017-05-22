# Ping Pong

This is a web app built using javascript and jQuery.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Web Browser.

```
Chrome, Edge, Firefox
```

### Installing

A step by step series of examples that tell you have to get a development env running

Clone the repo
Open the index.html file in the folder you have downloaded in a web browser.


## Sample Tests
Input: 17
Output: [1,2,ping,4,pong,ping,7,8,ping,pong,11,ping,13,14,pingpong,16,17]


## Running the tests

Enter a number above 0 in the input field and press the "Pingpong!" button beside it.

### Break down into end to end tests

The program first checks if your no is above 0. If it is below 0, the useris prompted to enter a no above 0.

The program then loops through each item between 1 and the provided no.

In every loop, the following checks are done:
  The program first checks if the no is divisible by 15 and replaces it with pingpong.
  Next, it checks if the no is divisible by 5 and replaces it with pong.
  It then checks if the no is divisible by 3 and replaces it with ping.

## Built With

* [jQuery](http://jquery.org/) - The javascript library used

## Authors

* **Chris Nyaga** - *Initial work* - [Chris](https://kaziplus.com/@chris)


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
