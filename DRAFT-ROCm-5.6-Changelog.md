### ROCm 5.6 Release Notes


#### HIP Changelog 

###### Optimizations

- Consolidation of hipamd, rocclr and OpenCL projects in clr
- Optimized lock for graph global capture mode

###### Additions

- hipRTC support for amd_hip_fp16
- hipStreamGetDevice implementation to get the device associated with the stream
- HIP_AD_FORMAT_SIGNED_INT16 in hipArray formats
- hipArrayGetInfo for getting information about the specified array
- hipArrayGetDescriptor for getting 1D or 2D array descriptor
- hipArray3DGetDescriptor to get 3D array descriptor

###### Changes

- hipMallocAsync to return success for zero size allocation to match hipMalloc
- Separation of hipcc perl binaries from HIP project to hipcc project. hip-devel package depends on newly added hipcc package
- Consolidation of hipamd, ROCclr, and OpenCL repositories into a single repository called clr. Instructions are updated to build HIP from sources in the HIP Installation guide
- Removed hipBusBandwidth and hipCommander samples from hip-tests

###### Fixes

- Regression in hipMemCpyParam3D when offset is applied

For HIP documentation, see rocm.docs.amd.com 


### ROCm v5.5.1 release updates

##### `hipStreamGetDevice`	- Limited testing on xnack+ configuration
- Multiple HIP tests failures (gpuvm fault or hangs)
- Get the device associated with the stream.	#

#### Upcoming Changes in a Future Release


    ```h	- Removal of gcnarch from hipDeviceProp_t structure
    hipError_t hipStreamGetDevice(hipStream_t stream, hipDevice_t* device);	- Addition of new fields in hipDeviceProp_t structure
    ```	  - maxTexture1D
  - maxTexture2D
  - maxTexture1DLayered
  - maxTexture2DLayered
  - sharedMemPerMultiprocessor
  - deviceOverlap
  - asyncEngineCount
  - surfaceAlignment
  - unifiedAddressing
  - computePreemptionSupported
  - uuid

- Removal of deprecated code
  - hip-hcc codes from hip code tree
- Correct hipArray usage in HIP APIs such as hipMemcpyAtoH and hipMemcpyHtoA
- HIPMEMCPY_3D fields correction (unsigned int -> size_t)
- Renaming of 'memoryType' in hipPointerAttribute_t structure to 'type'
