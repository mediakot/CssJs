CcsJs-for-Evolution
=====================
Component CssJs for MODX Evolution

��������
----------
�������� ��������� �� ���������� MinifyX ��� MODX EVO, ����� ������ ������ � ������� ������ � ��������. 
- ���������� ������ ����� (���������� �� ���� ���������� ����������) 
- ����������� ������ 
- ���������� ���� ������ � 1. 


��������� 
----------
- ���������� ����� Extras ��� PackageManager
- ������ ���������: ������ �� ������ ����� Assets, ������� 2 �������� js � css � ����� �� ������(istall/assets/snippets)

������ ������
----------


	[!css? &files=`assets/templates/tpl/css/bootstrap.css,
				   assets/js/prettify/prettify.css` 
		   &inline=`body{width:100%}` &parse=`1` &minify=`1`!]

	[!js? &files=`assets/js/jquery-1.8.3.min.js,
				  assets/templates/tpl/js/modernizr.custom.28468.js,
				  assets/js/jquery.validate.js,
				  assets/js/jquery.form.min.js,
				  assets/js/prettify/prettify.js` 
		  &inline=`$("#hide").hide();` &minify=`1`!]

	

��������� ��������
-------
- **files** ������ ������ � CSS �������, ������� ����� �������� � �������� ���� � �����
- **inline** ������ ����� ��� ������ ������� ����� �������� ��� ���������� 
- **minify** - ������� � ���������� ������ 
- **folder** � ����� ����� ��������� ������ ����. �� ��������� assets/cache/
- **parse** ������������ �� MODX ���� � ��������� inline
- **api** ����� ������� ��������. �� ��������� ���������� API �������� � � ������ ��������� ���������� ���� ������ ������� ����������� � ������ head ������ ���-�����. ���� �� ����� API ������� (��� ��������� ���������� ������� ����� �������� ����� ���������), �� ��������� ����� ������ ������� ������ � ���� ������� array('js'=>'���� � ������� JS �������','css'=>'���� � �� ������� CSS �������'); � ������ ���� ����� ���� �� ������� ��� �����-�� ��� ������ �� ����������� �������, �� ���� ������� ������� ����� ����.

