# <a id="HyperX_Http_Storage"></a> Class Storage

Namespace: [HyperX.Http](HyperX.Http.md)  
Assembly: HyperX.net8.0.dll  

```csharp
public static class Storage
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Storage](HyperX.Http.Storage.md)

#### Inherited Members

[object.Equals\(object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Methods

### <a id="HyperX_Http_Storage_GetObjectHash_System_String_System_String_"></a> GetObjectHash\(string, string\)

```csharp
public static Task<string> GetObjectHash(string projectCode, string key)
```

#### Parameters

`projectCode` [string](https://learn.microsoft.com/dotnet/api/system.string)

`key` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="HyperX_Http_Storage_GetObjectMeta_System_String_System_String_"></a> GetObjectMeta\(string, string\)

```csharp
public static Task<Storage.ObjectMeta> GetObjectMeta(string projectCode, string key)
```

#### Parameters

`projectCode` [string](https://learn.microsoft.com/dotnet/api/system.string)

`key` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[Storage](HyperX.Http.Storage.md).[ObjectMeta](HyperX.Http.Storage.ObjectMeta.md)\>

