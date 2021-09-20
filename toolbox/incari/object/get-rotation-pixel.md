# Overview

![The Get Rotation 2D Node.](../../../.gitbook/assets/getrotationpixel.png)

The **Get Rotation 2D Node** returns the *degree of rotation* of a **2D Object**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`| **ObjectID** | The target **Object** whose `Rotation` you wish to return, if one is not provided in the `Object ID` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | The ID of the target **Object** whose `Rotation` you wish to return. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Rotation` | **Float** | The *degree of rotation* of the target **Object**. |

# See Also

* [**Get Position Pixel**](get-position-pixel.md)
* [**Get Size Pixel**](get-size-pixel.md)
