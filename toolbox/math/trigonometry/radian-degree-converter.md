# Radian-Degree Converter

## Overview

![The Radian-Degree Converter Node.](../../../.gitbook/assets/node-radian-degree-convertor2.png)

**Radian-Degree Converter** takes a single **Float** value, representing an angle, in degrees \(°\) or radians \(rad\), and converts it from one unit to the other.

The equation used by the **Node** is determined by the `Mode` **Attribute**. The equations are:

* `Radian_to_Degree`: _D_ =  _R_ x 180/π.
* `Degree_to_Radian`: _R_ = _D_ x π/180,

where _R_ is an angle in radians \(rad\) and _D_ is an angle in degrees \(°\).

## Attributes

![The Radian-Degree Converter Node Attributes.](../../../.gitbook/assets/node-radian-degree-convertor2-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Mode` | **Drop-down** | Determines which conversion equation is used. |
| `Default Value` | **Float** | The default value of `Input`, if no value is provided in the `Input` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard input **Pulse**, to trigger the execution of the **Node**. |
| `Input` | **Float** | The angle to convert. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard output **Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | **Float** | The converted value. |

## See Also

* [**Trigonometry**](./)

## External Links

* [_Trigonometry_](https://www.khanacademy.org/math/trigonometry) on Khan Academy.
* [_Radians_](https://www.mathsisfun.com/geometry/radians.html) on Maths is Fun.
* [_Degrees_](https://www.mathsisfun.com/geometry/degrees.html) on Maths is Fun. 

