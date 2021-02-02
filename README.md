# neoca-workspace-skel

Quick usage:

1. Clone this
   ```
   git clone https://github.com/semedia-id/neoca-workspace-skel.git
   ```

2. Rename 'neoca-workspace-skel' to 'workspace'

3. to Use Gantry lefo:
   make symbolic link from user/workspace/scss, please follow this example.
   (There to much error to handle if create automaticly inside php):

   in windows:
   -----------
   ```
   mklink /D scss ..\..\..\workspace\scss
   ```

   in linux/bash:
   --------------

   ```
   ln -s ../../../workspace/scss scss
   ```   
   
