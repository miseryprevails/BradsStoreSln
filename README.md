# BradsStoreSln

Build of a Demo MVC app from ASP.NET Core 3 textbook.

## Link
https://www.apress.com/gp/book/9781484254394.

### Build Script
dotnet new globaljson --sdk-version 5.0.103 --output BradsStoreSln/OutdoorProducts
dotnet new web --no-https --output BradsStoreSln/OutdoorProducts --framework net5.0
dotnet new sln -o BradsStoreSln
dotnet sln BradsStoreSln add BradsStoreSln/OutdoorProducts 
dotnet new xunit -o BradsStoreSln/OutdoorProducts.Tests --framework net5.0
dotnet sln BradsStoreSln add BradsStoreSln/OutdoorProducts.Tests 
dotnet add BradsStoreSln/OutdoorProducts.Tests reference BradsStoreSln/OutdoorProducts 

### Chapter 7 Screenshots

### Step 1 Checking and Running Application
![Welcome Pic](https://github.com/miseryprevails/BradsStoreSln/blob/main/WelcomeToTheStore.PNG)


### Step 2 Bootstrap Applied
![Bootstrap Pic](https://github.com/miseryprevails/BradsStoreSln/blob/main/Bootstrap.PNG)

## Chapter 8 Screenshots

### Step 3 Add,Filter,Category
![Step3Pic](https://github.com/miseryprevails/BradsStoreSln/blob/main/Lab2-A%20Screenshot1.PNG)

### Step 4 Add To Cart Applied
![Cart](https://github.com/miseryprevails/BradsStoreSln/blob/main/Lab2-AScreenshot2.PNG)
![Cart2](https://github.com/miseryprevails/BradsStoreSln/blob/main/Lab2-AScreenshot3.PNG)

### Passed All Tests
![Test](https://github.com/miseryprevails/BradsStoreSln/blob/main/Lab2-A%20Passed%20Test.PNG)
