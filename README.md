## Perbedaan Antara MVC dan Clean Architecture
### Untuk MVC memiliki beberapa karakteristik yang membedakan dengan clean architecture yaitu: 
1. Konsep dasar dari MVC memiliki Pola yang memisahkan logika bisnis, tampilan, dan pengontrol dalam aplikasi.
2. Fokus utama dari MVC yaitu ada pada pemisahan antara Model (data), View (tampilan), dan Controller (penghubung logika dengan tampilan).
3. Strucktur lapisan nya sesuai dengan namanya yaitu terdiri dari Model, View, Controller.
4. terdapat ketergantungan yang terjadi antara View dan Controller yang sering kali bergantung pada Model sehingga bisa menyebabkan ketergantungan langsung pada framework.
5. Kegunaannya lebih sering digunakan pada aplikasi berbasis UI, seperti web dan mobile apps.
6. Testing bisa lebih sulit karena masih ada ketergantungan antara komponen.

### Untuk Clean Architecture memiliki beberapa karakteristik yang membedakan dengan MVC yaitu: 
1. Arsitektur perangkat lunak yang bertujuan untuk membuat kode lebih fleksibel, terstruktur, dan mudah diuji.
2. Pemisahan antara lapisan bisnis, domain, dan infrastruktur agar kode lebih terorganisir dan scalable.
3. memiliki 4 lapisan utama yang terdiri dari Entities (Domain), Use Cases (Bisnis), Interface Adapters (Presentasi), dan Frameworks & Drivers (Infrastruktur).
4. Memisahkan logika bisnis dari infrastruktur, sehingga lapisan inti (Domain & Use Cases) tidak bergantung pada teknologi eksternal.
5. Cocok untuk aplikasi besar dan kompleks yang membutuhkan skalabilitas tinggi.
6. Mudah diuji karena lapisan bisnis terpisah dari infrastruktur dan framework.

dari perbedaan tersebut dapat disimpulkan bahwa kedua hal ini berbeda dalama segi: 
1. kegunaannya
2. Fokus Utama
3. Strukturnya
4. ketergantungannya
5. kemudahannya dalam melakukan testing

