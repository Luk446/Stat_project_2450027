This folder contains limited visualisation of the solidworks part of the project. Due to the specificity of displaying models site like grabcad are much more suited. The construction drawings FEA reports are all available however. 

A limited amount of python is performed for this section too and can be found in solidworkspython

The models can be found on my [GrabCad!](https://grabcad.com/luke.edgecombe-2/models)

For this portion of the project. Using surgeon manuals and the paper a replication of the prosthetic was generated.

Once the model was generated
- model is assembled
- appropriate finite element analysis (FEA) achieved
- Visualisation done
- construction drawings with dimension are made

-  assembly manual used for dimensions  [Manual](VEPTR_information_sheet.pdf) + [Manual 2](veptter_2_manual.pdf)


The construction drawing sheet demonstrates the individual parts dimensions and the method of assembly through sub-assembly and exploded views (it is shown on pic but for clarity dimensions are in mm)

![Constructiondrawings+assems](https://github.com/Luk446/Stat_project_2450027/assets/145694364/d9d9b34a-ab4e-4b96-8733-7f5b4b1ea489)


The folder study reports contains the generated FEA analysis info, the detail is extensive and provides in-depth evaluation on the material response parameters.

For an easier more general evaluation a python notebook is generated following the format below:

- For the data from the two assemblies we use the seaborn histplot function which plots bivariate histograms that are excellent in demonstrating the density of value distribution for values recorded

First we analyse the extension assembly, in particular a torsion analyisis on the circular face 
![image](https://github.com/Luk446/Stat_project_2450027/assets/145694364/c0e6d1f2-8625-4a71-b314-a6ad4e1e6fae)

Next we analyse the screw hook assembly, the hook face is tested.

![image](https://github.com/Luk446/Stat_project_2450027/assets/145694364/ee2e7f7e-f81d-453e-b937-d6a427c60856)

All info derived is collated and displayed in the notebook "solidworkspython"
