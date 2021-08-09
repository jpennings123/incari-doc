# Overview

![The Set ArcStart Node.](../../../.gitbook/assets/setarcstart.png)

The **Set ArcStart Node** sets the starting *arc degree* of an **Object**, most likely a **Vector Arc** already created in the **Scene Outliner Module**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the target **Object**.|
|`ArcStart`|**Float**|The starting *arc degree*.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Set ArcEnd**](setarcend.md)
