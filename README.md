# Viscoelastic-Abaqus-model-for-the-analysis-of-composite-curing
This project presents an innovative approach for examining residual stresses in composites, induced by curing: an Abaqus viscoelastic model. The implementation of the model is carried out in Abaqus CAE, utilizing multiple Fortran subroutines such as USDFLD, UMAT, HETVAL, UEXPAN, and DISP.

![image](https://github.com/user-attachments/assets/2bd63acd-88a0-49f8-a800-74d349ce2e0d)

The Abaqus viscoelastic model is well recognized as a promising approach for analyzing curing behavior in composites, including residual stresses, strains, temperature, and polymerization during the curing process. In this project, we used the Abaqus viscoelastic model to analyze residual stresses, strains, temperature, and the degree of cure in AS4/3501-6 prepreg. For verification, we compared the results with the reference solution. For example, as shown in the figure below, the stress in the thickness direction obtained using the Abaqus viscoelastic model is well verified against the reference solution.

![image](https://github.com/user-attachments/assets/f0a8ecf7-247e-4eaf-8979-089e817c38a0)

In this repository, we have provided the complete .inp file, while some parts of the subroutines for the Abaqus viscoelastic model, written in Fortran, are also included. The subroutines provided are DISP, USDFLD, UMAT, HETVAL, and UEXPAN. More details regarding these models, along with theoretical explanations and the full Fortran codes for the Abaqus viscoelastic curing model, are available in our full package. You can access it through the link provided in the "About" section on the right side.

![image](https://github.com/user-attachments/assets/ab3a5bfb-d423-4cdc-8fad-7b9f422b7577)
