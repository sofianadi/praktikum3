# praktikum3
## Latihan1.cpp 

**Alur Argoritma**
1. Mendeklarasikan Variable int a,max,n sebagai varible input
2. membaca input dari key board  cin >> n
3. membandikan nilain variable **A** dengan Variable **max** jika **a>max**  
4. Bandingkan kembali kedua variabel sebanyak jumlah **n** atau bilangan yang di inputkan,,
5. sampai menemukan hasil **a=max** maka cetaklah.
6. print bilangan terbesar dari semua bilangan yang di inputkan.

**flowchart Program**
![flowchart](https://raw.githubusercontent.com/sofianadi/praktikum3/master/latihan1%20ss.jpg)

**CODE PROGRAM**
```c++
#include<iostream>
using namespace std;
int main ()
{
    int i = 0;
    int max=0;
    int n,a;
    cout << "masukan jumlah bilagan :" ;
    cin >> n;

    for (i;i<n;i++) {
        cout << "masukan bilangan ke-" << i+1 << ":" ;
        cin >> a;

        if (max<a)
            max = a;

    }
    cout << "bilangan terbesar adalah: " << max << endl;
}
```
**HASIL**
![img] (https://raw.githubusercontent.com/sofianadi/praktikum3/master/hasil%20latihan1.png)

## Latihan2.cpp 

**Alur Argoritma**
1. Mendeklarasikan Variable int A,B,C sebagai varible input
2. membaca input dari key board  cin >> A >> B >> C
3. membandikan nilain variable **A** dengan Variable **B** jika A lebih kecil dari pada B  
4. Bandingkan kembali variabel B dengan variabel C  
5. Jika kondisi **true** Maka cetaklah bilangan secara berurutan dari yang terkecil-terbesar yaitu **A,B,C**
6. jika kondisi **false** Bandingkan kembali Variabel A dengan variabel C jika A lebih kecil dari C
7. Jika kondisi **true** Maka cetaklah bilangan secara berurutan dari yang terkecil-terbesar yaitu **A,C,B**
8. Jika kondisi **false** Maka cetaklah bilangan secara berurutan dari yang terkecil-terbesar yaitu **C,A,B**
9. Kemudian jika A lebih kecil dari C.

10.Jika kondisi **true** Maka cetaklah bilangan secara berurutan dari yang terkecil-terbesar yaitu **B,A,C**

11.jika kondisi **false** Bandingkan kembali Variabel B dengan variabel C jika B lebih kecil dari C.

12.Jika kondisi **true** Maka cetaklah bilangan secara berurutan dari yang terkecil-terbesar yaitu **B,C,A**

13.Jika kondisi **false** Maka cetaklah bilangan secara berurutan dari yang terkecil-terbesar yaitu **C,B,A**

14.END.


** Flowchart Program**
![flowchart](https://raw.githubusercontent.com/sofianadi/praktikum3/master/latihan2%20ss.jpg)

**CODE PROGRAM**
```c++
#include <iostream>

using namespace std;

int main()
{
    int A,B,C;
    cout<<"MASUKAN BILANGAN 1: ";
    cin>> A;
    cout<<"MASUKAN BILANGAN 2: ";
    cin>> B;
    cout<<"MASUKAN BILANGAN 3: ";
    cin>> C;

    if (A<B){
      if (B<C)
            cout<< "Bilangan Terbesar Adalah:" << A << ","<< B <<","<< C << endl;
    else
        if (A<C)
            cout << "Bilangan Terbesar Adalah: " << A << ' '<< C << ' '<< B << endl;
        else cout << " Bilangan Terbesar Adalah: " << C << ' '<< A << ' '<< B << endl;
    }else {
    if (A<C)
        cout << " Bilangan Terbesar Adalah: " << B << ' '<< A << ' ' << C << endl;
    else
        if (B<C)

        cout<< "Bilangan terbesar Adalah: " << B << ' ' << C << ' ' << A << endl;
    else
        cout << " Bilangan Terbesar Adalah: " << C << ' '<< B << ' '<< A << endl;
    }


}
```
**HASIL**
![img](https://raw.githubusercontent.com/sofianadi/praktikum3/master/hasil%20latihan2.png)

## Latihan3.cpp 

**Alur Argoritma**
1. Mendeklarasikan Variable int A,B,C sebagai varible input
2. membaca input dari key board  cin >> A >> B >> C
3. membandikan nilain variable **A** dengan Variable **B** jika sama,  
4. Bandingkan kembali variabel A dengan variabel C  
5. Jika kondisi **true**/ ketiga variabel sama Maka cetaklah  **SEGITIGA SAMA SISI **
6. jika **false**/ jika hanya dua yang sama Maka cetaklah **SEGITIGA SAMA KAKI**
7. Dan jika Variavel A Sama dengan variabel C, jika kondisi *true** kama cetaklah **SEGITIGA SAMA KAKI**
8. jika kondisi **false** samakan kembali variabel C dengan Variabel B, jika kondisi **true** cetaklah **SEGITIGA SAMA KAKI**
9. jika kondisi **false** Cetaklah **SEGITIGA SEMBARANG**

10.END


**Flowchart Program**
![flowchart](https://raw.githubusercontent.com/sofianadi/praktikum3/master/latihan3%20ss.jpg)

**CODE PROGRAM**
```c++
#include<iostream>
using namespace std;

int main()
{
    int A,B,C;

    cout<<"BILANGAN 1: ";
    cin>> A;
    cout<<"BILANGAN 2: ";
    cin>> B;
    cout<<"BILANGAN 3: ";
    cin>> C;
    if (A==B)
    {
        if (A==C)
            cout << "HASILNYA ADALAH " << "SEGITIGA SAMA SISI";
        else
            cout << "HASILNYA ADALAH " << "SEGITIGA SAMA KAKI";
    }else{
    if (A==C)
        cout << "HASILNYA ADALAH " << "SEGITIGA SAMA KAKI";
    else
    {
        if (C==B)
            cout << "HASILNYA ADALAH " << "SEGITIGA SAMA KAKI";
        else
            cout << "HASILNYA ADALAH " << "SEGITIGA SEMBARANG";
    }
    }
}
```

**HASIL**
![img](https://raw.githubusercontent.com/sofianadi/praktikum3/master/hasil%20latihan3.png)