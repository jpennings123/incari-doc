# Overview

![The Create Object Node.](../../.gitbook/assets/node-create-object.png)

The **Create Object** **Node** creates [**Scene Objects**](../../getting-started/scene-objects/README.md) of a chosen **Object Type**.

In the **Attributes** it can be chosen the **Object Type** to create and the output is the **ObjectID** of the newly created **Object** and a **Bool** value indicating whether the creation of the **Object** was successful or not.

# Attributes

## Object Type

|Attribute|Type|Description|
|---|---|---|
| `Object Type` | **Drop-down** | The **Object Type** of the newly created **Object**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Parent ID` | **ObjectID** | **ObjectID** of a **Group** that the newly created **Object** will be part of. |
| `is 2D` | **Bool** | Whether the newly created **Object** will be *2D* or *3D*. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Object ID` | **ObjectID** | The unique generated **ObjectID** of the newly created **Object**. |
| `Success` | **Bool** | Whether the operation of creating the desired **Object** was successful or not. |

# See Also

* [**Scene Objects**](../../getting-started/scene-objects/README.md)


