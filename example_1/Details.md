Details
Your task is to write a client-server application for a vacation planner application. The main requirements of the application are as follows:
A client sends a request for booking a vacation package, by specifying the family size, number of days and whether meals are to be included.
The main steps are as follows:
1. The server sends prompts to the client to send each of the required data. E.g. The prompt for the first data may look like:
‘Welcome to vacation planner! Our prices are as follows:
The travel cost by ferry per person is 600 SEK. For air travel, it will be 900 SEK.
Accommodation is 250 SEK per person per night. Meals cost 100 SEK per person per day.
Please Enter number of travelers:- ‘
2. The client sends the requested information.
3. The server asks the client to send the following information, by sending appropriate prompt for each input:
Ferry or Air travel
Number of days
Meal included or not
4. The client gives appropriate response to each prompt from the server.
5. The server calculates the price according to the calculation method described above and sends the complete information (input from the client and calculated price) to the client.
6. The server prompts the client to confirm acceptance by sending the following information (one after the other): Contact name, Phone number and Address
7. The server saves all the booking information in a disk file (Contact name, ID number, number of nights, total price, and so on).
8. The server sends a message to the client to confirm that the booking is successful.9. The communication is terminated gracefully on both sides.
