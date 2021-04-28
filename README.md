# Feng's Lab_indentation_device&code
Here's the source code for indentation data processing.
# introduction
​	A custom-built indentation device is used for testing of viscoelastic properties of soft tissue. The device control program and GUI are based on LABVIEW. The data processing programs are written with MATLAB.

### Indentation device

![image1](https://github.com/aaronfeng369/FengLab_indentation_code/blob/main/photo/figure1.png)

### Typical stress-relaxation curve

![image2](https://github.com/aaronfeng369/FengLab_indentation_code/blob/main/photo/figure2.png)

### Data processing code

​	The data processing codes are written with MATLAB. The version of MATLAB is R2020b. Optimization Toolbox (version 9.0) and Global Optimization Toolbox (version 4.4) are required to be installed. The MATLAB codes can be download [here](https://github.com/aaronfeng369/FengLab_indentation_code/blob/main/indentation_codes.zip). 

### Demo data

​	The original data of stress relaxation process of 4 gelatin phantom samples captured during the indentation test is uploaded as [demo data](https://github.com/aaronfeng369/FengLab_indentation_code/tree/main/demo_data). Please run the "labview_display_v3.m" file with MATLAB (version: R2020b, required to be install Optimization Toolbox and Global Optimization Toolbox.

​	The "data.xlsx" contains the all the estimated parameters (C_0,C_1,C_2,tau1,tau2,R2) of each sample. The instantaneous shear modulus G_0 and long-term shear modulus G_infty are calculated based on the estimated parameters.

# Related Paper

 If you use our MATLAB processing code or some part of the code, please cite:

- Characterizing viscoelastic properties of breast cancer tissue in a mouse model using indentation

  DOI: https://doi.org/10.1016/j.jbiomech.2018.01.007

- Measurement of viscoelastic properties of injured mouse brain after controlled cortical impact
  
  DOI: https://doi.org/10.1007/s41048-020-00110-1
  
  Add paper here
  
