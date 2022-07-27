# CsharpLibTemplate

## What's this ?

C# library project file template for Rider IDE.

The C# default project template is very good at enabling nullable settings.

However, I'd like to treat it as an error rather than a warning anyway.

This template outputs `.csproj` file includes the following properties.

```xml
    <PropertyGroup>
        <WarningsAsErrors>Nullable</WarningsAsErrors>
        <Nullable>enable</Nullable>
    </PropertyGroup>
```

## References

- [Rider / Install custom project templates](https://www.jetbrains.com/help/rider/Creating_and_Opening_Projects_and_Solutions.html#managing-project-templates)
- [Stack Overflow / How to treat ALL C# 8 nullable reference warnings as errors?](https://stackoverflow.com/questions/58194983/how-to-treat-all-c-sharp-8-nullable-reference-warnings-as-errors)
