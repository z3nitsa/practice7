#include <iostream>
#include <fstream>
using namespace std;

int main() {
    system("chcp 65001");
    string s;
    ifstream file("practice.txt");

    for(file >> s; !file.eof(); file >> s)
        cout << s << endl;
    if (file.eof())
        cout << "Достигнут конец файла\n";

    file.close();

    return 0;
}
