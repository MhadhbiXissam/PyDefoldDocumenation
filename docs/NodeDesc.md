
# NodeDesc : 
## ```Memebers```    
```rust
position : Defold.Vector4 = None  
rotation : Defold.Vector4 = None  
scale : Defold.Vector4One = None  
size : Defold.Vector4 = None  
color : Defold.Vector4One = None  
type : int = 0  
blend_mode : int = 0  
text : str = ''  
texture : str = ''  
font : str = ''  
id : str = ''  
xanchor : int = 0  
yanchor : int = 0  
pivot : int = 0  
outline : Defold.Vector4WOne = None  
shadow : Defold.Vector4WOne = None  
adjust_mode : int = 0  
line_break : bool = False  
parent : str = ''  
layer : str = ''  
inherit_alpha : bool = False  
slice9 : Defold.Vector4 = None  
outerBounds : int = 1  
innerRadius : float = 0.0  
perimeterVertices : int = 32  
pieFillAngle : float = 360.0  
clipping_mode : int = 0  
clipping_visible : bool = True  
clipping_inverted : bool = False  
alpha : float = 1.0  
outline_alpha : float = 1.0  
shadow_alpha : float = 1.0  
overridden_fields : List[int] = []  
template : str = ''  
template_node_child : bool = False  
text_leading : float = 1.0  
text_tracking : float = 0.0  
size_mode : int = 0  
spine_scene : str = ''  
spine_default_animation : str = ''  
spine_skin : str = ''  
spine_node_child : bool = False  
particlefx : str = ''  
custom_type : int = 0  
enabled : bool = True  
visible : bool = True  
material : str = ''  
```

## ``[ENUM]`` : `Type`    
```python
NodeDesc.Type.TYPE_BOX
NodeDesc.Type.TYPE_TEXT
NodeDesc.Type.TYPE_PIE
NodeDesc.Type.TYPE_TEMPLATE
NodeDesc.Type.TYPE_SPINE
NodeDesc.Type.TYPE_PARTICLEFX
NodeDesc.Type.TYPE_CUSTOM
```
## ``[ENUM]`` : `BlendMode`    
```python
NodeDesc.BlendMode.BLEND_MODE_ALPHA
NodeDesc.BlendMode.BLEND_MODE_ADD
NodeDesc.BlendMode.BLEND_MODE_ADD_ALPHA
NodeDesc.BlendMode.BLEND_MODE_MULT
NodeDesc.BlendMode.BLEND_MODE_SCREEN
```
## ``[ENUM]`` : `ClippingMode`    
```python
NodeDesc.ClippingMode.CLIPPING_MODE_NONE
NodeDesc.ClippingMode.CLIPPING_MODE_STENCIL
```
## ``[ENUM]`` : `XAnchor`    
```python
NodeDesc.XAnchor.XANCHOR_NONE
NodeDesc.XAnchor.XANCHOR_LEFT
NodeDesc.XAnchor.XANCHOR_RIGHT
```
## ``[ENUM]`` : `YAnchor`    
```python
NodeDesc.YAnchor.YANCHOR_NONE
NodeDesc.YAnchor.YANCHOR_TOP
NodeDesc.YAnchor.YANCHOR_BOTTOM
```
## ``[ENUM]`` : `Pivot`    
```python
NodeDesc.Pivot.PIVOT_CENTER
NodeDesc.Pivot.PIVOT_N
NodeDesc.Pivot.PIVOT_NE
NodeDesc.Pivot.PIVOT_E
NodeDesc.Pivot.PIVOT_SE
NodeDesc.Pivot.PIVOT_S
NodeDesc.Pivot.PIVOT_SW
NodeDesc.Pivot.PIVOT_W
NodeDesc.Pivot.PIVOT_NW
```
## ``[ENUM]`` : `AdjustMode`    
```python
NodeDesc.AdjustMode.ADJUST_MODE_FIT
NodeDesc.AdjustMode.ADJUST_MODE_ZOOM
NodeDesc.AdjustMode.ADJUST_MODE_STRETCH
```
## ``[ENUM]`` : `SizeMode`    
```python
NodeDesc.SizeMode.SIZE_MODE_MANUAL
NodeDesc.SizeMode.SIZE_MODE_AUTO
```
## ``[ENUM]`` : `PieBounds`    
```python
NodeDesc.PieBounds.PIEBOUNDS_RECTANGLE
NodeDesc.PieBounds.PIEBOUNDS_ELLIPSE
```

