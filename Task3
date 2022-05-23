#include <iostream>
#include <fstream>
using namespace std;

int main() {
    system("chcp 65001");

    string line;

    ifstream fin("practice.txt");
    int n;
    cout << "Введите чисо строк, которое нужно прочитать из файла:\n";
    cin >> n;
    for (int i = 1; i <= n; ++i){
        getline(fin, line);
        {
            cout << line << endl;
        }
    }
    
    fin.close();

    return 0;
}

#include <iostream>
#include <fstream>
using namespace std;

int main() {
    system("chcp 65001");

    int n = 1000;
    
    char* buffer = new char[n+1]; buffer[n]=0;
    ifstream file("practice.txt");

    file.read(buffer,n);
    cout << buffer;
    file.close();

    return 0;
}
