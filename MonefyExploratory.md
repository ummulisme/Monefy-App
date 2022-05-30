# Monefy-App
## Session Based Exploratory Testing for Monefy app

#### AREAS
OS | Android | FREE Version
#### Strategy | Functional Testing

##### Duration : 90 minutes
### Test Scenarios 
#### Testing Calculator, Calendar, Categories, Performance

#### Charter vs. Opportunity
90% was taken for Charter , however 10% was spent on Category Health and Pet category, for some reason it didn’t show the percentage spent on it. It was intermittent and it got resolved once I cleared the data

### What kind of risks you need to mitigate for this type of app?
1. There is no passcode upon opening the app which means anyone can make changes to the finance.

### Charter 1 :To explore all items available as to know the app, Including verifying that icons take me to New expense module,Search option, New Transfer.
#### Time : 25 mins 
#### Priority : Medium.This would be explored first to know the application
#### Test Notes : Performing a thorough Sanity Testing and spending atleast 5mins on each Module

### Charter 2 : Verify the calculator is working fine and gives the correct percentage for chosen category on new income and new expense
#### Time : 25 mins
#### Priority : High .This would be explored second, as it is the focus functionality of the app. If this doesnot work properly it could messup the entire money management of the user.
#### Test Notes : Adding the highest number in the New Income and deducting more than what is available

### Charter 3 : Verify the Categories,Accounts,Currencies and Settings on the right side menu 
#### Time : 20 mins
#### Priority : Medium. This would be taken up next, as to check whether Categories are working seamlessly and taking the user to the correct page
#### Test Notes : Categories and Settings was explored mostly as other items were available for PRO version 
### Bug :When We clear data , the interval data is not cleared
### Steps to Reproduce :
1. Add an interval and clear data under Settings option.
2. Verify that interval data is not cleared which should be cleared

### Charter 4 : Verify the Calendar on the left menu option shows the correct data for day,month,year,etc time period
#### Time : 20 mins
#### Priority : High. This is an important feature which needs to display the correct expenses on a yearly, daily basis
#### Test Notes : On adding expense for a day, it was checked for the week, month, year and all inorder to see if data is synced througout

