
## ʵ������ͼ�����ϵͳ�������ģ

|ѧ��|�༶|����|
|:---------------:|:------------:|:------------:|
|201510414207|����15-2|����|

### 1.ͼ�����ϵͳ��ͼ

**1.1PlantUMLԴ�����£�**
~~~
@startuml
class �鼮��Ϣ��{
  �鼮����
  ����
  �۸�
  ���
  �������
  �ɽ�����
  SearchBook()
  AddBook()
  DeleteBook()
  UpdateBook()
  BorrowBook()
  ReturnBook()
  RenewBook()
}
class Ԥ����¼{
 Ԥ������
 ������Ϣ
 Reserve()
 GetUserData()
}
class ���ļ�¼{
  �鼮��Ϣ
  ������Ϣ
  getUserData()
  getBookData()
}
class ����{
  ����
  ����֤��
  ���鿨��
  �ѽ�ͼ��
  Ԥ��ͼ��
  ��������
  getUserData()
  UpdataUser()
}
class ͼ�����Ա{
  ְ����
  ����
  Ȩ��
  getLibrarianData()
  changeUserData()
}
class ϵͳ����Ա{
  ְ����
  ����
  Ȩ��
  AddLibrarian()
  UploadLibrarian()
  DeleteLibrarian()
}

�鼮��Ϣ�� "1"--"*" Ԥ����¼:��Ԥ��
Ԥ����¼ "*"--"1" ����:Ԥ��
Ԥ����¼ "*"--"1" ͼ�����Ա:�Ǽ�
���ļ�¼ "*"--"1" ͼ�����Ա:�Ǽ�
���ļ�¼ "*"--"1" ����:����
ϵͳ����Ա "*"--"*" ͼ�����Ա:����
ͼ�����Ա "*"--"*" �鼮��Ϣ��:ά��
@enduml
~~~
**1.2ͼ�����ϵͳ��ͼ���£�**

![](leitu.png)

### 2.ͼ�����ϵͳ����ͼ

**2.1��ͼ�����ͼ**

**2.1.1PlantUMLԴ�����£�**
~~~
@startuml

object �鼮 {
	 	���� = "��Ϣϵͳ���������"
	 	������� = "9787302329824"
	 	�۸� = "45.00Ԫ"
	 	������ = "�廪��ѧ������"
	 	���� = "������"
}
object ���ļ�¼ {
	 	�������� = "2018.4.10"
	 	Ӧ������ = "2018.5.10"
	 	�������� = "2015.4.17"
	 	����ID = "201510414207"
}
�鼮 "1"--"*" ���ļ�¼

@enduml
~~~

**2.1.2��ͼ�����ͼ���£�**

![](tushuduixiang.png)

**2.2��ϵͳ��ɫ����ͼ**

**2.2.1PlantUMLԴ�����£�**
~~~
@startuml

object ͼ�����Ա {
		 ���� = "ͼ�����Ա"
		 ID = "664712473"
		 ���� = "********"
		 ����Ȩ�� = "Librarian"
}
object ϵͳ����Ա {
		 ���� = "ϵͳ����Ա"
		 ���� = "********"
		 ���� = "Administor"
}

object ���� {
	 	���� = "HUI"
	 	����ID = "201510414207"
		�����鼮 = "Java�����ŵ�����"
		����Ȩ�� = "�ɽ���"
}
���� "*"--"*" ͼ�����Ա
ͼ�����Ա "*"--"1" ϵͳ����Ա
@enduml
~~~

**2.2.2��ϵͳ��ɫ����ͼ���£�**

![](jueseduixiangtu.png)
