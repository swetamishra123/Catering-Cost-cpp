It looks like you've provided a C++ program for calculating the cost of catering services for an event. To create a README file for your project on GitHub, you can include information about your project, how to compile and run the program, and sample output. Here's a basic README template:

```markdown
# Catering Cost Calculator

This is a simple C++ program that calculates the cost of catering services for an event based on the number of guests and the duration of the event. It takes into account the cost of servers and food to provide an estimate to the customer.

## Usage

To use this program, follow these steps:

1. Clone the repository to your local machine:
   ```sh
   git clone https://github.com/swetamishra123/Catering-Cost-cpp.git
   ```

2. Compile the program using a C++ compiler (e.g., g++):

   ```sh
   g++ catering_cost.cpp -o catering_cost
   ```

3. Run the program:

   ```sh
   ./catering_cost
   ```

4. Follow the prompts to input the event details, including the name of the event, customer name, number of guests, and event duration in minutes.

5. The program will calculate and display the estimated costs, the number of servers required, the cost for servers, the cost for food, the average cost per person, the total cost, and the 25% deposit needed to reserve the event.

## Example

Here's an example of how the program works:

```
Enter the name of the event
Fall Dinner
Enter the customer's first and last name
John Doe
Enter the number of guests
100
Enter the number of minutes in the event
180

Fall Dinner     
Event estimate for  John Doe
Number Of Server: 5
The Cost for Servers: 111.00
The Cost for Food is: 2070.00
Average Cost Per Person: 20.70

Total cost is: 2193.00
Please deposit a 25% deposit to reserve the event
The deposit needed is: 548.25
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
```

Replace the example and usage instructions with the actual information from your program. You can save this content in a file named `README.md` in your GitHub repository to provide clear documentation for your project.
