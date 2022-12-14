# Random-User-API-Performance-Test
## Scenario
Here Load testing is performed using RandomUser API where the expected load is 1,20,000 within 12 hour. Severall tests has been performed for 60s, 300s, 600s and 900s load using Jmeter. The tests having TPS breakdown and also Bottleneck/stress test point are summarized in Excel spreadsheet and the images of tests screenshots are attached in doc file containing HTML report for the last test of 900s having 2500 users.

The excel report and word file can be accessed from:
- [Excel report, bottleneck/stress test point report and Word file having test screenshots](https://github.com/dolna1610/Random-User-API-Performance-Test/tree/main/Resources)

## Overall TPS and test breakdown.
![User-API-load-TPS](https://user-images.githubusercontent.com/93023509/194759740-6e71c453-1c64-41c7-8bfc-44ca76c6d0a0.PNG)

## Individual Test Reports
- 166 users for 60 seconds

     ![60s](https://user-images.githubusercontent.com/93023509/194759843-0d4e31d1-20d8-4f08-82f2-e9e7b41e2fcf.PNG)
- 833 users for 300 seconds

     ![300s](https://user-images.githubusercontent.com/93023509/194759882-885b9c34-f12c-4bd1-b8b6-7981544adcfb.PNG)
- 1667 users for 600 seconds

     ![600sn](https://user-images.githubusercontent.com/93023509/194759929-14d302be-03b8-4931-ab53-263b2f8e49ec.PNG)
- 2500 users for 900 seconds

   ![Users-API-2500u-900s](https://user-images.githubusercontent.com/93023509/194760455-123a1e01-eec2-4405-888d-64967784f3da.PNG)


## HTML summery report.
 - For 2500 users of 900 seconds.
     
     ![usersAPI-htmlsummery](https://user-images.githubusercontent.com/93023509/194760113-3774a246-47a0-454a-91d5-5fb267745d9f.PNG)
