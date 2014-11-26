Large File Processor (LFP)
===
### 多线程分段处理大文件

 =======================================================

##使用

    <dependency>
        <groupId>com.ecfront</groupId>
        <artifactId>lfp</artifactId>
        <version>1.0</version>
    </dependency>

LFP("文件路径","自定义处理函数",<每次获取文件块大小，可选，默认为300000bytes>)

##示例

        LFP("\tmp\test.txt", {
          lines =>
          lines.foreach(println(_))
        })

=======================================================


### Check out sources
`git clone https://github.com/gudaoxuri/large-file-processor.git`

### License

Under version 2.0 of the [Apache License][].

[Apache License]: http://www.apache.org/licenses/LICENSE-2.0

