# 1. Introduction
> You can use right now on:  
> [Online Demo](https://wingcd.github.io/upainter-demo/samples/)

This is a texture paint toolset,you can use in Unity RawImage/Mesh Texture/Unity Edtior UI/other UI system;
<div align=center>
 <img src="./images/intro-1.png"> </img>
 <br/>
 Raw Image
</div>

<div align=center>
 <img src="./images/intro-2.png"> </img>
 <br/>
 Draw on mesh
</div>

<div align=center>
 <img src="./images/intro-3.png"> </img>
 <br/>
 Draw in editor
</div>

## Features
* Paint in runtime
* Paint in editor mode
* Paint in GPU
* Solid brush
* Texture brush
* Graphic brush
* Composite brush
* Fill Tool
* More blend type
* Post effect
* Undo/Redo
# 2. Quick Start
## Use Samples
* Open demo scene "uPainter/Samples/Samples.unity" 
* Click one sample
* Draw on canvas
## How to use 
* Create a new scene
* Add a Empty Object in Canvas, and stretch to fit size
<div align=center>
 <img src="./images/create-1.png"> </img>
 <br/>
 Create Empty GameObject
</div>

* Add RawImagePaintCanvas to this 
<div align=center>
 <img src="./images/create-2.png"> </img>
 <br/>
 Add RawImagePaintCanvas component
</div>

* Create a solid brush:in assets window, click right mouse button, select in path "Create/uPainter/SolidBrush"
* Modify brush's attributes
<div align=center>
 <img src="./images/create-3.png"> </img>
 <br/>
 Create solid brush
</div>

* Assign the solid brush to RawImagePaintCanvs's "Brush" property
* Draw on canvas
<div align=center>
 <img src="./images/create-4.png"> </img>
 <br/>
 Assign brush & Draw
</div>

# 3. Details Introduce
## Solid brush 
Paint solid color to texture
<div align=center>
 <img src="./images/brush-1.png"> </img>
 <br/>
 Solid brush
</div>

> <b>Brush Color:</b> color of brush  
> <b>Size:</b> size of brush,value Range(0,1) 
> <b>Point Distance Interval:</b> the minimum distance of last two points  
> <b>Self Overlay:</b> whether or not overlay self in on paint life circle    
> <div align=center>  
> <img src="./images/brush-1-1.png"> </img>  
> <br/>  
> Self Overlay  
> </div>  
>  
> <b>Blend Mode:</b> blend type with layer texture
> * Normal: Default mode  
> * Restore: Easer use this mode  
> * Replace: Scratch card use this mode  
> * Darken  
> * Mutipy  
> * ColorBurn  
> * LinearDark  
> * Lighten  
> * ColorScreen  
> * ColorDodge  
> * LinearDodge  
> * Overlay  
> * HardLight  
> * SoftLight  
> * VividLight  
> * PinLight  
> * LinearLight  
> * HardMix  
> * Difference  
> * Exclusion  
> * Subtract  
> * Add  
>  
> <div align=center>  
> <img src="./images/brush-1-2.png"> </img>  
> <br/>  
> Some blend modes  
> </div> 
>  
> <b>Softness:</b> softness of brush, value Range(0,1),default is 0>  
> <div align=center>  
> <img src="./images/brush-1-3.png"> </img>  
> <br/>  
> Softness
> </div> 
>  
> <b>Noise Rate:</b> mask brush with noise, can use this property to simulation uneven effect,such as crayon pen, only value bigger than 0 can be effective,value Range(0,1)
> <b>Noise Size:</b> set the noise size, only noise rate bigger than 0 can be effective,value Range(0,1)  
> <div align=center>  
> <img src="./images/brush-1-4.png"> </img>  
> <br/>  
> Noise
> </div> 
>  

## Texture brush
## Graphic brush
## Composite brush
## Post effect
## Undo/Redo