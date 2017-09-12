## HTTPS vs HTTP
- HTTPS (Hyper Text Transfer Protocol Secure) is a secure version of HTTP. All communications between your browser and server is encrypted.

- To setup HTTPS for website, need to buy, activate, and install SSL certificate.


## Ring Buffer
### What is it?
- A data structure. The way a ring buffer works is to think of the array as circular rather than linear, connecting end-to-end.

### Why is it useful?
- Allows unshift() method to execute in O(1) time because we keep track of

### A ring buffer's key functionality
- find(index)
- #unshift(item)
- #push(item)
- #delete(item)

### What to Keep Track Of?
- Length of stored data
- capacity (used to track when to resize array, different from length)
- location in memory
- start location, or memory location of arr[0]

[https://github.com/appacademy/sf-job-search-curriculum/blob/master/algorithms/arrays/arrays_reading.md]


### Load Balancer in Web Architecture
- Acts like middleware to distribute load to different servers, balancing the load.

## CSRF (Cross-Site Request Forgery)
- Formal definition: An attack that forces a user to execute unwanted actions on a web application in which they're currently authenticated.

- For example: User visits a form that says, "Click to win a puppy!". If user clicks, it instead issues a POST request to facebook.com to like a/A's page.
- CSRF is a form to have users like a page
- To prevent CSRF attacks on your forms, set an authenticity token in your session. (An authenticity token is just a random number with no special meaning.)
- On any non-GET request, Rails protects you from CSRF by either raising the `ActionController::InvalidAuthenticityToken` exception**, or logging out user by changing :exception to :null_session, which clears session.

## XSS (Cross-site Scripting)
- Expose vulnerabilities on client-side to manipulate client-side scripts like HTML and JS to execute in a manner desired by malicious user.

- i.e. Attacker sends victim a misleading email with a link containing malicious JS.


## Difference between XSS and CSRF
- Cross-site Request Forgery occurs during authenticated sessions. Cross-site scripting doesn't need an authenticated session.
-



## Event Loop in JS
- The event loop is a queue of callback functions. When an async function executes, the callback function is pushed into the queue. The event loop isn't processed until the code after an async function has
