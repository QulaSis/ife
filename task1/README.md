	��̬���ݰ󶨣�һ��

����Ŀ��
 1.�˽� getter �� setter 
 2.�˽� new

��������

ʵ��һ�� Observer��Ҫ�����£�

 1. �������ֻ���Ƕ��󣬲��������顣
 2. new Observer����һ�������� data ����Ҫ�ܹ����ʵ����ݽ�ȥ�Ķ��� 
 3. ͨ�� data �������Ժ��������Ե�ʱ�򣬾��ܴ�ӡ���Ҳ��Ӧ����Ϣ��

eg:

	let app1 = new Observer(
		{ name: 'youngwind', age: 25 }
	);

	let app2 = new Observer(
		{ university: 'bupt', major: 'computer' }
	);

// Ҫʵ�ֵĽ�����£� 
	app1.data.name // ������� name
	app.data.age = 100; // �������� age���µ�ֵΪ100 
	app2.data.university // ������� university 
	app2.data.major = 'science' // �������� major���µ�ֵΪ science