# Obsidian Notes

Publish your public notes with MkDocs

## Hello World!

The `index.md` in the `/docs` folder is the homepage you see here.

The folders in `/docs` appear as the main sections on the navigation bar.

The notes appear as pages within these sections. For example, [[Note 1]] in `Topic 1`

Test

```csharp
using System;
using System.Text.RegularExpressions;

class Program
{
    static void Main()
    {
        string input = "ABC XYZ123 DEF456789 LMN";

        string pattern = @"\b[A-Za-z]{3}\d*\b";
        Regex regex = new Regex(pattern);

        MatchCollection matches = regex.Matches(input);

        foreach (Match match in matches)
        {
            Console.WriteLine(match.Value);
        }
    }
}
```

DO Code blocks work?
```tasks
done last week
```

Testing tasks