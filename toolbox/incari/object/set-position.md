# Set Position

## Overview

![The Set Position Node.](../../../.gitbook/assets/node-set-position.png)

**Set Position** sets the value of a given **Object**'s `Position` **Attribute**.

## Attributes

![The Set Position Node Attributes.](../../../.gitbook/assets/node-set-position-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**, whose `Position` you wish to set, if one is not provided in the `Object ID` **Socket**. |
| `Position` | **Vector3** | The desired `Position` value of the **Object**, if one is not provided in the `Position` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object** whose `Position` you wish to set. |
| `Position` | **Vector3** | A 3-dimensional **Vector** that contains X, Y, and Z _positions_ of the target **Object**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Get Rotation**](get-rotation.md)
* [**Get Scale**](get-scale.md)
* [**Get Position**](get-position.md)

## External Links

* [_Position \(geometry\)_](https://en.wikipedia.org/wiki/Position_%28geometry%29) on Wikipedia.

