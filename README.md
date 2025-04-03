
## Setup MSTest
Everyone needs to run the following in their CLI. This installs the MSTest packages (predefined code) that allows us to create unit tests. 
```
dotnet add package MSTest.TestFramework
dotnet add package MSTest.TestAdapter
```

One developer runs the following commands and pushes the results up to GitHub for others to pull down. 
```
dotnet new test
```