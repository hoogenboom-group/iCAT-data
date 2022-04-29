# iCAT-data

Partial dataset repository for iCAT-workflow.

## Datasets

### `pancreas`
Serial sections of rat pancreas tissue (partial dataset) [[1]](https://doi.org/10.3389/fmolb.2021.822232).

**Stacks**
* AF594 (insulin)
* Hoechst
* Low-magnification EM
* High-magnification EM

**Full dataset visualization**
* [Nanotomy](http://nanotomy.org/OA/Lane2022FiCD/index.html)  
* [CATMAID](https://sonic.tnw.tudelft.nl/catmaid/2/links/a8bntqz)

**Organization**
```
┌ pancreas (project)
├──┬ AF594 (stack)
│  ├──┬ S004 (section --> z)
│  │  └── insulin-00001x00001.tif
│  ├─── S005
│  ├─── S006
│  └─── S007
├─── Hoechst
├─── EM_lomag
└──┬ EM_himag
   ├──┬ S004
   │  ├── lil_EM-00002x00002.tif
   │  ├── lil_EM-00002x00003.tif
   │  │   ...
   │  ├── lil_EM-00006x00005.tif
   │  └── lil_EM-00006x00006.tif
   ├─── S005
   ├─── S006
   └─── S007
```

**References**
1. Lane, Ryan, et al. "Integrated Array Tomography for 3D Correlative Light and Electron Microscopy." _Frontiers in Molecular Biosciences_ **8** (2021).
