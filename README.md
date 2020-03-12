# Comp_Practice
//1
#include <iostream>
#include <math.h>

using namespace std;

int main()
{
	setlocale(LC_ALL,"");
	int P, S, a;

	cout <<"Введите периметр квадрата: ";
	cin >> P;
	a = P/4;
	S = a*a;
	cout << "Площадь квадрата равна: " << S << endl;
	system("pause");
	return 0
}
//2
#include <iostream>
using namespace std;


int main()
{
	setlocale(LC_ALL, "RUS");
	int n, k;
	cout << "Введите номер дня недели: ";
	cin >> n;
	cout << "Кол-во дней до Нового Года: ";
	cin >> k;

	while (k)
	{
		if (n == 8) n = 1;
		else n++;
		k--;
	}
	    switch (n)
	{
	case 1:
		cout << "Понедельник"<<endl;
		break;
	case 2:
		cout << "Вторник"<<endl;
		break;
	case 3:
		cout << "Среда"<<endl;
		break;
	case 4:
		cout << "Четверг"<<endl;
		break;
	case 5:
		cout << "Пятница"<<endl;
		break;
	case 6:
		cout << "Суббота"<<endl;
		break;
	case 7:
		cout << "Воскресенье"<<endl;
		break;
	}
	system("pause");
	return 0;

}
//3


#include <iostream>

using namespace std;

int main()
{ 
    int n,x,x2,x3,x1;
    
setlocale(LC_ALL,"");
cout<< "Введите число от 100 до 999: ";
cin>>n;
if( n>=100 && n<=999)
{
x2 = n / 100; // вторая цифра
x3 = n % 10; // третья цифра
x1 = ((n % 100) - x3) / 10; // первая цифра
x = x1 * 100 + x2 * 10 + x3;
cout<<"Начальное число = " << x;
}
else
cout<<"Введено неверное число";
system("pause");
return 0;
}
//4

