# Methods

Methods for engineering applications: successful combination of parts.  (I'm aiming to improve the organization of this page; consider this a draft).

# Bonding Materials
Bonding Materials for Mechatronics Projects.


## Bonding Spreadsheet
As I began making this spreadsheet, I asked: what value am I adding that I could not find in other online resources?  Why did I have access to these other guides for so long, with so little success? Instead of creating another copy of a generic gluing table, this guide is intended to cover the following points:

* Exclusion of material pairs that are less relevant.
* Include real engineering criteria such as vibration resistance, UV tolerance,
* Include real fabrication factors such as time to set, shelf life of products, and how many tools are needed to perform a bond.
* Factor in the truth: nobody wants to sand every surface, achieve perfect flatness, and wipe everything with alcohol - exclude results that only work under perfect prep conditions.
* Somehow highlight the bonding knowledge nuggets that were game changing - like the discovery of what can be done with regular old PVC cement.
* Show FAILURES: describe situations that are common failure modes, and attempts I've made repeatedly which just are not reliable.
* Acknowledge that nobody wants to read a whole label of a professional adhesive product.  Try to summarize.
* Exclude good results if they only came from one particular brand of adhesive, and the inner-magic cannot be generalized very well.
* Orient the results to be suitable for a benchmark.  An actual strength-of-a-bond test that is easy to understand instead of PSI ratings found on the label
* Factor in the fact that bond strength may depend on Material A, Material B, or the glue itself.  In many cases we don't care how strong the glue is.

Ultimately, I decided a spreadsheet will not help.  There are too many exceptions to a yes/no type of bonding guide, and it requires discussion.  So, here is a spreadsheet that is halfway finished, that has some value but is no replacement for this guide.

[Click here for an insufficient XLSX guide](https://lobfile.com/file/RgvF.xlsx)


## Anti-bonding
This topic is nearly as important as bonding.  If you can discover a trio where two materials bond securely, and a third which departs clean and easily, then you have discovered a material to use when you fixture your setup - this can sometimes be HALF THE EFFORT of a gluing project. 

**Silicone Sheets** 
* Perfect worktable for most applications.  It's the only surface I've found that I can rest a hot glue gun on, let it drip, and have a zero-effort cleanup.

## Common Mistakes:
**Hot glue gone cold**: if you bond something with a large heat capacity, you MUST HEAT THE PARTS first.  hot melt works fansastically on two metal pieces of almost any surface condition if the parts get pre-heated and you prevent the glue from cooling before you clamp the parts.  I stick my parts in a 3D printer and set the temp to 70C for 5-10 minutes to prep them.  For small parts with big glue, you can skip this:  two pennies will bond without preheating, for example.

**JB Weld on Flexible Parts** don't do it.  Hard epoxies will peel right off if your parts are not rigid.  Epoxy is best for strong materials like metal and ceramics.

**Sprinkling money on a bond** Spending more money rarely helps anything.  Your last joint did not fail because the adhesive wasn't fancy enough.  Study a little, find an answer, and try a new chemical.

**Filling gaps with no-gap glue** Some adhesives are specifically intended to fill gaps with no problem. 

**Fussing with primer** PVC primer is not necessary in many cases.  If you have to move quickly there are many reasons to skip.  Most of all, moving quickly with volatile chemicals usually ruins a shirt, stains fingers, and drips solvents on good tables.

**Not testing** What if you could know a bond performance before you deposited any glues on your nice prototype?  Welcome to testing.  Grab a scrap of your material and try it out with the 

# Videos
Tutorials by video to complement your educatinal materials.

### USB (60 minutes)
USB cables, power, 5v regulators, communication bus, measuring quality, and failure modes.
<iframe width="1250" height="703" src="https://www.youtube.com/embed/9c9-YUSbgYs" title="More about USB than you ever wanted to know" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Tape (70 minutes)
Exacting details about tape materials & where to apply them as engineering materials.
<iframe width="1250" height="703" src="https://www.youtube.com/embed/W0sAR_jI4b8" title="More than you ever wanted to know about tape" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Thread Tapping
Tap threads in aluminum materials such as aluminum extrusions.  Proper fastener sizes to match 2020, 3030, aluminum rail, for selecting your screws.
<iframe width="1250" height="703" src="https://www.youtube.com/embed/wyiSZ53XoCU?si=PQr8zx2o3mjStuCP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Proper Screwdriver for Electronics
Philips screwdrivers have sizes and they are important! Many devices have screw terminals that are easily stripped.  Please equip yourself with a properly matched driver - here is how to tell!  
<iframe width="1250" height="703" src="https://www.youtube.com/embed/Tv_4055fiXU" title="modify a screwdriver for electronics, mechatronics" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Parametric Design: Why?
Parametric example with an multimeter bracket that has configurations in solidworks.  We use variables instead of constants, and the software rebuilds the model instantly!  Then the final designs are unlimited.
<iframe width="1250" height="703" src="https://www.youtube.com/embed/OkRfWXU7b-k" title="Tutorial: modeling and mindset for a parametric bracket (SOLIDWORKS)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Shortcuts on Crimping for Sensors
Everyone uses dupont connectors for arduino, etc.  How to crimp the connectors, verify them, and better ways to build terminals for reliability.  
<iframe width="1250" height="703" src="https://www.youtube.com/embed/mdD9NaCWuJ8" title="How to crimp Dupont Terminals, and why you SHOULDNT" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Easy Pneumatic Setup
Easily and cheaply add pneumatics to your design with this example.  Convert a fire extinguisher into a pneumatic air tank SAFELY and reliably.
<iframe width="1250" height="703" src="https://www.youtube.com/embed/AszFG81e_ro" title="pneumatic air battery" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Build Spade Terminals
Quick-disconnect terminals or Spade terminals are extremely common.  When to use them, and how to crimp them reliably, and how to select terminals.
<iframe width="1250" height="703" src="https://www.youtube.com/embed/Ed4rbTW7LTw" title="How to Crimp Quick Disconnects (spade terminals)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Ferrules
Avoid failure in fitment. Precise instructions for ferrule crimping.  Use ferrules for current-carrying connections.
<iframe width="1250" height="703" src="https://www.youtube.com/embed/LtvPOjP6O40" title="How to Crimp Ferrules" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Strip Round Cables
This lesser-known tool avoids damaging the internal wires for a jacketed, round cable.
<iframe width="1250" height="703" src="https://www.youtube.com/embed/9GT5Vm_QWao" title="Strip round cables without damaging insulation" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
