# @ch957869975/utils

工作中常用的的工具函数，不定时更新。

![npm](https://img.shields.io/npm/v/@ch957869975/utils.svg)

## Install

`npm i @ch957869975/utils --save`

## Usage

```js
import {getUnion} form '@ch957869975/utils'

const arr1 = [1, 2, 4]
const arr2 = [2, 3, 4]
getUnion(arr1, arr2) // [1, 2, 3, 4]

```

## API

| 函数名            | 参数          | 参数类型              | 说明                                                                                                                                                 |
| ----------------- | ------------- | --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| `trim`            | str           | String                | 删除文本内的空格                                                                                                                                     |
| `removeTag`       | str           | String                | 删除文本中的 html 标签                                                                                                                               |
| `getTimeStamp`    | str           | String                | 字符串时间转时间戳                                                                                                                                   |
| `getDate`         |               |                       | 获取当前日期                                                                                                                                         |
| `haveEmoji`       | content       | String                | 判断内容是否包含 emoji 表情                                                                                                                          |
| `getIntersection` | arr1,arr2     | Array                 | 得到两个数组的交集, 两个数组的元素为数值或字符串                                                                                                     |
| `getUnion`        | arr1,arr2     | Array                 | 得到两个数组的并集, 两个数组的元素为数值或字符串                                                                                                     |
| `hasOneOf`        | targetarr,arr | Array                 | 判断要查询的数组是否至少有一个元素包含在目标数组中                                                                                                   |
| `oneOf`           | value,arr     | String/Number , Array | String                                                                                                                                               | 判断要查询的值是否存于目标列表中 |
| `getExplorer`     |               |                       | 当前浏览器名称                                                                                                                                       |
| `on`              |               |                       | 绑定事件 on(element, event, handler)                                                                                                                 |
| `off`             |               |                       | 解绑事件 on(element, event, handler)                                                                                                                 |
| `hasKey`          | obj, key      | Object, String        | 判断一个对象是否存在 key，如果传入第二个参数 key，则是判断这个 obj 对象是否存在 key 这个属性。如果没有传入 key 这个参数，则判断 obj 对象是否有键值对 |
| `objEqual`        | obj1,obj2     | Object                | 判断两个对象是否相等，这两个对象的值只能是数字或字符串                                                                                               |
| `deepClone`       | obj           | Object                | 深拷贝对象                                                                                                                                           |
