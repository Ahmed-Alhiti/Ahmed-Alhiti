![header](profile.png)

### ✨ About Me
```csharp
public class AhmedFawaz
{
    public string Name => "Ahmed Al-Hiti";
    
    public ProfileInfo Profile => new ProfileInfo
    {
        Occupation = "Software Developer",
        Education = "Bachelor's Degree in Information Technology",
        CurrentlyLearning = "SOLID Principles & Advanced ASP.NET Core"
    };

    public string[] Skills => new[]
    {
        "C#", "Python", "C++", "Kotlin", "PHP",
        ".NET Framework", "ASP.NET Core", "WinForms",
        "ADO.NET", "SQL Server", "T-SQL",
        "RESTful API", "Git/GitHub", "3-Tier Architecture",
        "AI Automation", "Object-Oriented Programming", "System Design"
    };
}

public class ProfileInfo
{
    public string Occupation { get; set; }
    public string Education { get; set; }
    public string CurrentlyLearning { get; set; }
}
