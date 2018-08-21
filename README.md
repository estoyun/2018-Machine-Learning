### ���� ���� ���� �ΰ����� ����Ʈ����
���� ������ �����ϴ� �ΰ����� ����Ʈ�����Դϴ�.

### �ý��� ������
![image](https://user-images.githubusercontent.com/16822641/44392472-38565380-a56d-11e8-9505-9b691522420e.png)

### Demo Web Site
![image](https://user-images.githubusercontent.com/16822641/44392523-60de4d80-a56d-11e8-9ad2-b3fd42e5cef4.png)

### ���� ����
* [���û ���� ��� �� ������](https://data.kma.go.kr/climate/StatisticsDivision/selectStatisticsDivision.do?pgmNo=158) : ���û ������ ���� ä�� ���ݿ� ������ ��ġ�� ������ �м��ϱ� ���� �����Ͽ����ϴ�.
* [���� ���� ����](https://www.kamis.or.kr/customer/price/retail/period.do?action=monthly&yyyy=2018&period=10&countycode=&itemcategorycode=200&itemcode=211&kindcode=&productrankcode=&convert_kg_yn=N) : �������� ���� ���� ���� ������ �м��ϱ� ���� �����Ͽ����ϴ�.
* [�ð迭��ġ�Է� ��ġ���� �� ������](https://tykimos.github.io/2017/09/09/Time-series_Numerical_Input_Numerical_Prediction_Model_Recipe/) : �ð迭(Time-Series Analysis) ���� �� �н��ڷ�� �����Ͽ����ϴ�.

### ���� ���� ��ɾ�
```
# �ö�ũ �� ���� ������ �̵��մϴ�.
cd "Flask Web Server"

# �� ������ �����մϴ�.
python server.py
```

### ���̽� ������ �н� �� ���� ��ɾ�
```
# ���̽� ������ �̵��մϴ�.
cd "Python Software"

# ����(Excel) ���Ϸ� �н��� �����մϴ�.
python offline.py

# (�ɼ�) �н��� �����͸� Ȯ���մϴ�.
python "predict test.py"
>> ��� �µ�: -2.7
>> ���� �µ�: -6.6
>> �ְ� �µ�: 2.0
>> ������:  0.1
[2000.2086]

# ���Ŀ� ������ �� ������ �� ������ model ������ �ٿ��ֱ� �ϸ� ����˴ϴ�.
```
