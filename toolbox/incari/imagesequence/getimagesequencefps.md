# Overview

![The Get ImageSequence FPS Node.](../../../.gitbook/assets/getimagesequencefps.png)

The **Get ImageSequence Duration Node** returns the frame rate of the **ImageSequence**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the target **Object**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`FPS`|**Int**|The frame rate.|


# See Also

* [**Get ImageSequence Duration**](getimagesequenceduration.md)
* [**Get Current ImageSequence Frame**](getcurrentimagesequenceframe.md)
* [**Get Image Sequence Total Frames**](getimagesequencetotalframes.md)