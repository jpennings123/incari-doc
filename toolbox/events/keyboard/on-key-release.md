# On Key Release

## Overview

![The On Key Release Node.](../../../.gitbook/assets/node-on-key-release.png)

**On Key Release** is an **Event Listener** **Node** used for executing additional **Logic** when a key is released on a computer keyboard.

## Attributes

### Event

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Key` | **Drop-down** | The key that Incari will _listen_ to. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | Moves onto the next part of the **Logic** once the assigned key is released. |
| `Is Alt` | **Bool** | Whether or not the **Alt** key was also pressed when the assigned key was released. |
| `Is Ctrl` | **Bool** | Whether or not the **Ctrl** key was also pressed when the assigned key was released. |
| `Is Shift` | **Bool** | Whether or not the **Shift** key was also pressed when the assigned key was released. |

## See Also

* [**Events**](../README.md)
* [**Keyboard**](README.md)
* [**On Key Press**](on-key-press.md)
