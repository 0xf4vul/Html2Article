# Html2Article

.NETƽ̨�£�һ����Ч�Ĵ�Html����ȡ���ĵĹ��ߡ�  
������ȡ�����˻����ı��ܶȵ���ȡ�㷨��֧�ִ�ѹ����Html�ĵ�����ȡ���ģ�ÿ��ҳ��ƽ����ȡʱ��Ϊ10ms����ȷ�ʵ�95%���ϡ�  
![Html2Article](http://blog.stanzhai.com/images/project/Html2Article.png)

## �������Ŀ֧��Html������ȡ

- **��ʵ����Ŀ�е�Html2Article.cs���Ƶ������Ŀ�С�**
- **���������ռ�Html2Article��**
- **������´��룺**
```C#
// htmlΪ��Ҫ��ȡ��html�ı�
string html = "<html>....</html>";
// article�������Title(����)��PublishDate(��������)����Content(����)��������
Article article = Html2Article.GetArticle(html);
```

## Html2Article��

- **Html2Article������ȡ���ĵĺ�����**
- **Html2Article����˵��**
  AppendMode���Ƿ�ʹ������׷��ģʽ��Ĭ��Ϊfalse������Ϊtrue�Ὣ��������������ı���ӵ����ġ�  
  Depth����������ȣ�Ĭ��Ϊ5�������п�϶�ϴ��ҳ������Ӵ�ֵ��  
  LimitCount���ַ��޶��������������ı������ﵽ�޶�������Ϊ�����������ݣ�Ĭ��Ϊ180���ַ���  
  GetArticle(string html)����Html�ı��л�ȡArticle��

## License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)