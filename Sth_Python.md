### Python string删除元素

`str`为immutabe类型，不能直接删除，需要删除得用`string.replace(str,char,'')`,或者`string.strip`

### Python 深复制与浅复制

```python
a = [1,2,3]
b = a #b 为浅复制 ,深复制需要用
a[0]=5
b #[5, 2, 3]

#深复制

b = copy.deepcopy(a)
print b #[1, 2, 3]
a[0]=5
print a #[5, 3, 3]
print b#[1, 2, 3]

```

### 新式类(new style class)

类无其他继承时加上`objectclass A(object)`:`super` 只能用于新式类`super`多类继承时不会重复执行

###  
