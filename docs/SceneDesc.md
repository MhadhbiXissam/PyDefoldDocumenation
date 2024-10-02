
# SceneDesc : 
## ```Memebers```    
```rust
script : str = ''  
fonts : List[SceneDesc.FontDesc] = []  
textures : List[SceneDesc.TextureDesc] = []  
background_color : Defold.Vector4 = None  
nodes : List[Defold.NodeDesc] = []  
layers : List[SceneDesc.LayerDesc] = []  
material : str = '/builtins/materials/gui.material'  
layouts : List[SceneDesc.LayoutDesc] = []  
adjust_reference : int = 0  
max_nodes : int = 512  
spine_scenes : List[SceneDesc.SpineSceneDesc] = []  
particlefxs : List[SceneDesc.ParticleFXDesc] = []  
resources : List[SceneDesc.ResourceDesc] = []  
materials : List[SceneDesc.MaterialDesc] = []  
max_dynamic_textures : int = 128  
```

## ``[ENUM]`` : `AdjustReference`    
```python
SceneDesc.AdjustReference.ADJUST_REFERENCE_LEGACY
SceneDesc.AdjustReference.ADJUST_REFERENCE_PARENT
SceneDesc.AdjustReference.ADJUST_REFERENCE_DISABLED
```

