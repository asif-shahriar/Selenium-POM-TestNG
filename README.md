# Selenium-POM-TestNG
## Prerequisites
* Install jdk 1.8 or any LTS version
* Configure **JAVA_HOME** and **GRADLE_HOME**
* Download Allure 2.17.2 and configure environment path
* Stable internet connection
## How to run this project
* Clone the repo
* Open cmd in the root folder
* Give following commands:
```
gradle clean test
```
```
allure generate allure-results --clean -o allure-report
```
```
allure serve allure-results
```

These are the snapshots of the allure reports:


![1](https://user-images.githubusercontent.com/71173675/151309260-ed5740aa-614c-4d2c-80ee-b57b65e33aae.png)

![2](https://user-images.githubusercontent.com/71173675/151309271-7e08675a-53a2-4207-9802-f6257fec7ba4.png)

![3](https://user-images.githubusercontent.com/71173675/151309282-8efcba09-51f6-4df3-8004-4f18c51249b0.png)
