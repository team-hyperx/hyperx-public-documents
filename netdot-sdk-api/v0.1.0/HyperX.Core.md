# <a id="HyperX_Core"></a> Class Core

Namespace: [HyperX](HyperX.md)  
Assembly: HyperX.net8.0.dll  

```csharp
public static class Core
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Core](HyperX.Core.md)

#### Inherited Members

[object.Equals\(object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Properties

### <a id="HyperX_Core_PublicStorage"></a> PublicStorage

```csharp
public static PublicStorage PublicStorage { get; }
```

#### Property Value

 [PublicStorage](HyperX.Storage.PublicStorage.md)

## Methods

### <a id="HyperX_Core_GetTime"></a> GetTime\(\)

```csharp
public static Task<DateTimeOffset> GetTime()
```

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[DateTimeOffset](https://learn.microsoft.com/dotnet/api/system.datetimeoffset)\>

### <a id="HyperX_Core_Init_System_String_"></a> Init\(string\)

```csharp
public static Task Init(string projectCode)
```

#### Parameters

`projectCode` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task)

