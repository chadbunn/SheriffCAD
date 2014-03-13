SheriffCAD
==========

###**Convert SLO County roads to shapefile for use by SO CAD.**

**1.**	Get newest cut of county roads.  
**2.**	Rename it `SLOCO_SDE_ROADS_ALL` and replace the current feature class of the same name in the Model.gdb in the project folder.  
**3.**	Open ‘sheriffmodel.tbx’ in ArcMap and right-click and edit the Tritech Model flayer in that toolbox.  
**4.**	Set the initial input as the `SLOCO_SDE_ROADS_ALL` that resides in the Model.gdb.  
**5.**	Run the model.  
**6.**	Open the ToShapefile.tbx and right-click and edit the To Sheriff Shapefile model.  
**7.**	Set the initial input to the `slo_co_sheriff_roads` feature class that was produced from the Tritech Model flayer and resides in the Model.gdb.  
**8.**	Run the model, this one takes a bit longer so be patient.  
**9.**	Your shapefile will be found as `slo_co_sheriff_roads_mm_dd_yyyy.shp` in the Results folder.    
**10.**	Send this file to the S.O. and you are DONE.  

