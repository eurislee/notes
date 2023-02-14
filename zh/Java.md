## GSON解析转换LinkedTreeMap
指定类型转换  
```java
 List list = new Gson().fromJson(json, new TypeToken<List<list>>(){}.getType());
 String str_list = list.get(i).getValue();
```