# On Video Finish

## Overview
![The On Video Finish Node.](../../../.gitbook/assets/onvideofinish.png)


**On Video Finish** is an **Event Listener Node** that gives the user a way to perform an action once a video ends, such as repeating the video when it has finished. The video can be added through the file library to the right.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**. |

## Inputs
| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |