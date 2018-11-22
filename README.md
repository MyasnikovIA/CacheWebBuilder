# CacheWebBuilder

1) Install class
   d $SYSTEM.OBJ.Load("%ZDFM.Component.xml","c")
   d $SYSTEM.OBJ.Load("%ZDFM.demo.xml","c")
   d $SYSTEM.OBJ.Load("%ZDFM.xml","c")

2) Copy "CacheWebBuilder.exe" to "C:\InterSystems\Cache\bin\"  or to the directory where Cache is installed

3) Set version control to the selected namespace, or to all namespaces.
   For this you need run in Cache' terminal   d ##class(%ZDFM.SourceControll).InstallSorceControllAllNameSpace()   or w ##class(%Studio.SourceControl.Interface).SourceControlClassSet("%ZDFM.SourceControll",nameSpace)

4) Restart cache studio

5) Create a class in Cache Studio, save it. Then call the context menu and run the visual form designer "Cache Web Builder"->"Designer"

6) Create elements on the form and set their properties. The form supports pasting code. example: #($h)#

7) Save and run class



<div style="position:relative;height:0;padding-bottom:56.25%"><iframe src="https://www.youtube.com/embed/WZRcpL2r3rc?ecver=2" width="640" height="360" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" style="position:absolute;width:100%;height:100%;left:0" allowfullscreen></iframe></div>

 <img src="https://github.com/MyasnikovIA/CacheWebBuilder/blob/master/CtxMenu.png?raw=true"/>
 <img src="https://github.com/MyasnikovIA/CacheWebBuilder/blob/master/ImgStud.png?raw=true"/>
 <img src="https://github.com/MyasnikovIA/CacheWebBuilder/blob/master/Res.png?raw=true"/>
 
