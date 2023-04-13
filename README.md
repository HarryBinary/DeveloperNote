# DeveloperNote

When adding a new package to Anaconda, encounter the message: Multiple Errors Encountered
This is because you install Anaconda for all users in the PC (C:/ProgramFiles instead of C:/User/You/). So you need to launch Anaconda as admin. 
You can enable this behaviour by default by navigating to the Anaconda launch shortcut, right-click > Properties, go to Shortcut tab, click Advanced, and tick 'Always launch as administrator'.
Ref: https://stackoverflow.com/questions/53716956/anaconda-navigator-multiple-errors-encountered

When installing CUDA, encounter the message: Installation cannot continue
TO solve it, you need to choose Custom at first and then disable Visual Studio Integration.
Ref: https://forums.developer.nvidia.com/t/windows-10-cuda-installation-failure-solved/64389/2
