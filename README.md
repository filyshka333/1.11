#include <iostream>
using namespace std;
class Krab {
 string name;
public:
 void res()
 {
  cout << "Введите название футбольной команды:  " << name << endl;
  cin >> name;
  cout << "Это чемпион! " <<name << endl;
 }
};
int main()
{
 setlocale(LC_ALL, "Russian");
 Krab k;
 k.res();
 
}
