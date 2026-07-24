💡 Reflection Questions (Answer in your README.md)

Ques. What was the most "painful" part of building this without a framework?

Ans. The hardest part was writing everything manually, like the routes and server, because there was no framework to make it easier.

Ques. Why do you think we need to manually collect "chunks" of data in the POST route?

Ans. Because the data does not arrive all at once. We collect all the pieces first before using the data.

Ques. What HTTP status code did we return when a task was successfully created, and why?

Ans. We returned 201 Created because it means a new task was successfully added

Ques. If you had to add a DELETE route, what would the code look like? (Write a short pseudo-code snippet.)

Ans. This code checks if the request is DELETE, removes the task, and returns a success message.
