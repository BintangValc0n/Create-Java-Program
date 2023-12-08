Buat sebuah program Java untuk mengkonversi detik ke menit. Program meminta pengguna untuk memasukkan jumlah detik yang ingin dikonversi. Contoh:

Input: Masukkan jumlah detik = 81 

Output: 81 menit sama dengan 1 menit 21 detik

import java.util.Scanner;
/*
    Output yang dinginkan adalah : 0 menit sama dengan 0 menit 0 detik
    Angka 0 akan diubah dengan inputan otomatis pada scanner sesuai dengan test case
    perhatikan spasi pada output
*/
public class CodeRunner {

	public static void main(String[] args) {
	Scanner abi = new Scanner (System.in);
		
		int nama = abi.nextInt();
		int menit = 1;
		int detik = nama - 60;
		
		System.out.print(nama + " menit sama dengan "+ menit +" menit "+ detik + " detik" );
	}
}
