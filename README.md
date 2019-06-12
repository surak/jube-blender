# jube-blender
Uses JUBE (https://www.fz-juelich.de/ias/jsc/EN/Expertise/Support/Software/JUBE/_node.html) to launch multiple blender rendering tasks to your batch system

How to use

Create your blender file. Set rendering to "png" files.

edit jube-blender.xml

check the frame numbers, the input and output files. Then do a 

```
jube jube-blender.xml
```

This will create a series of png files. To assemble them into a video on a Mac, check https://github.com/surak/cocoa-tlassemble
