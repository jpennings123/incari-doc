# Overview

![The On Screen Scene Change Node.](../../../.gitbook/assets/onscreenscenechangenode.png)

The **On Screen Scene Change Node** is an **Event Listener** **Node** used for a **Logic Branch** when the **Scene** of a **Screen** is changed. The returned ID is the final **Scene**. 

# Attributes

![The On Screen Scene Change Node Attributes](../../../.gitbook/assets/onscreenscenechangeattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`OnScreenSceneChange`|**Screen**|The **Screen** whose **Scene** change prompts a **Logic Branch** to fire.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Scene ID`|**Scene**|The ID of the changed **Scene**. |



