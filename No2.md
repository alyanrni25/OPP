# OPP Jam Tangan
## Program

```c++
#include <iostream>
using namespace std;

class JamTangan {
public:
    string merk;
    string model;
    string warna;
    float harga;

    void tampilkan_info() {
        cout << "Merk: " << merk << endl;
        cout << "Model: " << model << endl;
        cout << "Warna: " << warna << endl;
        cout << "Harga: Rp" << harga << endl;
    }

    float hitung_harga_diskon(float persen) {
        return harga - (harga * persen / 100);
    }

    void tampilkan_harga_diskon(float persen) {
        float harga_diskon = hitung_harga_diskon(persen);
        cout << "Harga setelah diskon " << persen << "%: Rp" << harga_diskon << endl;
    }
};

int main() {
    JamTangan jam1;
    jam1.merk = "Rolex";
    jam1.model = "Submariner";
    jam1.warna = "Hitam";
    jam1.harga = 15000000;

// Contoh diskon 10%
    jam1.tampilkan_info();
    jam1.tampilkan_harga_diskon(10);  
    

    JamTangan jam2;
    jam2.merk = "Seiko";
    jam2.model = "Prospex";
    jam2.warna = "Biru";
    jam2.harga = 5000000;

// Contoh diskon 15%
    jam2.tampilkan_info();
    jam2.tampilkan_harga_diskon(15);  

    return 0;
}
```
# Capture Hasil Running
[Screenshot 2024-05-20 090319](https://github.com/alyanrni25/OPP/assets/156888432/2f35b1bc-be15-43ad-9b07-16b550b813af)
