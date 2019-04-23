# Capsule Networks Task's

We were assigned the following task for according to weeks

## Week 1

Learning the Maya Software and how to set up an environment for different 3D models object and write Mel Scripts and Python scripts.

So during the first week, I create few python scripts


```python
import maya.cmds as cmds

cubelist= cmds.ls("myCube")

if len(cubelist)>0:
  cmds.delete(cubelist)

result = cmds.polycube(w=9.248, h=9.248, d=9.248, name='mycube',)

print 'result'+ str (result )

transformName = cmds.instance(transformName, name =transformName ) 

![GitHub Logo](/images/logo.png)
