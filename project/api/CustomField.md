[comment]: # (Name:CustomField)
[comment]: # (Name:Microsoft.ProjectServer.CustomField)
[comment]: # (Type:class)
[comment]: # (Status:Verified)

# <a name="name"></a>CustomField class

inherits members from [ClientObject](https://msdn.microsoft.com/en-us/library/microsoft.sharepoint.client.clientobject.aspx)<br/>

<a name="description"></a>Contains the properties and methods that are used to create an enterprise custom field.

## <a name="syntax"></a>Syntax

### CSOM

```cs
class CustomField 
```
### JSOM

```javascript
PS.CustomField
```
### REST Interface

Supported.

```
PS.CustomField

http://contoso.sharepoint.com/sites/pwa/api/ProjectServer/CustomFields('{fieldid}')
```

## <a name="members"></a>Members


&#x2713; - Read Support &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&#x2713;&#x02B7; - Write Support

### <a name="properties"></a>Properties
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|<a name="AppAlternateId"></a>AppAlternateId|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the alternate custom field GUID that is specified in an App package for Project Online.|
|<a name="Description"></a>Description|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the description of the custom field.|
|<a name="EntityType"></a>EntityType|&#x2713;|&#x2713;|&#x2713;|[EntityType](EntityType.md)|Gets the type of entity (project, task, or resource) for the custom field.|
|<a name="EntityTypeId"></a>EntityTypeId|||&#x2713;|Guid|Gets the type of entity type id(project, task, or resource) for the custom field.|
|<a name="FieldType"></a>FieldType|&#x2713;|&#x2713;|&#x2713;|[CustomFieldType](CustomFieldType.md)|Gets the type of the custom field.|
|<a name="Formula"></a>Formula|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the formula that calculates the value of a custom field.|
|<a name="Id"></a>Id|&#x2713;|&#x2713;|&#x2713;|Guid|Gets the GUID of the custom field.|
|<a name="InternalName"></a>InternalName|&#x2713;|&#x2713;|&#x2713;|String|Gets the internal name of the custom field. Reserved for internal use.|
|<a name="IsEditableInVisibility"></a>IsEditableInVisibility|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the value is editable in project site visibility mode.|
|<a name="IsMultilineText"></a>IsMultilineText|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a text custom field can contain multiple lines.|
|<a name="IsRequired"></a>IsRequired|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a value for the custom field is required when the entity (project, resource, or task) is created.|
|<a name="IsWorkflowControlled"></a>IsWorkflowControlled|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether the custom field value is controlled by a workflow.|
|<a name="LookupAllowMultiSelect"></a>LookupAllowMultiSelect|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets a value that indicates whether multiple lookup table values can be set for the custom field.|
|<a name="LookupDefaultValue"></a>LookupDefaultValue|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Guid|Gets or sets the GUID of the default value in a lookup table for a custom field.|
|<a name="LookupEntries"></a>LookupEntries|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[LookupEntryCollection](LookupEntryCollection.md)|Gets a collection of valid lookup table entries for this field.|
|<a name="LookupTable"></a>LookupTable|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[LookupTable](LookupTable.md)|Gets or sets the LookupTable object for a text custom field.|
|<a name="LookupTableId"></a>LookupTableId|||&#x2713;|Guid|Gets or sets the LookupTable Id for a text custom field.|
|<a name="Name"></a>Name|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|String|Gets or sets the name of the custom field.|
|<a name="RollsDownToAssignments"></a>RollsDownToAssignments|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|Boolean|Gets or sets a value that indicates whether a custom field is set to automatically become a part of the list of available fields for the Assignment cube dimension.|
|<a name="RollupType"></a>RollupType|&#x2713;&#x02B7;|&#x2713;&#x02B7;|&#x2713;&#x02B7;|[CustomFieldRollupType](CustomFieldRollupType.md)|Gets or sets the way that the custom field rolls up to summary tasks.|

### <a name="methods"></a>Methods
> [!div class="mx-tdBreakAll"]
|**Name**|**.NET**|**JSOM**|**REST**|**Return Type**|**Description**|
|:-----|:-----:|:-----:|:-----:|:-----|:-----|
|[DeleteObject()](#DeleteObject__)|&#x2713;|&#x2713;|&#x2713;|void|Deletes the custom field object.|

<br/>
#### Method Details

#### <a name="DeleteObject__"></a>DeleteObject()

Deletes the custom field object.

##### Syntax

```
void DeleteObject()
```

##### Parameters

None

##### Return Value

void

## <a name="seeAlso"></a>See Also

[CustomFieldCollection](CustomFieldCollection.md)<br/>
[CustomFieldCreationInformation](CustomFieldCreationInformation.md)<br/>
