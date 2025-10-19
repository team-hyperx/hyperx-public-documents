# <a id="HyperX_Storage_PublicStorage"></a> Class PublicStorage

Namespace: [HyperX.Storage](HyperX.Storage.md)  
Assembly: HyperX.net8.0.dll  

```csharp
public class PublicStorage
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[PublicStorage](HyperX.Storage.PublicStorage.md)

#### Inherited Members

[object.Equals\(object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone), 
[object.ReferenceEquals\(object?, object?\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring)

## Constructors

### <a id="HyperX_Storage_PublicStorage__ctor_HyperX_Project_"></a> PublicStorage\(Project\)

```csharp
public PublicStorage(Project project)
```

#### Parameters

`project` [Project](HyperX.Project.md)

## Methods

### <a id="HyperX_Storage_PublicStorage_Get_System_String_"></a> Get\(string\)

```csharp
public FileDownloadProgress Get(string filename)
```

#### Parameters

`filename` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [FileDownloadProgress](HyperX.Http.FileDownloadProgress.md)

### <a id="HyperX_Storage_PublicStorage_Get_System_String_System_String_"></a> Get\(string, string\)

```csharp
public FileDownloadProgress Get(string filename, string downloadPath)
```

#### Parameters

`filename` [string](https://learn.microsoft.com/dotnet/api/system.string)

`downloadPath` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [FileDownloadProgress](HyperX.Http.FileDownloadProgress.md)

### <a id="HyperX_Storage_PublicStorage_GetHash_System_String_"></a> GetHash\(string\)

```csharp
public Task<string> GetHash(string filename)
```

#### Parameters

`filename` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[string](https://learn.microsoft.com/dotnet/api/system.string)\>

### <a id="HyperX_Storage_PublicStorage_GetMeta_System_String_"></a> GetMeta\(string\)

```csharp
public Task<Storage.ObjectMeta> GetMeta(string filename)
```

#### Parameters

`filename` [string](https://learn.microsoft.com/dotnet/api/system.string)

#### Returns

 [Task](https://learn.microsoft.com/dotnet/api/system.threading.tasks.task\-1)<[Storage](HyperX.Http.Storage.md).[ObjectMeta](HyperX.Http.Storage.ObjectMeta.md)\>

