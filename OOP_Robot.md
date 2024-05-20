# OOP ROBOT
## PROGRAM
```c++
#include <iostream>
using namespace std;

class Robot {
public:
    string nama, mbti;
    int umur;

    void tampilkan_info() {
        cout << "Nama: " << nama << endl;
        cout << "Umur: " << umur << endl;
        cout << "MBTI: " << mbti << endl;
    }
};

int main() {
    Robot prototipe1;

    prototipe1.nama = "Ucil";
    prototipe1.umur = 20;
    prototipe1.mbti = "ISTJ";


    prototipe1.tampilkan_info();

    Robot prototipe2;

    prototipe2.nama = "Molli";
    prototipe2.umur = 10;
    prototipe2.mbti = "IFNJ";

    prototipe2.tampilkan_info();


    return 0;
```

# Capture Hasil Running
![running robot](https://github.com/alyanrni25/OPP/assets/156888432/164ea77b-0807-4bf4-b0e8-c3d3289a8abd)


