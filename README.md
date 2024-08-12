# Header

[![Build and Deploy Coverage Report](https://github.com/Codemia-IT-Course/dotnet-unit-test-webinar/actions/workflows/coverage.yml/badge.svg)](https://github.com/Codemia-IT-Course/dotnet-unit-test-webinar/actions/workflows/coverage.yml)

[Coverage Report](https://codemia-it-course.github.io/dotnet-unit-test-webinar)

Run tests with code coverage:

```bash
dotnet test --collect:"XPlat Code Coverage"
```

Generate code coverage report:

```bash
reportgenerator --settings coverlet.runsettings -reports:{{coverage.cobertura.xml file path}} -targetdir:coverage-report -reporttypes:Html
```
