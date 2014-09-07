Thanks for installing PandocTasks.

A new build action has been added to your project called "Pandoc". Set any files that you want to transform with pandoc to use this build action, and they will be transformed during build.

The default output format is html, and the transformed file will be placed in the same directory as the input file. You can change these settings by setting <PandocOutputFormat> or <PandocOutputDir> in your project file. See the PandocTasks.targets file for all the options.

This nuget package includes a copy of pandoc which is licensed under the GPL. A copy of the license can be found in the package \build directory.