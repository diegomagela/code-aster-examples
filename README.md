# code-aster-examples
A number of examples for the open-source Finite Element Solver [Code_Aster](https://www.code-aster.org/) and [Salome_Meca](https://www.code-aster.org/spip.php?article303)

## Examples

Each folder contains a `.med` file with the mesh of the structure and a `.comm` file with the command file for Code_Aster. With these files anyone shoulf be able to reproduce the analyses with or without Salome_Meca. See the [IFC2CA video](https://youtu.be/V9Pc7SJvuRg) if you want to see how to reproduce the analyses with asterStudy, a dedicated module of Salome_Meca.

[Tutorials 01-03](Tutorials_01-03): Static analysis of a cantilever beam with 3D solid elements and post-processing of results
- [Video - Tutorial 01](https://youtu.be/lFUF5EelFUo)
- [Video - Tutorial 02](https://youtu.be/BizOXE3T9m8)
- [Video - Tutorial 03](https://youtu.be/07UxN1EaUvI)


[Tutorials 04-06](Tutorials_01-03): Steady-state thermo-mechanical analysis of a cantilever beam with 3D solid elements
- [Video - Tutorial 04](https://youtu.be/Rs_DuxT5dgw)
- [Video - Tutorial 05](https://youtu.be/D7V7Qn-40DU)
- [Video - Tutorial 06](https://youtu.be/eXNyT-aPh6Y)

[Tutorial 07](Tutorial_07): Static analysis of a cantilever beam with beam elements and post-processing of results
- [Video](https://youtu.be/Cx6mGyJH1Ms)

[Define Local Axes for 1D Elements](DefineLocalAxes1D): Define the orientation of the local axes of 1D elements in Code_Aster and extract this information in the result file, then visualize the local axes in Paraview
- [Video](https://youtu.be/FUiFjAtCyX0)

[Define Custom Beam Profile](CustomBeamProfile): Define a custom profile for beam elements given that these properties are calculated beforehand or extracted from a table. Extract not only the generalized forces but also the maximum stresses for each type of response
- [Video](https://youtu.be/uZBcvgoby54)

[Composite Shells](CompositeShellExample): Define a composite shell with an arbitrary number of layers, orhtotropic materials and arbitrary material directions and extract generalized forces and stress for a specific layer. BONUS: Example is performed with a Cross Laminated Timber (CLT) panel
- [Video](https://youtu.be/52INSrQ48iQ)

[Tensegrity Structure Example](TensegrityExample): Nonlinear dynamic analysis of a tensegrity structure with Code_Aster
- [Simulation Video](https://youtu.be/PegRyW-5HXY)

[IFC2CA Portal Example](IFC2CA_PortalExample): Download the IFC2CA example files and load them in Salome_Meca. Here you can find the files for the portal_01 example

_Note: The repository referenced in the video has been moved in the [IfcOpenShell/analysis-models](https://github.com/IfcOpenShell/analysis-models) repository. Due to major modifications in the project the Code_Aster files are not uploaded yet_
- [Video](https://youtu.be/V9Pc7SJvuRg)

## License
All content is licensed under an open-source, 'copyleft' license:
[Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)
![Attribution-ShareAlike 4.0 International](http://i.creativecommons.org/l/by-sa/3.0/88x31.png)
