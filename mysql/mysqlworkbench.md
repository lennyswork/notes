[intrinsic column flags] (基本字段类型标识)
- PK: primary key (column is part of a pk) 主键
- NN: not null (column is nullable) 非空
- UQ: unique (column is part of a unique key) 唯一
- AI: auto increment (the column is auto incremented when rows are inserted) 自增
[additional data type flags, depend on used data type] 扩展数据类型标记
 
- BIN: binary (if dt is a blob or similar, this indicates that is binary data, rather than text) 二进制(比text更大的二进制数据)
- UN: unsigned (for integer types, see docs: “10.2. Numeric Types”) 整数
- ZF: zero fill (rather a display related flag, see docs: “10.2. Numeric Types”)值中最有意义的字节总为0，并且不保存。