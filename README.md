# iso-8583-center
8583报文解析器
作为msb里的一个基础组件：用于标准的8583报文解析报文、组装报文

## Parser 解析组件

迭代一：byte[] -> Map<String,List<Map>><br>
  迭代二：byte[] -> Object implements Serializable

## serializer 组装报文组件
支持对象序列化

迭代一：Map<String,List<Map>> -> byte[] <br>
  迭代二：Object implements Serializable -> byte[]

## 时间安排
 暂无计划，但是，在实现msg模块下的mct时，会优先做这个
