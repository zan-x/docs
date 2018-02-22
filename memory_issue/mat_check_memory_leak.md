# MAT

1. 通过Android Device Monitor获取hprof文件
2. 通过Android tools中的hprof对上面获取到的hprof文件进行转换：hprof old.hprof new.hprof
3. 在MAT中导入hprof文件
4. 打开Histogram，可以通过名字对未是否的对象就行查询
5. 右键指定的对象，Merge shortest path to gc roots -> exclude all phantom/weak/soft etc. references
6. 可以看到持有改对象的引用
