
# MaterialDesc : 
## ```Memebers```    
```rust
name : str = ''  
tags : List[str] = []  
vertex_program : str = ''  
fragment_program : str = ''  
vertex_space : int = 0  
vertex_constants : List[MaterialDesc.Constant] = []  
fragment_constants : List[MaterialDesc.Constant] = []  
textures : List[str] = []  
samplers : List[MaterialDesc.Sampler] = []  
max_page_count : int = 0  
attributes : List[Defold.VertexAttribute] = []  
```

## ``[ENUM]`` : `ConstantType`    
```python
MaterialDesc.ConstantType.CONSTANT_TYPE_USER
MaterialDesc.ConstantType.CONSTANT_TYPE_VIEWPROJ
MaterialDesc.ConstantType.CONSTANT_TYPE_WORLD
MaterialDesc.ConstantType.CONSTANT_TYPE_TEXTURE
MaterialDesc.ConstantType.CONSTANT_TYPE_VIEW
MaterialDesc.ConstantType.CONSTANT_TYPE_PROJECTION
MaterialDesc.ConstantType.CONSTANT_TYPE_NORMAL
MaterialDesc.ConstantType.CONSTANT_TYPE_WORLDVIEW
MaterialDesc.ConstantType.CONSTANT_TYPE_WORLDVIEWPROJ
MaterialDesc.ConstantType.CONSTANT_TYPE_USER_MATRIX4
```
## ``[ENUM]`` : `VertexSpace`    
```python
MaterialDesc.VertexSpace.VERTEX_SPACE_WORLD
MaterialDesc.VertexSpace.VERTEX_SPACE_LOCAL
```
## ``[ENUM]`` : `WrapMode`    
```python
MaterialDesc.WrapMode.WRAP_MODE_REPEAT
MaterialDesc.WrapMode.WRAP_MODE_MIRRORED_REPEAT
MaterialDesc.WrapMode.WRAP_MODE_CLAMP_TO_EDGE
```
## ``[ENUM]`` : `FilterModeMin`    
```python
MaterialDesc.FilterModeMin.FILTER_MODE_MIN_NEAREST
MaterialDesc.FilterModeMin.FILTER_MODE_MIN_LINEAR
MaterialDesc.FilterModeMin.FILTER_MODE_MIN_NEAREST_MIPMAP_NEAREST
MaterialDesc.FilterModeMin.FILTER_MODE_MIN_NEAREST_MIPMAP_LINEAR
MaterialDesc.FilterModeMin.FILTER_MODE_MIN_LINEAR_MIPMAP_NEAREST
MaterialDesc.FilterModeMin.FILTER_MODE_MIN_LINEAR_MIPMAP_LINEAR
MaterialDesc.FilterModeMin.FILTER_MODE_MIN_DEFAULT
```
## ``[ENUM]`` : `FilterModeMag`    
```python
MaterialDesc.FilterModeMag.FILTER_MODE_MAG_NEAREST
MaterialDesc.FilterModeMag.FILTER_MODE_MAG_LINEAR
MaterialDesc.FilterModeMag.FILTER_MODE_MAG_DEFAULT
```

