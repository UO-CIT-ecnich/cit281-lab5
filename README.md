# Description
In this lab, I started by downloading and installing Postman, which is a tool used for testing web server APIs. This allowed me to interact with my server and send requests. It was important for me to understand how to use Postman effectively.

Next, I created a collection in Postman called "CIT" and organized it into folders. This helped me manage and group my queries, which will be useful in future CIT Minor courses. It was valuable for me to learn how to organize and structure my Postman collections.

Then, I created a Node.js and Fastify server application named "fastify-server.js" in my cit281/p4 folder. I implemented three GET routes in my server code: one to return all students, one to return a single student based on the provided ID, and an unmatched route handler. This allowed me to understand how to create routes and handle different types of requests.

To work with actual data, I added an array of fictitious student objects to my server code. Each student object had properties such as ID, last name, and first name. This helped me understand how to work with data in my server application.

Using Postman, I tested all three GET routes of my server. This was important because it allowed me to verify that my routes were functioning correctly and returning the expected results. I captured screenshots of the Postman requests for each route, which helped me document my testing process.

I also learned how to implement a POST route handler in my server application. This route accepted a JSON request body with properties "last" and "first". I was able to handle the POST verb, add the provided data to the students array, assign a new ID, and return the updated array entry. This taught me how to handle different types of requests in my server application.

Finally, I used Postman to send a POST request to my server. I included a Content-Type header as "application/json" and provided test data in the JSON body. I captured a screenshot of the Postman request, including the URL and the returned new student entry. This exercise helped me understand how to test and validate my server's POST functionality.

Overall, this lab provided me with hands-on experience in developing a server application, testing it using Postman, and understanding the concepts of routing and handling different types of requests. I learned how to organize my Postman collections, work with data in my server application, and ensure that my routes are functioning correctly. These skills are important for building and testing APIs effectively.
