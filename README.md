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
    };

    public string[] Skills => new[]
    {
        "C#", "C++", "Kotlin",
        ".NET Framework","WinForms",
        "ADO.NET", "SQL Server", "T-SQL","SQLite",
        "RESTful API", "Win32APIs","GitHub", "3-Tier Architecture",
        "Object-Oriented Programming","Functional Programming" ,"System Design"
    };
}

public class ProfileInfo
{
    public string Occupation { get; set; }
    public string Education { get; set; }
}
