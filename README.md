# SPM_modify
### spm_contrast.m
change contrast save filename --> filename = contrast name   
e.x. con_0001.nii --> T_<conName>.nii

### spm_run_factorial_design.m
aim to overwrite SPM.mat automatically
add a try to read a "overwrite.mat" file in user-define code dir, 
if not have this file in pwd then ask user to check want to overwrite or not.

### spm_run_fmri_spec.m
aim to overwrite SPM.mat automatically
add a try to read a "overwrite.mat" file in user-define code dir, 
if not have this file in pwd then ask user to check want to overwrite or not.
