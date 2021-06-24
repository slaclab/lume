# LUME

- LUME is a project to extend and generalize the [SimEx](https://github.com/eucall-software/simex_platform) platform for FEL community use.

- Wrap standard, developed electron/photon simulation codes with a common interface (pure Python) with minimal installation complexity, ultimately platform-independent (laptop to  HPC)

- Use the newly developed openPMD standard for data exchange (HDF5 files).

- Create standards for machine and beamline components database descriptions. 

- Well documented for use by developers, Ph.D. students, users (simulation as a service).

- Supporting technologies: Machine database, Simulation Catalogue, Visualization and (G)UI,Optimization hooks, PSANA integration


[IPAC21 paper](https://www.slac.stanford.edu/~cmayes/IPAC21/IPAC21-THPAB217-LUME.pdf)

[IPAC21 slides](https://www.slac.stanford.edu/~cmayes/IPAC21/IPAC21-THPAB217-LUME-slides.pdf)





## Particle and Wavefront exchange standards

- [openPMD](https://github.com/openPMD/openPMD-standard)

- [openPMD-beamphysics extension](https://github.com/openPMD/openPMD-standard/blob/upcoming-2.0.0/EXT_BeamPhysics.md)

- [openPMD-wavefront extension](https://github.com/openPMD/openPMD-standard/blob/upcoming-2.0.0/EXT_Wavefront.md)

## Particle and Wavefront packages

- [openPMD-beamphysics Python package](https://github.com/ChristopherMayes/openPMD-beamphysics)

- [openPMD-wavefront Python package](https://github.com/LUME-SIMEX/openPMD-wavefront)

## Particle Creation

- [distgen](https://github.com/ColwynGulliford/distgen)


## Injector codes

- [LUME-Astra](https://github.com/ChristopherMayes/lume-astra)

- [LUME-GPT](https://github.com/ColwynGulliford/lume-gpt)

- [LUME-Impact](https://github.com/ChristopherMayes/lume-impact)

## Accelerator codes

- [PyTao](https://github.com/bmad-sim/pytao) based on [Bmad](https://www.classe.cornell.edu/bmad/)

## FEL codes

- [LUME-Genesis](https://github.com/slaclab/lume-genesis)

- [ZFEL](https://github.com/slaclab/zfel)

## X-ray codes

- [SRW](https://github.com/ochubar/SRW)


## EPICS

- [LUME-EPICS](https://github.com/slaclab/lume-epics)

## Surrogate Models
- [LUME-Model](https://github.com/slaclab/lume-model)


## Optimization

- [Xopt](https://github.com/ChristopherMayes/Xopt)


## How to cite LUME

Please use the following for publications:

```bibtex
@inproceedings{LUME,
	author         = "C. E. Mayes, P. H. Fuoss, J. R. Garrahan, H. Slepicka, A. Halavanau, 
	J. Krzywinski, A. L. Edelen, F. Ji, W. Lou, N. R. Neveu, A. Huebl, R. Lehe, L. Gupta,
	C. M. Gulliford, D. C. Sagan, J. C. E, C. Fortmann-Grote",
	title          = "{Lightsource unified modelinig environment (LUME), a start-to-end simulation ecosystem",
	booktitle      = "{Proc. of IPAC}",
	year           = "2021",
	pages 		="THPAB217"
}
```

