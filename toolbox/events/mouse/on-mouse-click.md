# Overview

![The On Mouse Click Node.](../../../.gitbook/assets/node-on-mouse-click.png)

**On Mouse Click** is an **Event Listener** **Node** used for executing a **Logic Branch** when an **Object** is clicked.

# Attributes

## Object

|Attribute|Type|Description|
|---|---|---|
| `Object` | **ObjectID** | The **Object** in which a click triggers the **Logic Branch**.|

## Button

|Attribute|Type|Description|
|---|---|---|
| `Mouse Button` | **Drop-down** | Whether the left, middle or right button of the mouse will trigger the **Logic**. |


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `IsLongClick` | **Bool** | _True_ when the button is pressed longer than usual. |
# See Also

* [**Events**](../README.md)
* [**Mouse**](README.md)
