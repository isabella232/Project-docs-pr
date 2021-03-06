[comment]: # (Name:LookupTableCollection)
[comment]: # (Name:Microsoft.ProjectServer.LookupTableCollection)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>LookupTableCollection class

inherits members from [ClientObjectCollection<LookupTable>](https://msdn.microsoft.com/EN-US/library/ee539303)<br/>

<a name="description"></a>Represents a collection of [LookupTable](LookupTable.md) objects.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class LookupTableCollection 
```
### JSOM

```javascript
PS.LookupTableCollection
```
### REST Interface

Supported.

```
PS.LookupTableCollection

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/LookupTables
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="[Integer]"></a>[Integer]|&#x2713;|||[LookupTable](LookupTable.md)|Gets a [LookupTable](LookupTable.md) from the collection at the specified index.|
|<a name="Item"></a>Item||&#x2713;||[LookupTable](LookupTable.md)|Gets a [LookupTable](LookupTable.md) from the collection at the specified index.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[&#39;{LookupTableId}&#39;](#&#39;{LookupTableId}&#39;)|||&#x2713;|[LookupTable](LookupTable.md)|Gets a [LookupTable](LookupTable.md) from the collection with the specified LookupTableId.|
|[Add(LookupTableCreationInformation parameters)](#Add_[LookupTableCreationInformation]_LookupTableCreationInformation.md__parameters_)|&#x2713;|&#x2713;|&#x2713;|[LookupTable](LookupTable.md)|Adds the [LookupTable](LookupTable.md) that is specified by the [LookupTableCreationInformation](LookupTableCreationInformation.md) object to the collection.|
|[GetByAppAlternateId(String objectId)](#GetByAppAlternateId_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[LookupTable](LookupTable.md)|Get an element from the lookup table collection by using the alternate object GUID that is specified in an App package for Project Online.|
|[GetByGuid(Guid uid)](#GetByGuid_Guid_uid_)|&#x2713;|&#x2713;|&#x2713;|[LookupTable](LookupTable.md)|Gets a [LookupTable](LookupTable.md) from the collection with the Guid value.|
|[GetById(String objectId)](#GetById_String_objectId_)|&#x2713;|&#x2713;|&#x2713;|[LookupTable](LookupTable.md)|Gets a [LookupTable](LookupTable.md) from the collection with the Id value.|
|[Remove(LookupTable table)](#Remove_[LookupTable]_LookupTable.md__table_)|&#x2713;|&#x2713;||Boolean|Removes the specified [LookupTable](LookupTable.md) from the collection.|
|[Update()](#Update__)|&#x2713;|&#x2713;||void|Updates the lookup table collection.|

<br/>
#### Method Details

#### <a name="&#39;{LookupTableId}&#39;"></a>&#39;{LookupTableId}&#39;
 
Gets a [LookupTable](LookupTable.md) from the collection with the specified LookupTableId.

##### Syntax

```
LookupTable http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/LookupTables('{LookupTableId}')
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|LookupTableId|String|the id of the LookupTable|

##### Return Value

[LookupTable](LookupTable.md)

#### <a name="Add_[LookupTableCreationInformation]_LookupTableCreationInformation.md__parameters_"></a>Add([LookupTableCreationInformation](LookupTableCreationInformation.md) parameters)
 
Adds the [LookupTable](LookupTable.md) that is specified by the [LookupTableCreationInformation](LookupTableCreationInformation.md) object to the collection.

##### Syntax

```
LookupTable Add(LookupTableCreationInformation parameters)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|parameters|[LookupTableCreationInformation](LookupTableCreationInformation.md)|The properties that can be set when creating a lookup table.|

##### Return Value

[LookupTable](LookupTable.md)

#### <a name="GetByAppAlternateId_String_objectId_"></a>GetByAppAlternateId(String objectId)
 
Get an element from the lookup table collection by using the alternate object GUID that is specified in an App package for Project Online.

##### Syntax

```
LookupTable GetByAppAlternateId(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The alternate custom field GUID.|

##### Return Value

[LookupTable](LookupTable.md)

#### <a name="GetByGuid_Guid_uid_"></a>GetByGuid(Guid uid)
 
Gets a [LookupTable](LookupTable.md) from the collection with the Guid value.

##### Syntax

```
LookupTable GetByGuid(Guid uid)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|uid|Guid|The Guid of the [LookupTable](LookupTable.md)|

##### Return Value

[LookupTable](LookupTable.md)

#### <a name="GetById_String_objectId_"></a>GetById(String objectId)
 
Gets a [LookupTable](LookupTable.md) from the collection with the Id value.

##### Syntax

```
LookupTable GetById(String objectId)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|objectId|String|The id of the [LookupTable](LookupTable.md).|

##### Return Value

[LookupTable](LookupTable.md)

#### <a name="Remove_[LookupTable]_LookupTable.md__table_"></a>Remove([LookupTable](LookupTable.md) table)
 
Removes the specified [LookupTable](LookupTable.md) from the collection.

##### Syntax

```
Boolean Remove(LookupTable table)
```

##### Parameters
> [!div class="mx-tdBreakAll"]
|**Name** |**Type**|**Description**|
|:------ |:----|:------ |
|table|[LookupTable](LookupTable.md)|The [LookupTable](LookupTable.md) to remove.|

##### Return Value

Boolean

#### <a name="Update__"></a>Update()
 
Updates the lookup table collection.

##### Syntax

```
void Update()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[LookupTable](LookupTable.md)<br/>
[LookupTableCreationInformation](LookupTableCreationInformation.md)<br/>
[ProjectContext](ProjectContext.md)<br/>
