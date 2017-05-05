[comment]: # (Name:EntityTypes)
[comment]: # (Name:Microsoft.ProjectServer.EntityTypes)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>EntityTypes class

<a name="description"></a>Represents the types of Project Server entities that are exposed through CSOM.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class EntityTypes 
```
### JSOM

```javascript
PS.EntityTypes
```
### REST Interface

This resource supports GET, POST, PUT, PATCH, and MERGE HTTP commands.

```
PS.EntityTypes

http://contoso.sharepoint.com/sites/pwa/_api/ProjectServer/EntityTypes
```

## <a name="members"></a>Members

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="AssignmentEntity"></a>AssignmentEntity|&#x2713;|&#x2713;|&#x2713;|[EntityType](EntityType.md)|Gets an assignment entity type.|
|<a name="ProjectEntity"></a>ProjectEntity|&#x2713;|&#x2713;|&#x2713;|[EntityType](EntityType.md)|Gets a project entity type.|
|<a name="ResourceEntity"></a>ResourceEntity|&#x2713;|&#x2713;|&#x2713;|[EntityType](EntityType.md)|Gets a resource entity type.|
|<a name="TaskEntity"></a>TaskEntity|&#x2713;|&#x2713;|&#x2713;|[EntityType](EntityType.md)|Gets a task entity type.|

## <a name="seeAlso"></a>See Also

[ProjectContext](ProjectContext.md)<br/>