# flink_datagen

通过flink把文件的数据灌到kafka里,打包后，kafka拉起后，可以通过以下命令进行
java -classpath {jar.path} myflink.SourceGenerator --input {inputfile.path} --output kafka localhost:9092 --speedup 2000
