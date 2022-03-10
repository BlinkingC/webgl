# 创建和初始化着色器

## 创建着色器对象
    gl.createShader()
## 向着色器对象填充着色器程序的源代码
    gl.shaderSource()
## 编译着色器
   gl.compileShader()
## 创建程序对象
   gl.createProgram()
## 为程序对象分配着色器
   gl.attachShader()
## 链接程序对象
   gl.linkProgram()
## 使用程序对象
   gl.useProgram()


## 链接数据
### 新建矩阵数据
   var array=[]
### 创建缓冲区
    gl.createBuffer()
### 指定缓冲区类型
    gl.bindBuffer()
### 绑定数据
    gl.bufferData()
###  获取shader变量  
    gl.getAttribLocation()
### 告诉显卡从当前绑定的缓冲区（bindBuffer()指定的缓冲区）中读取顶点数据。
    gl.vertexAttribPointer()
### 激活顶点数据
    gl.enableVertexAttribArray()


