# http-post-caller

## Description
Invoke a POST request to a given `url` by making a GET request to this website.

## How to use
1. Get the POST url that you want to call;
2. Encode the url in [base64](https://www.base64encode.org/);
3. Make a GET request to `https://worgho2.github.io/http-post-caller?url=<BASE64_POST_URL>`

## Practical Applications
- Useful when you need to put a link inside an email that accepts POST requests.
- Useful to call a POST webhook from browser.
