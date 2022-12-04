# medlar_python3

- python3版本：`3.10.x`
- 虚拟环境使用anaconda


# 字符串

- `title()`：将每个单词的首字母大写
- `upper()`：大写
- `lower()`：小写
- `strip()`：去除首尾空格
- `lstrip()`：去除开头空格
- `rstrip()`：去除结尾空格
- `str()`：将非字符串值表示为字符串

# 列表

- `[]`：表示列表，列表元素是可修改的
- `some_list[0]`：使用索引访问列表元素
- `some_list[-1]`：返回最后一个列表元素
- `some_list[-2]`：返回倒数第二个列表元素
- `some_list[index] = "something"`：修改列表中指定索引元素的值
- `some_list.append()`：在列表元素末尾添加元素
- `some_list.insert(index, 'something')`：在指定的索引位置插入元素
- `del some_list[index]`：删除指定索引位置处的元素
- `some_list.pop()`：删除列表最后的元素，并返回删除的元素
- `some_list.pop(index)`：删除指定索引位置处的元素，并返回删除的元素
- `some_list.remove(something)`：根据值删除元素（只会删除第一个匹配到的值），并返回删除的元素
- `some_list.sort()`：对列表元素进行排序（会使原列表发生改变）
- `some_list.sort(reverse=True)`：列表按字母顺序相反的顺序排序
- `some_list.sorted()`：对列表进行临时排序（原列表不会发生改变）
- `some_list.sorted(reverse=True)`：对列表进行临时排序，按字母顺序相反的顺序排序（原列表不会发生改变）
- `some_list.reverse()`：反转列表元素的排列顺序（原列表会发生改变）
- `len(some_list)`：获取列表长度
- `for e in some_list:`：使用for循环遍历列表
- `range(1, 5)`：生成1到5的数字，不包含5
- `list(range(1, 5))`：将range()的结果转换为一个数字列表
- `range(1, 11, 2)`：指定步长，从1开始不断加2，一直到11
- `min(some_list)`：找到列表中的最小值
- `max(some_list)`：找到列表中的最大值
- `sum(some_list)`：得到列表中的值的总和
- `some_list = [value * 2 for value in range(1, 11)]`：列表解析，将for循环和创建新元素代码合并为一行
- `some_list[0:3]`：切片，获取索引0到索引2的元素
- `some_list[:3]`：切片，获取索引0到索引2的元素
- `some_list[0:]`：切片，获取索引0到列表末尾的元素
- `some_list[-3:]`：切片，获取列表中最后三个元素
- `for e in some_list[:3]:`：for循环遍历切片
- `some_new_list = some_list[:]`：复制列表

# 元组

- `()`：来定义元组，元组是元素不可修改的的列表
- `some_tuple(100, 200)`：定义个两个元素的元组
- `for e in some_tuple:`：for()循环遍历元组

# if语句

- `if`
- `elif`
- `else`
- `==`：是否相等
- `!=`：是否不相等
- `and`：检查多个条件
- `or`：检查多个条件
- `e in some_list`：检查元素是否在列表中
- `e not in some_list`：检查元素是否不包含在列表中

# 字典

- `{}`：定义字典
- `some_dict = {'key1': value1, 'key2': value2}`
- `some_dict['key']`：获取指定key的值
- `some_dict['key'] = value`：添加新的key-value到字典中
- `some_dict['key'] = new_value`：修改key对应的值
- `del some_dict['key']`：删除键值对
- `for key, value in some_dict.items():`：for循环遍历字典
- `for key, value in some_dict.keys():`：for循环遍历字典中所有键
- `for key, value in sorted(some_dict.keys()):`：for循环按顺序遍历字典中所有键
- `for key, value in some_dict.values():`：for循环遍历字典中所有值

# while循环

- `while`
- `break`
- `continue`

# 函数

- `def function_name():`：定义函数
- `function_name()`：调用函数

# 类

- `class SomeClass():`：定义类
- `__init__(self, other_arg)`：构造方法
- `some_instance = SomeClass()`：创建类的示例


# 其他

- `input()`：程序暂停等待输入
- 