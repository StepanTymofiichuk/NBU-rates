# Overview
NBU rates&convert app is designed to quickly and easily convert USD, EUR, GBP to UAH. The app is developed using React Native framework.
# Features
- displays official National Bank of Ukraine rate of USD, EUR, GBP for current and for entered date.
- allows to convert USD, EUR, GBP to UAH for current and for entered date.
# Diagrams
![sequence diagram](https://github.com/StepanTymofiichuk/pet-projects/blob/main/sequence.jpg)  
- Get rate for current date  
`GET "https://bank.gov.ua/NBUStatService/v1/statdirectory/exchange?valcode=EUR&date=[DATE]&json"`  
- Get rate for entered date  
`GET "https://bank.gov.ua/NBUStatService/v1/statdirectory/exchange?valcode=[CODE]&date=[DATE]&json"`
# Screens
![sequence diagram](https://github.com/StepanTymofiichuk/pet-projects/blob/main/NBUrates.jpg)
# Download link
- Android:  
https://drive.google.com/file/d/1MYlcS2_d-ZCnhLR31j15zUTrYy1GsbQQ/view?usp=sharing
