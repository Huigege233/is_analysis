### ����������
### �༶��15����2��
### ѧ�ţ�201510414207


- - -
## ����ͼ1�����Լ��ɼ���������
<b>PlantUMLԴ�����£�</b>
```
@startuml
|����|
start
:���ſ���;
#red:���԰��ű�;
|��ʦ|
:����;
split
#red:A��B�Ծ�;
split again
#red:��ӡ������;

|ϵ����|
:����ǩ��;
#HotPink:��ӡ������;
endsplit
|����|
:��ӡ�Ծ�;
#red:�Ծ�;
|ѧ��|
:�μӿ���;
#green:���;
|��ʦ|
fork
    :�ɼ���;
    |����|
    if(�в�����) then(��)
        :���Ų���;
     endif
forkagain
|��ʦ|
    #white:���;
    :װ���浵;
endfork
:��ĩ���̽���;
end

@enduml
```

<b>ҵ������ͼ���£�</b>

![ҵ������ͼ](school.png)

<b>����˵����</b>

1. ���ݲ�ͬ������Ȩ�޷ֳ�������
2. ���񴦰��ſ��Ը������԰��ű�
3. ��ʦ�����Լ�������ӡ����
4. ϵ����ǩ�֣����񴦴�ӡ��
5. ѧ���μӿ���
6. ���Ҹ����ɼ�
7. �����жϳɼ��Ƿ񼰸񣬲����Ų���
8. ��ĩ���̽���


## ����ͼ2���ͻ�ά�޷�������
<b>PlantUMLԴ�����£�</b>
```
@startuml
|�ͻ�|
start
    #red:�������;
|ҵ����|
if(���¿ͻ���) then(��)
    :�Ǽǿͻ���Ϣ;
else(����)
endif
    :���ſ���;
    :�ƶ�����;
|�ͻ�|
if(������) then(��)
    end
else(��)
    #red:ǩ�������ͬ;
endif
|ҵ����|
fork
    :���Ź���;
fork again
    :���Ų���;
end fork
    :��д�ɹ���;
|����|
    #white:��ȡ����;
    #white:���ŷ���;
|�ͻ�|
    #red:���ղ���д�������;
|ҵ����|
    :�����ɹ���;
|������Ա|
    #green:�����տ�;
end
@enduml
```

<b>ҵ������ͼ���£�</b>

![ҵ������ͼ](manage.png)

<b>����˵����</b>
1. �ͻ��������
2. ҵ�����ж��Ƿ����¿ͻ������Ǽǿͻ���Ϣ�����ſ��첢�ƶ�����
3. ���ͻ����⣬��ǩ����ͬ
4. ҵ�������Ź��˺Ͳ��ϣ���д�ɹ���
5. ������ȡ���ϲ����ŷ���
6. �ͻ����ղ�����
7. ҵ���������ɹ���
8. ��������տ�