# Lid-driven cavity flow example in OpenFOAM

[Tutorial Link](https://www.openfoam.com/documentation/tutorial-guide/2-incompressible-flow/2.1-lid-driven-cavity-flow)

<img width="683" height="384" alt="image" src="https://github.com/user-attachments/assets/063aa95c-2e6b-4be9-a569-53fe210b54c1" />

The geometry is shown in Figure in which all the boundaries of the square are walls. The top wall moves in the x direction at a speed of 1 m/s while the other 3 are stationary. Initially, the flow will be assumed laminar and will be solved on a uniform mesh using the icoFoam solver for laminar, isothermal, incompressible flow.

## Results

<img width="1920" height="1080" alt="Screenshot from 2025-12-30 19-33-08" src="https://github.com/user-attachments/assets/dd6c61b4-4890-40db-b2af-e313a8354551" />

<img width="1920" height="1080" alt="Screenshot from 2025-12-30 19-42-18" src="https://github.com/user-attachments/assets/474c4fc8-5516-4b68-a6ed-1d9380bdc61b" />

## Additional Information

* I used OpenFOAM 2412 on Ubuntu 24.04 LTS.
* I had to install _paraview_ separately (used to run _paraFoam_ for Postprocessing)
