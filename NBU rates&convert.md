# Overview
NBU rates&convert app is designed to quickly and easily convert USD, EUR, GBP to UAH. The app is developed using React Native framework.
# Features
- displays official National Bank of Ukraine rate of USD, EUR, GBP for current and for entered date.
- allows to convert USD, EUR, GBP to UAH for current and for entered date.
# Diagrams
![sequence diagram](https://github.com/StepanTymofiichuk/pet-projects/blob/main/sequence.jpg)
### API
- Get currerncy rate for given date - *returns UAH price for specified currency on given date*
`GET "https://bank.gov.ua/NBUStatService/v1/statdirectory/exchange?valcode=[CODE]&date=[DATE]&json"`\
Parameters:\
`valcode` - currency code in ISO-4217\
`date` - currency exchange `date yyyy/mm/dd`
### API Example
- Get UAH to EUR rate for given date\
`https://bank.gov.ua/NBUStatService/v1/statdirectory/exchange?valcode=EUR&date=20200302&json`\
Parameters:\
`valcode` - **EUR**\
`date` - **Mar 2, 2020**\
![api](https://github.com/StepanTymofiichuk/pet-projects/blob/main/api.PNG)
# Screens
![sequence diagram](https://github.com/StepanTymofiichuk/pet-projects/blob/main/NBUrates.jpg)
# Download link
- Android:  
https://drive.google.com/file/d/1MYlcS2_d-ZCnhLR31j15zUTrYy1GsbQQ/view?usp=sharing
