==����==
---
# 1. Markdown��ʲô��

**Markdown**��һ��������**�������**�����Դ��ı���ʽ(�׶�����д���׸���)��д�ĵ�����������HTML��ʽ������
**Markdown**Ҳ�������Ϊ����MARKDOWN���Ա�д������ת����HTML���ݵĹ��ߣ������һ��perl�ű�Markdown.pl��

# 2. ˭��������ô��������
����Aaron Swartz��John Gruber��ͬ��ƣ�Aaron Swartz������λ��ȥ�꣨2013��1��11�գ���ɱ,���ſ���һ�����������ĳ���Ա��ά���ٿƶ����Ľ����ǣ��������ʦ�����ҡ�������֯�ߡ���������ҡ�ά���ٿ��ˡ�

���������������ݵ�����������

**14��**����RSS 1.0����׼���ƶ���   
**2004**�����˹̹����֮����ѧ��   
**2005**�괴��Infogami��֮����Reddit�ϲ���Ϊ��ϻ��ˡ�   
**2010**�괴������ᣨDemand Progress�������������ֹ������淨����SOPA��������ո��᰸��Ȼ�����ء�   
**2011**��7��19�գ��򱻿ش�MIT��JSTOR����480��ƪѧ�����Ĳ��������ʽ�ϴ������类����
2013��1����ɱ������

# 3. ΪʲôҪʹ������

�����׶����������������д���﷨�򵥣����׸��Ĵ��ı������������ż��������Ӱ�ӡ�
����HTML������ת��ΪHTML��ʽ������
��ƽ̨ʹ�á�
Խ��Խ�����վ֧��Markdown��
��������������֯��ĵ����ʼ�����Markdown-here, Airmail��
����Word���Ҳ�������ģ���

# 4. ��ôʹ�ã�

���������չ��Markdown���﷨���Լ򵥵����㰮�����֡�

�ϻ�̫�࣬�������ģ�Markdown�﷨��Ҫ��Ϊ���¼��󲿷֣� **���⣬���䣬�������ã��������飬ǿ�����б��ָ��ߣ����ӣ�ͼƬ����б�� \������'`'**��

4.1 ����
---------------
������ʽ��   
1��ʹ��`=`��`-`���һ���Ͷ������⡣

>һ������   
`=========`   
��������   
`---------` 

The results above show that: 

һ������   
===
��������
---

2��ʹ��#���ɱ�ʾ1-6�����⡣

> \# һ������   
\## ��������   
\### ��������   
\#### �ļ�����   
\##### �弶����   
\###### ��������   

The results above show that:
> 
# һ������   
## ��������   
### ��������   
#### �ļ�����   
##### �弶����   
###### ��������  

4.2 ����
------------
�����ǰ��Ҫ�п��У���ν�Ŀ�����ָû���������ݡ������ڶ���ǿ�ƻ��еķ�ʽ��ʹ���������Ͽո���ϻس��������л���ʡ�Իس�����

The results above show that:   
> 1.��һ������пո��лس���  
2.��һ��һ��������  
3.��һ��û����
4.��һ��Ӧ�ø�����һ�����  

4.3 ��������
---------
�ڶ����ÿ�л���ֻ�ڵ�һ��ʹ�÷���>,����ʹ�ö��Ƕ�����ã��磺

>\> ��������  
\>> Ƕ������

The results above show that:
> ��������  
>> Ƕ������

4.4 ��������
-----
��������Ľ�������ÿ�м���4���ո����һ���Ʊ������ͬд����һ��������
��ͨ���䣺   
void main()  
{   
printf("Hello, Markdown.");   
}   

�������飺  

    void main()
    {
    printf("Hello, Markdown.");
    }

ע��:��Ҫ����ͨ����֮����ڿ��С�

4.5 ǿ��
-------
��ǿ����������ֱ����*����_���磺

*б��*��_б��_  
**����**��__����__  

4.6 �б�
-----------
ʹ��`��`��`+`����`-`��������б���:
>-��+*�� ��һ�� -��+*�� �ڶ��� - ��+*��������   

**ע��**����Ǻ���������һ���ո���Ʊ�������������������У������ǰ������֮����ڿ��С�

The results above show that:   
>- ��һ��    
>- �ڶ���    
>- ������

�����б�ı�Ƿ�ʽ�ǽ������ķ��Ż�������,������`.`���磺
The results above show that:   
>1. ��һ��
>2. �ڶ���
>3. ������

4.7 �ָ���
---
�ָ����ʹ�þ�������������`*`��������ʹ��`-`��`_`��

The first   
\***   
The Second   
\---   
The Third   
\______   

**The results above show that:  ** 

The first
***
The Second
---
The Third
______

4.8 ����
---
���ӿ�����������ʽ���ɣ�����ʽ�Ͳο�ʽ��
����ʽ��

>`[younghz��Markdown��](https:://github.com/younghz/Markdown "Markdown")��`

**The results above show that:  ** 

[younghz��Markdown��](https:://github.com/younghz/Markdown "Markdown")��

�ο�ʽ��

>`[younghz��Markdown��1][1]     
[younghz��Markdown��2][2]
[1]:https:://github.com/younghz/Markdown "Markdown"
[2]:https:://github.com/younghz/Markdown "Markdown"`

**The results above show that:  ** 

[younghz��Markdown��1][1]   
[younghz��Markdown��2][2]

[1]:https:://github.com/younghz/Markdown "Markdown"
[2]:https:://github.com/younghz/Markdown "Markdown"


ע�⣺������
```
[1]:https:://github.com/younghz/Markdown "Markdown"
```
�������������С�

4.9 ͼƬ
----
���ͼƬ����ʽ���������ƣ�ֻ�������ӵĻ�����ǰ����һ��`��`��   
>`![image](https://github.com/1plusc/Resource/blob/master/img/forexample.jpg?raw=true) `

**The results above show that:  ** 

![image](https://github.com/1plusc/Resource/blob/master/img/forexample.jpg?raw=true)  

4.10 ��б��`\`
---
�൱�ڷ�ת�����á�ʹ���ų�Ϊ��ͨ���š�   

4.11 ����'`'
---
�𵽱�����á��磺   
>\`ctrl+a`

**The results above show that:  ** 

>`ctrl+a`

# 5. ��˭���ã�
---
Markdown��ʹ���ߣ�

GitHub   
����   
Stack Overflow   
Apollo   
Moodle   
