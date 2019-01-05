# C-Perkalian-Pecahan

    #include <iostream>

    using namespace std;
    typedef struct pecahan
    {
    int pb;
    int py;
    };

    int main(int argc, char*argv[])
    {
    pecahan P1,P2,P3;

    cout << "\t\t\Pelita bangsa\n\n" << endl;
    cout << "==========================================\n" << endl;
    cout << "Nama : Rafi Alwan Setyawan \nNIM  : 311810325\n" << endl;
    cout << "==========================================\n" << endl;

    cout << "\t     Perkalian Pecahan\n" << endl;

    cout << "Masukkan Pembilang 1  = ";
    cin >> P1.pb;  //Pembilang P1
    cout << "Masukkan Penyebut 1   = ";
    cin >> P1.py;  //Penyebut P1

    cout << "\t      " << P1.pb << endl;
    cout << "\tP1 =  -"<< endl;
    cout << "\t      " << P1.py << endl;

    cout << "\nMasukkan Pembilang 2  = ";
    cin >> P2.pb;  //Pembilang P2
    cout << "Masukkan Penyebut 2   = ";
    cin >> P2.py;  //Penyebut P2

    cout << "\t      " << P2.pb << endl;
    cout << "\tP2 =  -"<< endl;
    cout << "\t      " << P2.py << endl;

    P3.pb = P1.pb*P2.pb; //rumus perkalian pecahan
    P3.py = P2.py*P2.py;

    cout << "==========================================\n" << endl;
    //tampilan P3 = Hasil perkalian
    cout << "\n Hasil P1 X P2" << endl;
    cout << "\t      " << P3.pb << endl;
    cout << "\tP3 =  -" << endl;
    cout << "\t      " << P3.py << endl;

    return 0;
    }
    
Hasil
![img](https://github.com/Rafflesia3/C-Perkalian-Pecahan/blob/master/C++%20Perkalian%20pecahan.png?raw=true)
