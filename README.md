# Coding Guidelines

### Naming
| Id  | Description | Bad Practice | Good Practice | More Info |
| --- | --- | --- | --- | --- |
| nm_001  | Use camel case for variables name | ``` var person_age = 18; ``` | ``` var personAge = 18; ``` | [more](https://docs.microsoft.com/en-us/previous-versions/dotnet/netframework-1.1/x2dbyw72%28v%3dvs.71%29)
| nm_002  | Private fields names should start with "_" | ``` private readonly personAge; ``` | ``` private readonly _personAge; ``` | More explanation here |

### async/await
| Id  | Description | Bad Practice | Good Practice | More Info |
| --- | --- | --- | --- | --- |
| aw_001  |  Use "Async" suffix for all async methods | ``` public async Task PostMessage(string message)```<br>```{```<br>```... await something```<br>```}``` | ``` public async Task PostMessageAsync(string message)```<br>```{```<br>```... await something```<br>```}``` | [link to wiki]() |
