---
title: Main Page
permalink: /Main_Page/
---

## A.A. Martinos Center / Wald group anthropomorphic phantom builder's Wiki

<a href="/File:giorgio_phant.jpg" class="wikilink"
title="200px|thumb|right|CAD model of the &quot;MGH head 1&quot; phantom">200px|thumb|right|CAD
model of the "MGH head 1" phantom</a>

This Wiki is a resource for people interested in constructing
anthropomorphic MRI phantoms developed by [Larry Wald's
group](http://www.nmr.mgh.harvard.edu/martinos/people/showPerson.php?people_id=178)
at the [Martinos Center for Biomedical
Imaging](http://www.nmr.mgh.harvard.edu/martinos/flashHome.php),
[Massachusetts General Hospital](http://www.massgeneral.org/).

The basic principle is that improved anthropomorphic phantoms lead to
better and faster development of MRI methodology with less use of
healthy subject volunteers. This is both cost effective and ethical.
Therefore we distribute our designs and ask only that you reference the
appropriate paper and the source of the design.

Designs are available in standard CAD format are intended to be 3D
printed. Most of the components are open source designs.

## MGH 3D-printing CAD phantoms for download

- [MGH head
  phantom](https://phantoms.martinos.org/index.php/MGH_head_1:MGH_head_1)
- [MGH "Angel 001" head phantom with realistic
  B0](https://phantoms.martinos.org/MGH_Angel_001)
- [MGH "Angel 002" head phantom with realistic B0 (re-fillable brain
  compartment)](https://phantoms.martinos.org/index.php/MGH_Angel_002)
- [MGH fetal phantom version
  1](https://phantoms.martinos.org/index.php/MGH_fetal_1:MGH_fetal_1)

## MGH voxel numerical models for download

- [MGH "Angel 001" voxel head
  model](https://phantoms.martinos.org/MGH_Angel_001_voxels)
- [MGH "BoMA" voxel head
  model](https://phantoms.martinos.org/MGH_BoMA_voxels)
- [MGH "HS1" voxel head + chest model (female, medium
  size)](https://phantoms.martinos.org/HS1_voxels)
- [MGH "HS3" voxel head + chest model (male, large
  size)](https://phantoms.martinos.org/HS3_voxels)
- [MGH "HS4a" voxel head + chest model (female, large
  size)](https://phantoms.martinos.org/HS4a_voxels)
- [MGH "HS6" voxel head + chest model (male, large
  size)](https://phantoms.martinos.org/HS6_voxels)
- [MGH "DCA" detailed voxel head model (female, medium
  size)](https://phantoms.martinos.org/DCA_voxels)
- [DBS Virtual
  Population](https://phantoms.martinos.org/DBS_virtual_population)

## 3D-printed phantoms construction tips

<a href="/File:Rubber_spray.jpg" class="wikilink"
title="200px|right|thumb|Red rubber spray used to waterproof 3D printed plastic parts">200px|right|thumb|Red
rubber spray used to waterproof 3D printed plastic parts</a>

This section contains general instructions for making 3D printed
phantoms. More detailed/specific instructions may be available on the
individual phantoms webpage.

### 3D printing

Once you have downloaded the CAD files for a specific phantom, 3D print
them. Note that some parts may require you to be able to dissolve the
support material, which is not possible on all 3D printers. This is most
important for complex parts (e.g., skull) with many grooves and cavities
that are not be easily reachable. If you do dissolve the support
material using a solvent, make sure that the parts are clean and
perfectly dry before continuing the phantom making process (this may
require leaving them in a well-ventilated area for one or two days).

When used for MRI, the plastic parts must be completely free of air
cavities. Therefore, it is important that all parts are printed as
"dense" as opposed to "sparse". Although the "sparse" option results in
faster printing and smaller volumes of plastic being used for each
phantom, the presence of air cavities in the plastic parts will create
off-resonance effects that may render the phantom useless. It is our
experience that printing all plastic parts as "dense" is an absolute
necessity at 7 Tesla.

### Waterproofing

The next step is to seal the printed parts. Even if your 3D printer
offers a "waterproof" printing option, in our experience this does not
mean that the parts will actually be waterproof... 3D printing of
waterproof parts is difficult. Mostly, the "waterproof" 3D printing
options available on some printer work only for parts that are flat and
don't have any complex details (e.g., flat panels). These almost always
fail for complex geometries such as a human head. We have experimented
with several techniques for waterproofing phantoms including painting
the plastic parts with epoxy and melting of the plastic surface with a
solvent (acetone can be used to melt ABS parts. Methylene chloride can
be used to melt polycarbonate plastic). We have found that these two
methods do not work well however. The method that we currently use for
all our models at MGH consists in spraying the parts with a rubber
spray. For our phantoms, we apply three thick coats of rubber spray on
the outside and the inside of all parts (covering the outside of the
outer parts prevents leaks and sweating in the event where some water
infiltrates the plastic parts because of failure of the inner-most
rubber coat). We use a red rubber spray as opposed to a black one since
the latter color is often achieved using ferrite particles that may be
magnetic. Note that the parts must be entirely sealed with spray before
assembly (inside and outside surface), including the small grooves and
nudges used for assembly of matching parts (for good mating of
complementary parts after coating with the rubber spray, we have left
some room between the matching grooves and nudges in the CAD models).

We have had success with the following aerosol spray rubber coating (3
or 4 coats):

Performix 11201 Plasti Dip Red Multi-Purpose Rubber Coating Aerosol - 11
oz. (Red)

[McMaster Carr weblink for Plasti-Dip rubber
spray](http://www.mcmaster.com/#9560t4/=1370zq1)

The red spray works the best.

### Assembly

Once all parts are waterproofed, simply assemble them by gluing them
with epoxy. Apply a small pressure between the two parts during curing
to ensure a good seal. If the phantom contains nested parts (e.g. a
skull compartment inside an outer plastic shell), assemble the inner
compartment first and the outer second. Also, if the filling port of the
inner compartment does not extend outside the phantom do not forget to
fill the compartment before assembling the outer compartment!

### Filling

<a href="/File:Cond_vs_NaCl.JPG" class="wikilink"
title="300px|right|thumb|Linear relationship between NaCl concentration and the conductivity as determined using a dielectric probe">300px|right|thumb|Linear
relationship between NaCl concentration and the conductivity as
determined using a dielectric probe</a>

The final step consists in filling the various compartments with
tissue-mimicking gel. We use the following mixture (all concentrations
are in percent of total weight):

- Agar: 1% to 3% depending on the desired viscosity. When mixed with
  water, a 1% agar solution has a tick but liquid consistency. A
  water-based 3% agar solution is solid at room temperature.
- Gadolinium: 0.1%, this is useful to reduce T1 and hence allows faster
  testing of protocols (short TR).
- Salt (NaCl): This is required for increasing the conductivity of the
  mixture and hence loading of the coil. See the graph on the right to
  determine the appropriate concentration.
- Sodium Azide (NaN3): 0.05%, this is used to prevent bacterial growth.
  (Use caution working with NaN3 as it is highly toxic. Do not let NaN3
  solution contact skin. Also avoid exposing the powder or solution to
  metal objects, which can generate toxic gas)

Additionally, one can add ethylene glycol form to lower the permittivity
(the mixture above has a permittivity close to that of water, i.e. ~80,
which is greater than the permittivity of biological tissues, i.e. ~50).
The proper concentration of ethylene glycol should be determined using a
dielectric probe. In our experience, lowering the water permittivity to
tissue-levels requires large amounts of ethylene glycol. This may change
other parameters of the mixture such as its consistency and its
conductivity. In order to prepare the mixture, we recommend the
following step-by-step process:

- Heat the water in glass containers using a microwave oven until the
  water boils.
- Add all the ingredients except the agar and mix well.
- If you kept the water hot using a hot plate, turn it off (otherwise
  you will burn the agar at the bottom of the container). Slowly pour
  the agar powder in the hot mixture while stirring continuously to
  avoid the formation of large lumps of undissolved agar. Note that for
  the agar to dissolve well, the water temperature should be at least 80
  degrees Celsius.

Before filling the phantom you may want to wait an hour or two so that
the mixture cools and doesn't damage the waterproof rubber coating. Also
keep in mind that agar shrinks in volume as it cools down. To completely
fill the phantom compartments, wait until the agar mixture completely
cools and then complete filling with some of the leftover mixture.
Finally, seal the compartment using hot glue.

## References

\[<http://www.ncbi.nlm.nih.gov/pubmed/17659546> Design, Construction and
Evaluation of an Anthropomorphic Head Phantom With Realistic
Susceptibility Artifacts

\[<http://www.ncbi.nlm.nih.gov/pubmed/3821466> New Polyvinyl Alcohol Gel
Material for MRI Phantoms

\[<http://www.ncbi.nlm.nih.gov/pubmed/16148391> Tissue-mimicking phantom
materials for narrowband and ultrawideband microwave applications

\[<http://www.ncbi.nlm.nih.gov/pubmed/22396226> A Novel MRI-Compatible
Brain Ventricle Phantom for Validation of Segmentation and Volumetry
Methods

\[<http://www.ncbi.nlm.nih.gov/pubmed/21866208> Heterogeneous
Anthropomorphic Phantoms With Realistic Dielectric Properties For
Microwave Breast Imaging Experiments

\[<http://www.ncbi.nlm.nih.gov/pubmed/22225325> An anthropomorphic
polyvinyl alcohol brain phantom based on Colin27 for use in multimodal
imaging