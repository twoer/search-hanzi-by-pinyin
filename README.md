# 根据拼音反向查找汉字

比如，已知：

>{
    "NAME": "交通银行股份有限公司四川省分行营业部",
    "PINYIN": "jiao tong yin hang gu fen you xian gong si si chuan sheng fen hang ying ye bu"
},

输入：`gongsigs` 或者 `gs` 返回 `公司`

实现原理：`基于正则`

Demo：[https://twoer.github.io/search-hanzi-by-pinyin/example/](https://twoer.github.io/search-hanzi-by-pinyin/example/)


# 使用方法
`var result = pinyinUtils.searchHanziByPinyin(key, list, pinyinKey, hanziKey, isInitial);`

`key`：关键字  
`list`：数据源  
`pinyinKey`：拼音字段 key  
`hanziKey`：汉字字段 key  
`isInitial`：是否按照首字母搜索  

返回结果：

`hanzi`：`Array`，搜索关键字，如 `['交', '通']`    
`list`：`Array`，搜索结果  

