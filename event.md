Laravel��event�����ṩһ���򵥵Ĺ۲���ʵ�֣���������Ӧ�ó����ﶩ��������¼����¼���ͨ���������� app/Events Ŀ¼�£������ǵĴ�������򱻱����� app/Handlers/Events Ŀ¼�¡�

1.�����¼�
  laravel���EventServiceProvider�ṩһ������ĵط�ע�����е��¼��������
  
2.�����¼�
  ʹ��Event Facade�������ǵ��¼���
  $response = Event::fire(new PodcastWasPurchased($podcast));
fire ��������һ����Ӧ�����飬������������������Ӧ�ó��������Ҫ��ʲô��Ӧ��