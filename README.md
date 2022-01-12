/*
	Nama			: Salman Dermawan
	NIM				: 2130511060
	Kelas			: 1B
	Mata Kuliah		: Dasar Pemrograman
	Program Studi	: Teknik Informatika
*/

#include <iostream>
using namespace std;

void premium(){
	int biayaPremium[7] = {15000000, 10000000, 8000000, 15000000, 7000000, 2000000, 5000000};
	int Total = biayaPremium[0] + biayaPremium[1] + biayaPremium[2] + biayaPremium[3] + biayaPremium[4] + biayaPremium[5] + biayaPremium[6];
		
		cout << "---------------------------" << endl;
		cout << "Detail Harga Paket Premium " << endl;
		cout << "---------------------------" << endl << endl;
		cout << "Dekorasi 		: Rp. " << biayaPremium[0] << endl;
		cout << "Make Up Artist 		: Rp. " << biayaPremium[1] << endl;
		cout << "Photo / Video 		: Rp. " << biayaPremium[2] << endl;
		cout << "Catering 		: Rp. " << biayaPremium[3] << endl;
		cout << "Entertainment 		: Rp. " << biayaPremium[4] << endl;
		cout << "Master of Ceremony 	: Rp. " << biayaPremium[5] << endl;
		cout << "WO Team 		: Rp. " << biayaPremium[6] << endl;
		cout << "Total 			: Rp. " << Total << endl;
}

void ketPrem(){
	cout << "					================================" << endl;
	cout << "						  Paket Premium" << endl;
	cout << "					================================" << endl;
	cout << "1. Dekorasi				2. Make Up Artist			3. Photo / Video\n";
	cout << "	- Pelaminan 10 meter			- Rias Pengantin 1 Pasang		- 150 Foto & Album\n";
	cout << "	- Fresh Flower				- Rias Orang Tua & Besan		- 12 R + Figura 2\n";
	cout << "	- Photoboth				- Rias Among Tamu 5 Orang		- Wedding Book\n";
	cout << "	- Pergola				- Rias Pagar Ayu			- Cinematic 5 Menit\n";
	cout << "	- Handbouqet				- Nail Art				- Free Wedding\n";
	cout << "	- Dekor Meja Akad			- Softlense					- 16 R + Figura 2\n";
	cout << "	- Buku Tamu				- 1 Robe Pengantin Putri			- Cinematic 1 Menit\n";
	cout << "	- Welcome Sign									- All FIles in Flash Disk\n";
	cout << "	- Dekor Mobil\n";
	cout << "	- Kotak Uang\n" << endl;
	cout << "4. Catering				5. Entertainment			6. Master of Ceremony\n";
	cout << "	- 4 Menu prasmanan			- 2 Singer Vocal			- 2 Person MC (Male/Female)\n";
	cout << "	- 2 Menu Gubug				- Piano\n";
	cout << "	- 2 Menu Desert				- Guitar\n";
	cout << "	- 1 Snack Jajanan Pasar			- Bass\n" ;
	cout << "						- Cajon\n" << endl;
	cout << "7. WO Team\n";
	cout << "	- 5 Person Team" << endl;
}

void Gold(){
	int biayaGold[7] = {10000000, 8000000, 6000000, 10000000, 5000000, 2000000, 5000000};
	int Total = biayaGold[0] + biayaGold[1] + biayaGold[2] + biayaGold[3] + biayaGold[4] + biayaGold[5] + biayaGold[6];
	
		cout << "---------------------------" << endl;
		cout << "Detail Harga Paket Gold " << endl;
		cout << "---------------------------" << endl << endl;
		cout << "Dekorasi 		: Rp. " << biayaGold[0] << endl;
		cout << "Make Up Artist 		: Rp. " << biayaGold[1] << endl;
		cout << "Photo / Video 		: Rp. " << biayaGold[2] << endl;
		cout << "Catering 		: Rp. " << biayaGold[3] << endl;
		cout << "Entertainment 		: Rp. " << biayaGold[4] << endl;
		cout << "Master of Ceremony 	: Rp. " << biayaGold[5] << endl;
		cout << "WO Team 		: Rp. " << biayaGold[6] << endl;
		cout << "Total 			: Rp. " << Total;
}

void ketGold(){
	cout << "					================================" << endl;
	cout << "						  Paket Gold" << endl;
	cout << "					================================" << endl;
	cout << "1. Dekorasi				2. Make Up Artist			3. Photo / Video\n";
	cout << "	- Pelaminan 7 meter			- Rias Pengantin 1 Pasang		- 100 Foto & Album\n";
	cout << "	- Fresh Flower				- Rias Orang Tua & Besan		- 12 R + Figura 2\n";
	cout << "	- Photoboth				- Rias Pagar Ayu			- Wedding Book\n";
	cout << "	- Dekor Meja Akad			- Nail Art				- Cinematic 5 Menit\n";
	cout << "	- Buku Tamu				- Softlense				- Free Wedding\n";
	cout << "	- Welcome Sign				- 1 Robe Pengantin Putri		- All FIles in Flash Disk\n";
	cout << "	- Kotak Uang\n" << endl;
	cout << "4. Catering				5. Entertainment			6. Master of Ceremony\n";
	cout << "	- 3 Menu Prasmanan 				- 2 Singer Vocal			- 2 Person MC (Male/Female)\n";
	cout << "	- 2 Menu Gubug				- Piano\n";
	cout << "	- 2 Menu Desert				- Guitar\n" << endl;
	cout << "7. WO Team\n";
	cout << "	- 5 Person Team" << endl;
}

void silver(){
	int biayaSilver[7] = {8000000, 6000000, 5000000, 8000000, 4000000, 2000000, 5000000};
	int Total = biayaSilver[0] + biayaSilver[1] + biayaSilver[2] + biayaSilver[3] + biayaSilver[4] + biayaSilver[5] + biayaSilver[6];
	
		cout << "---------------------------" << endl;
		cout << "Detail Harga Paket Silver " << endl;
		cout << "---------------------------" << endl << endl;
		cout << "Dekorasi 		: Rp. " << biayaSilver[0] << endl;
		cout << "Make Up Artist 		: Rp. " << biayaSilver[1] << endl;
		cout << "Photo / Video 		: Rp. " << biayaSilver[2] << endl;
		cout << "Catering 		: Rp. " << biayaSilver[3] << endl;
		cout << "Entertainment 		: Rp. " << biayaSilver[4] << endl;
		cout << "Master of Ceremony 	: Rp. " << biayaSilver[5] << endl;
		cout << "WO Team 		: Rp. " << biayaSilver[6] << endl;
		cout << "Total 			: Rp. " << Total;
}

void ketSilver(){
	cout << "					================================" << endl;
	cout << "						  Paket Silver" << endl;
	cout << "					================================" << endl;
	cout << "1. Dekorasi				2. Make Up Artist			3. Photo / Video\n";
	cout << "	- Pelaminan 4 meter			- Rias Pengantin 1 Pasang		- 100 Foto & Album\n";
	cout << "	- Artificial Flower			- Rias Orang Tua & Besan		- 12 R + Figura 2\n";
	cout << "	- Welcome Sign				- Nail Art				- Cinematic 5 Menit\n";
	cout << "	- Kotak Uang				- Softlense				- All FIles in Flash Diskt\n";
	cout << "						- 1 Robe Pengantin Putri\n" << endl;
	cout << "4. Catering				5. Entertainment			6. Master of Ceremony\n";
	cout << "	- 4 Menu Prasmanan			- 1 Singer Vocal			- 2 Person MC (Male/Female)\n";
	cout << "	- 2 Menu Gubug				- Piano\n";
	cout << "						- Guitar\n" << endl;
	cout << "7. WO Team\n";
	cout << "	- 5 Person Team" << endl;
}

void Customer(){
	string Nama, Lokasi, Bln;
	int Tgl, Tlp;
	
		cout << "---------------------------" << endl;
		cout << "      Format Pemesanan " << endl;
		cout << "---------------------------" << endl << endl; 
		cout << "Nama		: ";
		cin >> Nama >> Nama;
		cout << "Untuk Tanggal	: ";
		cin >> Tgl;
		cin >> Bln;
		cout << "Lokasi		: ";
		cin >> Lokasi;
		cout << "Nomer Telepon	: ";
		cin >> Tlp;
		cout << endl << "Pemesanan Anda akan kami Proses" << endl;
		cout << "Terima Kasih telah mempercayakan kepada A-ONE Wedding Organizer" << endl;
}

int main(){
	int pilih, a;
	char DH, PP, yt, BM;
		cout << "	========================================================================" << endl;
		cout << "				A-ONE Wedding Organizer " << endl;
		cout << "			Kota Sukabumi - Jawa barat " << endl;
		cout << "		Email : aone@wedding.com	Website : www.AoneWO.com " << endl;
		cout << "	========================================================================" << endl;
		cout << endl;
		cout << "SELAMAT DATANG DI A-ONE Wedding Organizer"<< endl << endl; 
		
		paket:
		cout << "Daftar Paket Wedding Organizer : " << endl;
		cout << "1. Paket Premium" << endl;
		cout << "2. Paket Gold" << endl;
		cout << "3. Paket Silver" << endl;
		cout << "Masukan pilihan Paket : ";
		cin >> pilih;
		system("CLS");
	
		do{
		switch(pilih){
			case 1:
				ketPrem();
				cout << endl;
				cout << "Detail harga (y/t) ? ";
				cin >> DH;
				if (DH == 'Y' || DH == 'y'){
				system("CLS");
				premium();
				}else (DH == 'T' || DH == 't');{
				goto PPP;}
					PPP:
					cout << endl << endl;
					cout << "Pilih Paket (y/t) ? ";
					cin >> PP;
				 	if (PP == 'Y' || PP == 'y'){
				 	system("CLS");
				 	Customer();
				 	}else if (PP == 'T' || PP == 't'){
				 	system("CLS");
				 	goto paket;}
			break;
			
			case 2:
				ketGold();
				cout << endl;
				cout << "Detail harga (y/t) ? ";
				cin >> DH;
				if (DH == 'Y' || DH == 'y'){
				system("CLS");
				Gold();
				}else (DH == 'T' || DH == 't');{
				goto PPG;}
					PPG:
					cout << endl << endl;
					cout << "Pilih Paket (y/t) ? ";
					cin >> PP;
					if (PP == 'Y' || PP == 'y'){
				 	system("CLS");
				 	Customer();
				 	}else if (PP == 'T' || PP == 't'){
				 	system("CLS");
				 	goto paket;}
			break;
			
			case 3:
				ketSilver();
				cout << endl;
				cout << "Detail harga (y/t) ? ";
				cin >> DH;
				if (DH == 'Y' || DH == 'y'){
				system("CLS");
				silver();
				}else (DH == 'T' || DH == 't');{
				goto PPS;}
					PPS:
					cout << endl << endl;
					cout << "Pilih Paket (y/t) ? ";
					cin >> PP;
				 	if (PP == 'Y' || PP == 'y'){
				 	system("CLS");
				 	Customer();
				 	}else if (PP == 'T' || PP == 't'){
				 	system("CLS");
				 	goto paket;}
			break;
			
			default:
				cout << "Pilihan yang anda pilih salah" << endl;
				cout << "Kembali ke menu awal (y/t) ? ";
				cin >> BM;
				if (BM == 'Y' || BM == 'y'){
				system("CLS");
				goto paket;
				}else if (BM == 'T' || BM == 't'){
				system("CLS");
				goto end;}
				
				
		} a++;
	} while (a=0);
	end:	
		return 0;
}

