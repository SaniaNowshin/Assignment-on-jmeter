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

  ![Load test (Report)](https://github.com/user-attachments/assets/962f6dcf-a89a-42b2-a652-4f004859b483)
  
![Load test](https://github.com/user-attachments/assets/f9b033ed-5d7c-4f45-8a14-ef2f25d9da33)


 

 -	Stress Test

   ![Stress test(report)](https://github.com/user-attachments/assets/b86f0771-31bc-4cfd-ac3d-395176ab046f)

   ![Stress Test](https://github.com/user-attachments/assets/b3a17ac4-2703-4746-ae70-11c8dd0af933)




## Documentation for the API(dmoney):

![dmoney(requests Summary)](https://github.com/user-attachments/assets/79cdf509-7c98-4b22-a768-4250bb26bf90)
![dmoney(statistics)](https://github.com/user-attachments/assets/4ba3c60a-a584-4a48-8ee5-d674539f6aad)




