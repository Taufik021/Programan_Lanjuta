  PROGRAM_JAVA 
  
KATA-KATA MOTIVASI

PENJELASAN TAUFIK

Program sederhana berbasis Java Console ini meminta pengguna untuk memasukkan nama, lalu memberikan pesan motivasi yang membangkitkan semangat.
Program ini menggunakan kelas Scanner untuk menerima input dari pengguna dan menampilkan pesan motivasi di layar.

Fitur Program

Menampilkan tampilan pembuka sederhana (dekorasi dengan tanda "=" dan "-").

Meminta pengguna memasukkan nama.

Menampilkan pesan motivasi personal berdasarkan nama yang dimasukkan.

Kode Program

import java.util.Scanner;

public class ppickk {
public static void main(String[] args) {
Scanner input = new Scanner(System.in);

        System.out.println("===----------===");
        System.out.println("======----======");
        System.out.print("Masukkan Nama: ");
        String nama = input.nextLine();
        // System.out.print("APA YANG TERJADI DI DUNIA INI: ");
        // String dunia = input.nextLine();
        System.out.print("KASI KATA-KATA HARI");
        // String kata = input.nextLine();

        System.out.println("\nSEMANGAT " + nama + "");
        System.out.println("JADIKANLAH UJIAN DI DUNIA ITU MENJADI TEMAN SEMENTAR KAMU");
    }
}

Cara Menjalankan Program
- Simpan kode di atas dengan nama ppickk.java
- Buka terminal atau command prompt di folder tempat file disimpan

Jalankan perintah berikut untuk meng-compile

javac ppickk.java

Setelah berhasil dikompilasi, jalankan program dengan perintah

java ppickk


Masukkan nama kamu ketika diminta, lalu lihat pesan motivasi yang muncul

Contoh Output

===----------===

======----======

Masukkan Nama: TAUFIK

KASI KATA-KATA HARI
SEMANGAT TAUFIK

JADIKANLAH UJIAN DI DUNIA INI MENJADI TEMAN SEMENTAR KAMU

Catatan

Baris komentar // String dunia = input.nextLine(); dan // String kata = input.nextLine(); dapat diaktifkan jika kamu ingin menambahkan input tambahan (misalnya kata motivasi dari pengguna).

Program ini cocok digunakan untuk latihan dasar input-output di Java menggunakan Scanner.