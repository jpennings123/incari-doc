# Overview

![The Serial Send Packet Node.](../../../.gitbook/assets/seriasendpacketnode.png)

The **Serial Send Packet Node** is used to send a data **Packet** after selecting a **Serial Communication** connection from the **Drop-down Menu**.

# Attributes

![The Serial Send Packet Node Attributes.](../../../.gitbook/assets/serialsendpacketattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Is Binary`|**Bool**|Can be toggled on or off depending on if the `Message` body is binary or not.|
|`Configuration`|**Drop-down**|The desired **Serial** connection.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Message`|**String**|The **Packet's** `Message`.|


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also
* [**Serial Start**](serialstart.md)
* [**Serial Stop**](serialstop.md)
  
