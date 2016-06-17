# ViaplayAssignment
=======================================================================================
README.TXT
======================================================================================

Details of the files.


TestClient.html
1. I have written a simple HTML form to post in the resource URL.
2. Defaulted the input with the example resource link.
3. Please provide a different URL in the input box to get the trailer URL.
4. The trailer url or an information message gets printed as the response.

app.js
1. This node.js program has all the logics.
2. It starts a http server on port 8081
3. When the client submits a resource link URL, the /getTrailer gets called.
4. There are 3 http requests made in sequence to get the final trailer URL.
5. A steps are explained in comments.


Steps to test

1. Please extract the contents to a folder and run the app.js using command "node app.js"
2. Once the server starts in 8081, the TestClient.html can be used to submit the input.
