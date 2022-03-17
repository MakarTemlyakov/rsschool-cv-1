# Makar Temlyakov
## Junior Frontend Developer
### Contact Information
#### Phone: *+375333720488*
#### Email: *makartemlyakov@gmail.com*

### About Myself
 My carrer started with experience working with .Net on Backend side, where I learned and worked with MVC pattern, 
 sometimes I also worked with API and bussines logic on back-end, fixing bags, make refactoring and working with database.
 Project on which I worked was commerce solution, where users can buy or to sell some things.
 I also a litle working with Frontend stack like React,TypeScript, Redux, on this side I often fixed bags, working with features and writtng autotest's.
 When I worked with Frontend side, I have a interst in Frontend stack and I wanna to know more information about it.

### Technologies Stack and Skills
* C#,.Net, MSSQL, Entity Framework, ASP.NET MVC;
* JavaScript,TypeScript;
* React,Redux;
* CSS,HTML;
* VS Code, Visual Studio, Managment SQL Studio;
* Unit Tests/Selenium/Mocha.

 ### CodeExample
 **Code from my test project:**
 ``` C# 
     public async Task<List<PlayersMatchInfo>> GetPlayersMatchInfo()
     {
        var content = await HttpHelper.GetContent(_httpClient, "api/players/25907144/matches?project=heroes");
        var matches = JsonConvert.DeserializeObject<List<MatchPlayersDto>>(content);
        var viewMatches = _mapper.Map<List<PlayersMatchInfo>>(matches);
        return viewMatches;
     }
     JavaScript
     const getUserName = (userId: number) => {  
        return usersInfo
            .filter(x => x.id === userId)
            .map(x =>
            x.gender === "Male"
                ? `Mr.${x.first_name} ${x.last_name}`
                : `Ms.${x.first_name} ${x.last_name}`
            )
        }
      };
     const getUserCompanyInfo = (userId: any) => {
     return companyInfo
         .filter(x => x.id === userId)
         .map((x, id: number) => {
         return (
            <div key={id}>
            <p>
                Company: <a href="http://awesome.website">{x.title}</a>
            </p>
            <p>Industry: {x.industry}</p>
            </div>
         );
         });
     };
```
### Work Experience and Learn information about technologies
 * JavaScript Manual on https://learnjavascript.ru (in progress);
 * .Net course on Metanit (https://metanit.com/sharp/);
 * Frontend on Udemy.com (Udemy.com)(in progress).

### Education
* BSUIR;
* Udemy;
* Cursera.

### English
 Pre-intermediate, Lingualo, Online-courses, London Grammar Practice WorkBook