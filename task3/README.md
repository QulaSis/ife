	��̬���ݰ󶨣�����

����Ŀ��
 1.�˽��¼���������

��������

let app2 = new Observer({
    name: {
        firstName: 'shaofeng',
        lastName: 'liang'
    },
    age: 25
});

app2.$watch('name', function (newName) {
    console.log('�ҵ����������˱仯�����������ϱ��ˣ�Ҳ���������ֱ��ˡ�')
});

app2.data.name.firstName = 'hahaha';
// ������ҵ����������˱仯�����������ϱ��ˣ�Ҳ���������ֱ��ˡ�
app2.data.name.lastName = 'blablabla';
// ������ҵ����������˱仯�����������ϱ��ˣ�Ҳ���������ֱ��ˡ�