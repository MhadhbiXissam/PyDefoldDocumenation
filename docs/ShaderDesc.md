
# ShaderDesc : 
## ```Memebers```    
```rust
shaders : List[ShaderDesc.Shader] = []  
reflection : ShaderDesc.ShaderReflection = None  
shader_type : int = 0  
```

## ``[ENUM]`` : `Language`    
```python
ShaderDesc.Language.LANGUAGE_GLSL_SM120
ShaderDesc.Language.LANGUAGE_GLSL_SM140
ShaderDesc.Language.LANGUAGE_GLES_SM100
ShaderDesc.Language.LANGUAGE_GLES_SM300
ShaderDesc.Language.LANGUAGE_SPIRV
ShaderDesc.Language.LANGUAGE_PSSL
ShaderDesc.Language.LANGUAGE_GLSL_SM430
ShaderDesc.Language.LANGUAGE_GLSL_SM330
```
## ``[ENUM]`` : `ShaderType`    
```python
ShaderDesc.ShaderType.SHADER_TYPE_VERTEX
ShaderDesc.ShaderType.SHADER_TYPE_FRAGMENT
ShaderDesc.ShaderType.SHADER_TYPE_COMPUTE
```
## ``[ENUM]`` : `ShaderDataType`    
```python
ShaderDesc.ShaderDataType.SHADER_TYPE_UNKNOWN
ShaderDesc.ShaderDataType.SHADER_TYPE_INT
ShaderDesc.ShaderDataType.SHADER_TYPE_UINT
ShaderDesc.ShaderDataType.SHADER_TYPE_FLOAT
ShaderDesc.ShaderDataType.SHADER_TYPE_VEC2
ShaderDesc.ShaderDataType.SHADER_TYPE_VEC3
ShaderDesc.ShaderDataType.SHADER_TYPE_VEC4
ShaderDesc.ShaderDataType.SHADER_TYPE_MAT2
ShaderDesc.ShaderDataType.SHADER_TYPE_MAT3
ShaderDesc.ShaderDataType.SHADER_TYPE_MAT4
ShaderDesc.ShaderDataType.SHADER_TYPE_SAMPLER2D
ShaderDesc.ShaderDataType.SHADER_TYPE_SAMPLER3D
ShaderDesc.ShaderDataType.SHADER_TYPE_SAMPLER_CUBE
ShaderDesc.ShaderDataType.SHADER_TYPE_SAMPLER2D_ARRAY
ShaderDesc.ShaderDataType.SHADER_TYPE_UNIFORM_BUFFER
ShaderDesc.ShaderDataType.SHADER_TYPE_UVEC2
ShaderDesc.ShaderDataType.SHADER_TYPE_UVEC3
ShaderDesc.ShaderDataType.SHADER_TYPE_UVEC4
ShaderDesc.ShaderDataType.SHADER_TYPE_TEXTURE2D
ShaderDesc.ShaderDataType.SHADER_TYPE_UTEXTURE2D
ShaderDesc.ShaderDataType.SHADER_TYPE_RENDER_PASS_INPUT
ShaderDesc.ShaderDataType.SHADER_TYPE_UIMAGE2D
ShaderDesc.ShaderDataType.SHADER_TYPE_IMAGE2D
ShaderDesc.ShaderDataType.SHADER_TYPE_SAMPLER
ShaderDesc.ShaderDataType.SHADER_TYPE_STORAGE_BUFFER
```

