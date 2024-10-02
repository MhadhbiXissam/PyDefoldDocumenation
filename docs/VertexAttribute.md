
# VertexAttribute : 
## ```Memebers```    
```rust
name : str = ''  
name_hash : int = 0  
semantic_type : int = 1  
element_count : int = 0  
normalize : bool = False  
data_type : int = 7  
coordinate_space : int = 2  
long_values : VertexAttribute.LongValues = None  
double_values : VertexAttribute.DoubleValues = None  
binary_values : bytes = b''  
```

## ``[ENUM]`` : `DataType`    
```python
VertexAttribute.DataType.TYPE_BYTE
VertexAttribute.DataType.TYPE_UNSIGNED_BYTE
VertexAttribute.DataType.TYPE_SHORT
VertexAttribute.DataType.TYPE_UNSIGNED_SHORT
VertexAttribute.DataType.TYPE_INT
VertexAttribute.DataType.TYPE_UNSIGNED_INT
VertexAttribute.DataType.TYPE_FLOAT
```
## ``[ENUM]`` : `SemanticType`    
```python
VertexAttribute.SemanticType.SEMANTIC_TYPE_NONE
VertexAttribute.SemanticType.SEMANTIC_TYPE_POSITION
VertexAttribute.SemanticType.SEMANTIC_TYPE_TEXCOORD
VertexAttribute.SemanticType.SEMANTIC_TYPE_PAGE_INDEX
VertexAttribute.SemanticType.SEMANTIC_TYPE_COLOR
VertexAttribute.SemanticType.SEMANTIC_TYPE_NORMAL
VertexAttribute.SemanticType.SEMANTIC_TYPE_TANGENT
```

