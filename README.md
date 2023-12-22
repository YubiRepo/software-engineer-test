
# TECHNICAL TEST

## Diketahui: 
Perusahaan ABCD ingin membuat aplikasi yang memiliki kemampuan untuk mencatat orderan pesanan dari client dengan spesifikasi sebagai berikut.

![WhatsApp Image 2023-12-22 at 15 36 50](https://github.com/YubiRepo/Backend-Test-Dev/assets/62506582/d2b1b30d-04b0-41e4-831f-6d81e618afda)


1. Data Style: informasi perihal product (cukup isi data saja di database, tidak perlu di buat UI nya).

      | Name           | Desc                      |
      |----------------|---------------------------|
      | Hair Punk | Week Style Kekinian            |
      | Yellow Rainbow | Week Style Kidz Zaman Now |
      | Relic Style | Week Style Classic           |

3. Color Method: informasi metode warna (cukup isi data saja di database, tidak perlu di buat UI nya).

    | Name      | Desc                              |
    |-----------|-----------------------------------|
    | Roasted   | Pengolahan warna dengan dibakar   |
    | Boiled    | Pengolahan warna dengan di rebus  |
    | Printed   | Pengolahan warna dengan di print  |
   

4. Color Name Method: informasi prihal identitas warna color method, 1 color method bisa memiliki banyak color name method (cukup isi data saja di database, tidak perlu di buat UI nya).
 
    | Name  | Color Method    |
    |-------|-----------------|
    | Red Classic   | Roasted |
    | Blue Marin    | Roasted |
    | Dark Morron   | Boiled  |
    | Grey Water    | Printed |

5. Sales Order: merupakan informasi pesanan dari client dengan ketentuan sebagai berikut.
    - 1 Sales Order bisa memiliki banyak style
    - Di dalam 1 style bisa memiliki banyak color method.
    - Di dalam 1 color method bisa milih lebih dari satu colorn ame method beserta qty yang dipesan.

## Pertanyaan: 
  Silahkan di buatkan aplikasi berbasis web menggunakan framework Laravel (BE), VUE JS (FE), dan Mysql Sebagai DBMS sesuai spesifikasi dari informasi diatas. untuk membantu pembuatan, berikut dilampirkan mockup interface aplikasi yang akan di buat.

![WhatsApp Image 2023-12-22 at 15 36 50 (1)](https://github.com/YubiRepo/Backend-Test-Dev/assets/62506582/eb68bbb4-7812-4f2b-8512-ec703aa09d9f)
![WhatsApp Image 2023-12-22 at 15 36 50 (2)](https://github.com/YubiRepo/Backend-Test-Dev/assets/62506582/2fc11eb9-3b24-41dd-8aad-4449e124525e)

