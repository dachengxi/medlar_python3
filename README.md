# medlar_python3

- python3版本：`3.10.x`
- 虚拟环境使用anaconda

# 数字

- `int()`：将其他的数据类型转换为整型
- `float()`：将其他的数字类型转换为浮点型

# 字符串

- `title()`：将字符串中每个单词的首字母大写
- `upper()`：大写
- `lower()`：小写
- `some_str.capitalize()`：字符串首字母大写
- `strip()`：去除首尾空格
- `strip('.')`：去除首尾的点
- `lstrip()`：去除开头空格
- `rstrip()`：去除结尾空格
- `str()`：将非字符串值表示为字符串
- `'some_str' *`：复制字符串
- `'some_str'[index]`：可以根据索引来获取字符串对应位置处的字符
- `replace()`：替换
- `[start:end:step]`：对字符串进行分片，得到从start开始到end之前的全部字符
  - `[:]`：分片，提取从开头到结尾的整个字符串
  - `[start:]`：分片，从start提取到结尾
  - `[:end]`：分片，从头提取到end-1
  - `[start:end]`：分片，从start提取到end-1
  - `[start:end:step]`：分片，从start提取到end-1，每step个字符提取一个
- `len(some_str)`：获取长度
- `some_str.split(',')`：使用逗号分割字符串，得到一个列表
- `','.join(some_str_list)`：将列表合并成一个字符串，使用逗号分割
- `some_str.startswith('something')`：是否以指定字符串开头
- `some_str.endswith('something')`：是否以指定字符结尾
- `some_str.find('something')`：查找第一次出现指定字符串的位置
- `some_str.rfind('something')`：查找最后一次出现指定字符串的位置
- `some_str.count('something')`：统计指定的字符串出现了多少次
- `some_str.isalnum()`：字符串所有字符都是字母或数字吗
- `some_str.center(30)`：30个字符位居中
- `some_str.ljust(30)`：左对齐
- `some_str.rjust(30)`：右对齐

# 列表

- `[]`：创建列表，列表元素是可修改的
- `list()`：创建列表、将其他数据类型转换成列表类型
- `some_list[0]`：使用索引访问列表元素
- `some_list[-1]`：返回最后一个列表元素
- `some_list[-2]`：返回倒数第二个列表元素
- `some_list[index] = "something"`：修改列表中指定索引元素的值
- `some_list.append()`：在列表元素末尾添加元素
- `some_list.extend(other_list)`：合并列表
- `some_list += other_list`：合并列表
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
- `some_new_list = some_list.copy()`：复制列表
- `some_new_list = list(some_list)`：复制列表
- `some_list.index(something)`：查询指定元素的索引位置
- `something in some_list`：判断给定的元素是否在列表中存在
- `some_list.count(something)`：统计给定的值在列表中出现的次数
- - `','.join(some_list)`：将列表合并成一个字符串，使用逗号分割

# 元组

- `()`：来定义元组，元组是元素不可修改的的列表
- `tuple()`：使用其他的类型创建元组
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
- `dict()`：将包含双值子序列的的序列转换为字典
- `some_dict = {'key1': value1, 'key2': value2}`
- `some_dict['key']`：获取指定key的值
- `some_dict['key'] = value`：添加新的key-value到字典中
- `some_dict['key'] = new_value`：修改key对应的值
- `del some_dict['key']`：删除键值对
- `some_dict.items()`：获取所有键值对
- `for key, value in some_dict.items():`：for循环遍历字典
- `some_dict.keys()`：获取所有键
- `for key, value in some_dict.keys():`：for循环遍历字典中所有键
- `for key, value in sorted(some_dict.keys()):`：for循环按顺序遍历字典中所有键
- `some_dict.values()`：获取所有值
- `for key, value in some_dict.values():`：for循环遍历字典中所有值
- `some_dict.update(other_dict)`：将一个字典的键值对复制到另一个字典中去
- `some_dict.clear()`：删除字典中所有元素
- `something in some_dict`：判断元素是否在字典中存在
- `some_dict.get(key)`：获取指定key的值
- `some_new_dict = some_dict.copy()`：将字典复制到新的字典中去

# 集合

- `set()`：创建集合、将其他类型转换为集合
- `&`：交集运算符
- `intersection()`：获取交集
- `|`：并集运算符
- `union()`：获取并集
- `-`：差集运算符
- `difference()`：获取差集
- `^`：异或运算符
- `symmetric_difference()`：获取异或集
- `<=`或`issubset()`：判断一个集合是否是另一个集合的子集
- `>=`或`issuperset()`：判断一个集合是否是另一个集合的超集

# while循环

- `while`
- `break`
- `continue`
- `else`：循环外else，如果while正常结束，没有使用break跳出，程序将进入可选的else段

# for迭代

- `for something in some_list:`：遍历列表
- `break`
- `continue`
- `else`：循环外else，如果while正常结束，没有使用break跳出，程序将进入可选的else段
- `zip()`：对多个序列进行并行迭代

# 函数

- `def function_name():`：定义函数
- `function_name()`：调用函数
- `def function_name(*args):`：星号将一组可变数量的位置参数集合合成参数数值的元组
- `def function_name(**kwargs):`：两个星号将参数收集到字典中
- 内部函数，在函数中定义另外一个函数
- 闭包
- lambda()函数，匿名函数

# 装饰器

- 装饰器是一个函数，把一个函数作为输入并且返回另外一个函数
- 可以直接调用装饰器函数，进行人工装饰器赋值
- 可以在要装饰的函数前添加装饰器名字`@decorator_name`进行装饰

# 类

- `class SomeClass():`：定义类
- `__init__(self, other_arg)`：构造方法
- `some_instance = SomeClass()`：创建类的示例
- `class SomeClass(SomeSuperClass):`：继承类
- 以`self`作为第一个参数的方法是实例方法
- `@classmethod`指定的方法是类方法，类方法第一个参数是类本身`cls`
- `@staticmethod`修饰的方法是静态方法

# 文件

- `with open(filename) as some_file:`：打开文件
- `with open(filename, 'wt') as some_file:`：以写模式打开文本文件
  - mode的第一个字母：
    - `r`：读模式
    - `w`：写模式
    - `a`：附加模式
  - mode的第二个字母：
    - `t`：表示文本类型
    - `b`：表示二进制文件
- `some_file.read()`：读取文件
- `some_file.readline()`：读取一行
- `for line in some_file:`：按行读取文件
- `lines = some_file.readlines()`：读取所有行，并存储在列表中
- `some_file.write()`：写内容到文件中
- `some_file.tell()`：返回距离文件开始处的字节偏移量
- `some_file.seek()`：允许跳转到文件其他字节偏移量的位置

# 异常

- `try-except`
- `Exception`类，可以继承此类来定义新的异常

# json

- `import json`：导入json模块
- `json.dump()`：将json存储到文件中
- `json.load()`：从文件中读取json
- `json.dumps()`：编码成json字符串
- `json.loads()`：把json字符串解析成python数据结构

# 模块和import语句

- 模块仅仅是python代码的一个文件
- `import`可以引用其他模块的代码
- `import module_name`
- `from module_name import function_name`
- `import module_name as mn`：使用别名导入模块
- `from module_name import function_name as fn`：使用别名导入模块的函数

# 包

- 在目录下添加文件：`init.py`，该目录就变成了一个包

# 格式化

python有两种格式化字符串的方式，旧方式和新方式，这两种方式在python 2和python 3中都适用，新方式适用于python 2.6以及以上。

## 旧方式

旧方式的形式为：string % data，其中string是包含待插值的序列。转换类型有如下：

- `%s`：字符串
- `%d`：十进制整数
- `%x`：十六进制整数
- `%o`：八进制整数
- `%f`：十进制浮点数
- `%e`：以科学计数法表示的浮点数
- `%g`：十进制或科学计数法表示的浮点数
- `%%`：文本值%本身

示例：

- `"something %s something" % some_str`
- `"something %s something %s" % (some_str, some_str)`

还可以在%和类型字母之间设置最大宽度、最小宽度、排版以及填充字符等

## 新方式

新方式使用`{}`和`format()`进行格式化，格式如下：

- `'{} {} {}'.format(n, f, s)`
- `'{2} {0} {1}'.format(f, s, n)`可以指定插入的顺序
- `'{n} {f} {s}'.format(n=42, f=7.03, s='string cheese')`：参数可以是字典或者命名变量，格式串中的标识符可以引用这些名称
- `'{0[n]} {0[f]} {0[s]} {1}'.format(some_dict, some_str)`：{0}表示字典，{1}表示字典后面的字符串
- `'{0:d} {1:f} {2:s}'.format(n, f, s)`：指定参数格式
- `'{0:10d} {1:10f} {2:10s}'.format(n, f, s)`：支持设置最小域宽度、最大字符宽、排版等
- `'{0:10.4d} {1:10.4f} {2:10.4s}'.format(n, f, s)`：支持设置精度，小数点后面的数字表示精度，对浮点数表示的时候小数点后的数字个数，对字符串表示的时最大字符个数

# 正则表达式

- `import re`：正则库
- `some_pattern = re.compile('some pattern')`：对模式进行编译
- `some_pattern.match('some_str')`：使用编译好的模式进行匹配
- `search()`：返回第一次成功匹配，如果存在的话
- `findall()`：返回所有不重叠的匹配，如果存在的话
- `split()`：根据pattern将source切分若干段，返回有这些片段组成的列表
- `sub()`：还需要一个额外的参数replacement，会把source中所有匹配的pattern改成replacement

# 系统os模块

- `open()`：打开或创建文件
- `import os`：导入系统模块
- `os.path.exsits('path')`：检查文件是否存在
- `os.path.isfile(name)`：检查是否为文件
- `os.path.isdir(name)`：检查是否为目录
- `os.path.isabs(name)`：检查是否为绝对路径名
- `os.rename(name, new name)`：重命名文件
- `os.link()`：创建硬链接
- `os.symlink()`：创建符号链接
- `os.path.islink()`：检查是文件还是符号链接
- `os.chmod()`：修改权限
- `os.chown()`：修改所有者
- `os.path.abspath()`：获取绝对路径
- `os.path.realpath()`：获取符号链接的路径名
- `os.remove()`：删除文件
- `os.mkdir()`：创建目录
- `os.rmdir()`：删除目录
- `os.listdir()`：列出目录内容
- `os.chdir()`：从一个目录跳转到另一个目录
- `os.getpid()`：获取进程号
- `os.getcwd()`：获取当前工作目录
- `os.getuid()`：获取用户ID
- `os.getgid()`：获取用户组ID
- `import shutil`：导入shutil模块
- `shutil.move(file, other file)`：复制文件
- `import glob`：导入glob模块
- `glob.glob('m*')`：使用Unix shell的规则来匹配文件或者目录

# 日期和时间

- `datetime`模块
- `time`模块
- `calendar`模块
- `dateutil`模块

# 日志

- `logging`模块
- `debug`
- `info`
- `warn`
- `error`
- `critical`

# 其他

- `input()`：程序暂停等待输入