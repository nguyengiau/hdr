High Dynamic Range Tone Mapping:
> A Proposal for Google’s Summer of Code 2007

High Dynamic Range (HDR) images exceed the visualization capabilities of display and print media. In order to effectively utilize the display capabilities, we need to compress the HDR image. There are different algorithms available in literature to address the color compression for HDR images. During this proposed Google Summer of Code 2007 project, I plan to write C/C++ code for established HDR tone mapping algorithms. In addition, I plan to improve upon some of the existing algorithms to create pleasing and highly natural representations of HDR image content and work on a concept to include parameters into ICC or CTL color profiles for later universal reproduction and standardization.

There are three main objectives for this project.
  1. Improve upon some of the existing algorithms.
> 2. Work on a concept to include parameters into ICC or CTL color profiles for later universal reproduction and standardization.
> 3. Make the state of the art HDR tone mapping algorithms readily available

The project is designed such that we obtain a whole spectrum of HDR tone mapping source codes for the open source community with a pleasing and easy to use GUI. I plan to avoid the duplication of efforts in cases where the inventors of the algorithms are willing to contribute the code in C/C++ under the licensing terms of our open source community. There will be a super set S of tone mapping algorithm source codes that I plan to obtain for this project. It will be composed of two mutually exclusive and exhaustive subsets, namely, I and C. I refer to the subset where the code is written and tested by myself whereas C refers to the subset where the code is contributed by well known people upon invitation, which will be tested and documented by me. The members of set I shall include at least 3 of the methods described below.
> I. Single-Scale Retinex (SSR)
> II. Multi-Scale Retinex (MSR)
> III. Reinhard’s Operator
> IV. Bilateral Filter
> V. Fast Tone Mapping for High Dynamic Range Images
The remaining methods shall form the subset C. It is expected that the proposed project will make a spectra of state of the art HDR tone mapping algorithms available under the open source scheme.