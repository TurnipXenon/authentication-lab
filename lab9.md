# Lab 9

## Question 1

Django by default handles auth with sessions. The server keeps the session data while the client only receives the
session key to this.

## Question 2

httpie uses HTTP Basic Auth.

## Question 3

Token Authentication gives the keys or tokens to the clients, unlike Sessions which only gives them the key. Basic auth
passes the credentials as clear text or easily decodable data, unlike tokens.

## Question 4

Client logs in with Google, Google returns some code and tokens for client, which are then given to bitbucket, bitbucket
then gives this code to Google, Google then gives bitbucket the tokens, and bitbucket confirms that the client's
credentials are correct, or shows the resources restricted for the client.

## Question 5

https://github.com/TurnipXenon/authentication-lab
