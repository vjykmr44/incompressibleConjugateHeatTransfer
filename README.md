# incompressibleConjugateHeatTransfer

1. Development of an incompressible conjugate heat transfer in OpenFOAM 6 (Foundation version).

2. Base solver - "chtMultiRegionFoam"
        Fluid part - replaced with the equations from "buoyantBossinesqPimpleFoam'
        Solid part - heat diffusion equation

3. Modified BC for the interface of solid-fluid region for based on temperatureCoupledBC
