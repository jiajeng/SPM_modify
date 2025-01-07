# SPM_modify
### spm_contrast.m
change contrast save filename --> filename = contrast name   
e.x. con_0001.nii --> con_[conName].nii  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; spmT_0001.nii --> spmT_[conName].nii

### spm_run_factorial_design.m
aim to overwrite SPM.mat automatically  
try to read a "overwrite.mat" file in user-define code dir(pwd),   
if not exist this file in pwd then ask user want to overwrite SPM.mat file or not(original SPM do).  

### spm_run_fmri_spec.m
aim to overwrite SPM.mat automatically  
try to read a "overwrite.mat" file in user-define code dir(pwd),   
if not exist this file in pwd then ask user want to overwrite SPM.mat file or not(original SPM do).  
