#数组相关

PHP的数组可以作为Golang的array、map、slice使用

PHP的`$isSet = isset($arr["key3"])`类比Goalng的
```
arr := map[string] string {"key1":"a", "key2":"b"}
_, isSet := arr["key3"] 
```

PHP的`unset($arr["key3"])`等价于Goalng的
```
arr := map[string] string {"key1":"a", "key2":"b"}
_, isSet := arr["key3"] 
if isSet {
    delete(arr, "key3")
}
```
