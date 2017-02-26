## ![](../../images/icons/Solution_Parameter.png) Solution Parameter

![](../../images/components/Solution_Parameter.png)

Solution Parameter.

#### Inputs
* ##### filename [Required]
OpenFOAM filename that the values are belong to (e.g.
* ##### values [Required]
new values as a valid OpenFOAM (c++) dictionary.
* ##### tRange [Optional]
Script variable solutionParam
* ##### replace [Optional]
Set to True if you want the original dictionary to be replaced

#### Outputs
* ##### solutionParam
A solution parameter.


[Check Hydra Example Files for Solution Parameter](https://hydrashare.github.io/hydra/index.html?keywords=Butterfly_Solution Parameter)