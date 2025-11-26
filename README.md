## <img width="952" height="483" alt="image" src="https://github.com/user-attachments/assets/87e518d9-fb40-488b-b870-1eddc779d91c" />
```
#include <iostream>
#include <string>
#include <windows.h>
using namespace std;

int main() {
    system("color C3");
    SetConsoleCP(1251);
    SetConsoleOutputCP(1251);
  
    string last_name;
    cout << "Введіть прізвище: ";
    getline(cin, last_name);

    string first_name;
    cout << "Введіть ім'я: ";
    getline(cin, first_name);

    int age;
    cout << "Введіть вік: ";
    cin >> age;

    cin.ignore();

    string city;
    cout << "Введіть місце проживання: ";
    getline(cin, city);

    cout << "\n--- Результат ---\n";
    cout << "Мене звати " << first_name << " " << last_name << endl;
    cout << "Мені " << age << " років" << endl;
    cout << "Я живу в " << city << endl;

    return 0;
}

```
