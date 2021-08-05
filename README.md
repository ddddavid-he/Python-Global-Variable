# GlobalVariable

#### 介绍
Python 实现跨文件的全局变量的模块


#### 使用说明




1.  导入模块

```
from GlobalVariable import globalVariables as gbv
```

2.  添加全局变量

    a.  通过对属性赋值添加

        ` gbv.newVariable = "This is a new global variable" `


    b.  通过 gbv.add()方法添加

        ` gbv.add("newVariable", "This is a new global variable") `

        
        ```
        nameList = ['a', 'b', 'c']
        valueList = [1, 2, 3]
        gbv.add(nameList, valueList)
        ```

3.  显示已添加的全局变量列表
    
    `gbv.all()`


4.  删除全局变量

    `gbv.rm('toBeRemoved')`


    ```
    nameList = ['a', 'b', 'c']
    gbv.rm(nameList)
    ```    
