## Part 1

![addMessage1](addMessage1.png)  
One method that is called is handleRequest with input of http://localhost:4010/add-message?s=Hello. Here the path field is set to "/add-message" and query field is set to "s=Hello". The index field is set to 1 and message field is set to "Hello". The messages field goes from empty to containing "Hello". The buildResponse() method is also called. Here the response field is set to an empty String and then "Hello" is added to it.

![addMessage2](addMessage2.png)
One method that is called is handleRequest with input of http://localhost:4010/add-message?s=How%20are%20you. Here the path field is set to "/add-message" and query is set to "s=How%20are%20you". The index field is set to 1 and message field is set to "How are you". The messages field goes from "Hello" to "Hello" and "How are you". The buildResponse method is also called. The response field is set to an empty string and then both "Hello" and "How are you" are added to it.

## Part 2



## Part 3
