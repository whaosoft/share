0.  以上俩个包都是关于grpc的也不多说了
1.  关于<网路数据采集程序> go语言+pfring(并未上传程式) , go1.5版本正常 在1.5以上版本时出现cgo指针的问题 , 现已修改成功了, 有遇到相同问题的欢迎找我 whaosoft@qq.com
2.  关于go语言 ping的程式< goping > 欢迎大家来指出问题

< 近期将上传modbus的采集器python编写,有配置化页面 >

3.  关于 json2xml xml2json <br/>
XMLSerializer 里的一些坑那<br/>
import net.sf.json.xml.XMLSerializer 可以做 但遇到数组时有bug
<br/> 如下<br/>
```
<Message>
  <mrs a="n1">
    <mr>22</mr>
    <mr>1</mr>
  </mrs>
</Message>
```
原版有问题, 本人对此做了修改 ,大伙可以去试试 
