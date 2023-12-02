# Statproject
Python and Solidworks statistical analysis for university year 3 RnD module project. The aim of this project is to perform multiple statistical analysis on a medical prosthetic.

The chosen paper can be found at [https://journals.lww.com/spinejournal/FullText/2005/09011/The_Treatment_of_Spine_and_Chest_Wall_Deformities.11.aspx]

The objective of the paper is: 
Is VEPTR (Vertical Expandable Prosthetic titanium rib) expansion good for treatment of TIS (Thoracic insufficiency syndrome) associated with fused ribs.
- ET (expansion thoracostomy) and VEPTR were developed to directly control spine and chest deformity during growth

Important arameters measured in the paper are:
- Cobb angle (standard measurement to determine and track the progression of scoliosis)
- Length of Thoracic spine
- CT derived lung volumes
- Pulmonary function tests
    - only in older children

 Cobb angle is deemed to be the 'success' variable as that is the goal of the paper. Cobb angles range can be in an extensive range and response depends on value
![image](https://github.com/Luk446/Stat_project_2450027/assets/145694364/06e9e430-20b5-45d2-813b-19208ee26b13) source[https://openi.nlm.nih.gov/detailedresult?img=PMC4192527_kjod-44-254-g001&req=4]

 Specific cobb angles (degree)
- approx 10 = minimum for scoliosis
- 15 < X < 20 = low priority
- 20 < X < 40  = medium
- 40+ = spinal intervention required

Due to the importance of this variable the first analysis we do is based on it. It can be found in "Cobbangleanlysis.ipynb", in this we perform a hypothesis test with use of a anderson darling test