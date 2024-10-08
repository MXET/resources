# Open Research Collab

Authored by David Malawey for posting projects for collaboration & sharing ideas.  

## Collaboration intention
Instead of generating one result at a time, and publishing one academic article, open and incremental publication allows for real-time peer review & unlimited perturbations & results.  The research topics posted here are intrinsically suited to worldwide collaboration because the resources required to execute the research are fully within the digital space.  Ie, research of a rocket engine requires engineers to have a copy of the rocket engine, but the torque-testing research project will require only common materials, common design softwares, and shared documents consisting of 3D models, online data, common engineering standards, & digitally described methods.

## Torque testing project

<br /> <img src="https://i.imgur.com/Bd2hNES.jpeg" width="400" /> <br />
This project was initiated to develop a novel torque testing method including an aparatus, formulas, & use cases.

### Background:
3D printed parts are frequently evaluated for mechanical properties.  The most common tests, such as dog-bone tension testing (ASTM D638), were designed for traditionally manufactured parts.  We can better accomodate our designers' needs by considering real-world 3d printing design problems.  Designers face:
* I am bonding an FDM part to a rigid structure.  Is my bond strong enough?
* I am mating two FDM parts.  What geometry is best for the mating interface?
* My FDM part can be stronger, but there are too many variables to test.  Should we add adhesive area, flanges & fasteners, ribs, etc?
* Round parts enhancement:
  * Can I enhance my slip-ring with the new capabilities of 3D geometry?
  * Can I enhance a fluid-carrying interface?
  * Can I enhance a rotating coupling?

The project purpose is for solving new problems (fixed criteria) and exploration (flexible & open) in bonding materials, printing materials, and mating components in assemblies

### Problems:
*To solve the following problems:*
1) specifically test shear, torque-induced shear, and common true failure modes for additive materials.
2) design a test that can rapidly inform on comparative results, ie: is the bonded joint stronger than the material?
3) design a test which accomodates variations in parts which reflect real-world variations.
5) develop a test which leverages common tools.
6) examine shear failure for anisotropic parts and assemblies.
7) standardize a test geometry which is easily repeated.
8) make test such that samples do not require fine tolerance for fairly accurate results.
9) reduce the number of sample parts to collect a range of data.

### Exploration:
*To support exploration of the following*
1) what insights can we discover in 3D printing parameters such as infill patterns with a test that loads the part in multiple directions?
2) How closely does the shear surface map to the theoretical shear locations?
3) Can we modify the interface such that we can assume a constant shear value at all surface locations (thin-tube-assumption)?
4) Can we use test results to feedback into geometry optimization for interconnected parts?

The test geometry should not be considered fixed.  With digital control of the geometry, we should consider

### Images

Figure 1: Test Aparatus
<details>
  Figure 1 The basic test assembly is simple and easy to adapt.   A 3D printed fixture can be mounted in an ordinary vise & torque is measured with a beam-style torque wrench.  Finer instruments can be used if needed. 
  <br />
  <summary> Exapand to view ► </summary>
  <img src="https://i.imgur.com/6gJ2nkE.jpeg" width="400" />
  </details>

Figure 2: Bonded Parts
<details>
  Initial trials involve two parts and a bonded zone for evaluation of a joint.  The primary goal is to discover if the bond has equal strength to the parts, to be found in the failure location.  
  <br />
  <summary> Expand to view ► </summary>
  <img src="https://i.imgur.com/7N04RQV.jpeg" width="400" />
  </details>


Figure 3: Fixture & sample
<details>
  The fixture (blue component) is mounted in the fixture before testing.  Easily mate the components without tools.  Steel balls interlock the parts to prevent rotation of the fixed sample.  The balls are one way to offer inexpensive tool-free interlocking and many alternatives are possible.  The black fixture can be bolted to any steady surface, clamped in a vise, or adjusted to suit a professional tensile test aparatus.
  <br />
  <summary> Expand to view ► </summary>
  <img src="https://i.imgur.com/m5M9Hzs.jpeg" width="400" />
  </details>

Figure 4: Torque measuring instrument
<details>
  The most economical option for collecting test data.  Simple beam-style torque wrench with analog readout.  These beam-style torque wrenches are available for auto mechanics at low cost and typically mate with 1/2in or 3/8in square socket (female).  This photo includes a low-cost wrench desigend for oil filters or "oil filter wrench" which can be used to grip circular or polygon profiles.
  <br />
  <summary> Expand to view ► </summary>
  <img src="https://i.imgur.com/cynPAI1.jpeg" width="400" />
  </details>

Figure 5: Fixture Pin
<details>
  The image shows a high-strength bolt acting as a pin, with M8 thread size and smooth shoulder.   The pin can be included for maintaining alignment of the test components or omitted to offer freedom of motion.  The pin can lightly clamp the samples to isolate force in the torque z-direction.  Alternatively, the pin can clamp with a prescribed clamping force to test results on friction or interlocking geometries.
  <br />
  <summary> Expand to view ► </summary>
  <img src="https://i.imgur.com/yAnao1i.jpeg" width="400" />
  </details>

Figure 5: Failure Zone
<details>
  The image shows the shear zone where failure is expected for a bonded pair of samples.  The geometry herein can be loosely assumed to be a thin tube for shear calculations or it can be adjusted to a custom shape, to more closely match analytical solutions.
  <br />
  <summary> Expand to view ► </summary>
  <img src="https://i.imgur.com/zCy4Pzv.jpeg" width="400" />
  </details>
