# angular-formspree
Angular directive for formspree.io

## Demo
You can see a working demo at [jasonvoirin.com](http://www.jasonvoirin.com)

## Dependencies
No dependencies are required. However, angular-formspree was built with bootstrap css.

## Setup Instructions
1. Add the angular-formspree directive script tag in your header: <br>
<pre><code><script src="js/directives/angular-formspree.js"></script></code></pre>
2. Add 'angularFormspree' as a module dependancy:
<pre><code>angular.module('yourAppModule', ['angularFormspree']);</code></pre>
3. In the angular-formspree directive, set your timer and list your image locations in the “scope.images” array: <br>
<pre><code>
//1. Add the email you want the messages to be sent<br>
var email = "jasonvoirin@gmail.com";<br>
//2. Add the email subject line <br>
var email_subject = "JasonVoirin.com Contact Form Submission";<br>
//3. Add a message the user will see when the form is submitted successfully<br>
var success_message = "Your message was sent! We will be in touch soon.";<br>
//4. Add a message the user will see if the form receives an error and does not submit successfully<br>
var error_message = "Oops. There was an error when trying to send your message.";<br>
</code></pre>
4. Add <code>\<angular-formspree>\</angular-formspree></code> where you want the form to show.<br>


## Donate 
Github charges me a monthly fee to contribute this code to our development community. Help me cover the cost by donating via [Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2SYBU2SUZCJUE).



