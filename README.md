# <p><img src="iconMt.png" width="64px" height="64px" align="middle"/> <img src="iconFV.png" width="64px" height="64px" align="middle"/>  Mt FluentValidation</p>

Набор базовых шаблонов валидации на основе пакета ```FluentValidation``` для проектов Mt Rele.

## Перечень технологий (зависимости):

netstandard2.1, [Mt.Utilities](https://github.com/g-aa/mt-utilities), FluentValidation, SonarAnalyzer.CSharp, NUnit.

## [История изменения.](CHANGELOG.md)

## Покрытие кода тестами:

Перед первым запуском ```.test.bat```, для просмотра покрытия кода тестами проверьте наличие ```dotnet-reportgenerator-globaltool``` выполнив команду:

```dotnet tool list --global```

в перечне пакетов должен присутствовать необходимый пакет:

```
Идентификатор пакета                   Версия      Команды
------------------------------------------------------------------
dotnet-reportgenerator-globaltool      5.1.19      reportgenerator
```

при его отсутствии необходимо выполнить команду:

```dotnet tool install -g dotnet-reportgenerator-globaltool```

## Основной функционал пакета:

| Компонент                                | Описание                                       |
|------------------------------------------|------------------------------------------------|
| Mt.FluentValidation.ValidationExtensions | Методы расширения для пакета FluentValidation. |