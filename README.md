Assuming that your application has built and deployed correctly, you can use a tool such as Postman (https://www.postman.com) to test the lilve web version.  You can make GET requests, passing the data in as x-www-form-urlencoded named variable.  For example, to test the ReversString operation, you can make a GET request to https://uoh-500088-0X.azurewebsites.net/api/ReverseString , with the form variable "data" containing the data in the body of the message.  In addition to the functionality that you and your colleagues have been working on, there are also some integration methods:

  - NthSentence(string data, int n) // returns sentence n from the text
  - NthLine(string data, int lineLength, int n) // returns the n line from text when it is formatted in lines no longer than lineLength
  - JustifiedText(string data, int lineLength) // Returns text split into lines exactly lineLength characters long, padded internally to ensure starting and ending at a neat edge
  - HighlightTopWords(string data, int n) // returns the text but with the most popular n words highlighted
