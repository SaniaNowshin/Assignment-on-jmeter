# Jmeter Performance Testing

## Project Summary: 
     This project demonstrates performance testing using Apache JMeter. The tests were designed to assess the throughput and performance of two APIs:
     1.	Booking API: Simulates user interactions for creating and searching bookings. The project includes both load and stress tests.
     2.	Dmoney API: Simulates various financial transactions such as deposits, withdrawals, payments, and money transfers by using dynamic data generation and parameterization for realistic testing scenarios.


## Technologies I have used:

- Apache JMeter
- Java Runtime Environment (JRE)



## How to run?

1.	Clone the Repository
2.	Install Apache Jmeter
3.	Open Jmeter
4.	Configure CSV Files (for Dmoney API): For the Dmoney API test, ensure the following CSV files (deposit.csv, withdraw.csv, sendMoney.csv, payment.csv)
5.	Run the Load Test and the Stress Test (for booking API)
   -a. Select the booking.jmx or dmoney.jmx script in JMeter.
   -b. Click the green Start button at the top to begin running the load test.
   -c. Monitor the test progress in the View Results Tree and Summary Report listeners.


## Documentation for the API(booking):
-	Load Test
 ![Load test (Report)](https://github.com/user-attachments/assets/fcd5297f-5ee2-4148-a5c7-613d39ed5f41)

![Load test](https://github.com/user-attachments/assets/f4bff86d-2b00-4fcf-b6a5-6313ccf1ade5)

 -	Stress Test

  
![Stress Test](https://github.com/user-attachments/assets/f57a32c2-8237-4a8f-b2d8-6459f336a8a4)
![Stress test(report)](https://github.com/user-attachments/assets/419198e4-e353-40a3-846d-c50ade94c049)



## Documentation for the API(dmoney):

![image](https://github.com/user-attachments/assets/5726f254-308a-4c0a-9474-7e8084df8f37)

![image](https://github.com/user-attachments/assets/6b85b254-1d88-4c78-afe9-4262fbfa73ad)





