# pratikum04

*Latihan1 

#Membuat program penjualan barang

```
Alur algoritmanya.
	-Mendeklarasikan int kode, N, jumlah, banyak
	-Mendeklarasikan long int total,diskon,akhir, bayar, harga,duit,kembalian
	-Mendeklarasikan variabel N sebagai banyak barang yang dibeli.
	-Mendeklarasikan variabel kode sebagai kode barang
	-mendeklarasikan variabel jumlah sebagai pengulang bnyaknya pembelian
	-mendeklarasikan variabel banyak sebagai nilai inputan 
	-Mendeklarasikan variabel total sebagai penentu harga sesuai banyaknya barang yang dipesan
	-Mendeklarasikan variabel diskon sebagai potongan harga
	-mendeklarasikan variabel akhir sebagai penentu pembayaran setelah dikurangi diskon
	- mendeklarasikan variabel bayar sebagai penentu banyaknya pembayaran
	-mendeklarasikan variabel harga sebagai penentu harga barang
	-mendeklarasikan variael duit sebagai inputan
	-mendeklarasikan variabel kembalian sebagai penentu uang kembalian.
	-membuat perulangan untuk banyaknya pembelian.
		for(jumlah=1;jumlah<=banyak;jumlah++)
	-membuat perbandingan untuk menentukan diskon dalam setiap pembelian.
```

```C++

if((bayar>1000000)){
		diskon = bayar*0.10;
		cout<<"\nKamu Dapat Diskon 10%\t";
		}else
   		 if((bayar>=501000)&& (bayar<=1000000)){
		diskon = bayar*0.05;
		cout<<"\nKamu Dapat Diskon 5%\t";
		}else
 		   if((bayar<501000)){
		diskon = 0;
		cout<<"\nKamu Dapat Diskon 0%\t";
		}
		else {
		diskon = 0;
		}
```

#Berikut kode lengkapnya

```
#include <iostream>

using namespace std;

int main()
{
    char pembelian;
int kode, N, jumlah, banyak;
long int total,diskon,akhir, bayar, harga,duit,kembalian;
atas:
cout<<" ===================FACHMI EKA PANGESTU ELEKTRONIK===================\n";
cout<<"\n";
cout<<"                HARGA YANG TERJANGKAU & KUALITAS TERJAMIN\n";
cout<<"\n";
cout<<" ===========================DAFTAR BARANG===========================\n";
cout<<" 1.  Meja Makan\n";
cout<<" 2.  Dispenser\n";
cout<<" 3.  TV LED\n";
cout<<" 4.  DVD Player\n";
cout<<" 5.  Senter\n";
cout<<" 6.  Lampu Emegeny\n";
cout<<" 7.  Setrika\n";
cout<<" 8.  Lampu Philips\n";
cout<<" 9.  Terminal kuningan\n";
cout<<" 10. Lampu Hias\n";
cout<<" 11. Ac Portable Trends\n";
cout<<" ===================FACHMI EKA PANGESTU ELEKTRONIK===================\n";
cout<<"\n";
cout<<"Jumlah Barang Yang Dipesan = ";
cin>>banyak;
jumlah=1;
bayar=0;
for(jumlah=1;jumlah<=banyak;jumlah++)
{ulang:
 cout<<" \n\nMasukan Kode Barang = ";
cin>>kode;
cout<<"\n";
    if (kode==1)
{
    cout<<" Nama Barang     = Meja Makan\n";
    cout<<" Harga           = Rp. 180000,-\n";
    cout<<" Jumlah Barang   = ";
    cin>>N;
    harga=180000;
    total=harga*N;
    cout<<" Total Harga     = Rp"<<total;
    cout<<"\n";
}
else
    if (kode==2)
{
    cout<<" Nama Barang     = Dispenser\n";
    cout<<" Harga           = Rp. 150000,-\n";
    cout<<" Jumlah Barang   = ";
    cin>>N;
    harga=150000;
    total=harga*N;
    cout<<" Total Harga     = Rp"<<total;
    cout<<"\n";
}
else
    if (kode==3)
{
    cout<<" Nama Barang     = TV LED\n";
    cout<<" Harga           = Rp. 3000000,-\n";
    cout<<" Jumlah Barang   = ";
    cin>>N;
    harga=3000000;
    total=harga*N;
    cout<<" Total Harga     = Rp"<<total;
    cout<<"\n";
}
else
    if (kode==4)
{
    cout<<" Nama Barang      = DVD Player\n";
    cout<<" Harga            = Rp. 300000,-\n";
    cout<<" Jumlah Barang    = ";
    cin>>N;
    harga=300000;
    total=harga*N;
    cout<<" Total Harga      = Rp"<<total;
    cout<<"\n";
}
else
    if (kode==5)
{
    cout<<" Nama Barang     = Senter\n";
    cout<<" Harga           = Rp. 50000,-\n";
    cout<<" Jumlah Barang   = ";
    cin>>N;
    harga=50000;
    total=harga*N;
    cout<<" Total Harga     = Rp"<<total;
    cout<<"\n";
}
else
    if (kode==6)
{
    cout<<" Nama Barang     = Lampu Emegeny\n";
    cout<<" Harga           = Rp. 80000,-\n";
    cout<<" Jumlah Barang   = ";
    cin>>N;
    harga=80000;
    total=harga*N;
    cout<<" Total Harga     = Rp"<<total;
    cout<<"\n";
}
else
    if (kode==7)
{
    cout<<" Nama Barang     = Setrika\n";
    cout<<" Harga           = Rp. 150000,-\n";
    cout<<" Jumlah Baran    = ";
    cin>>N;
    harga=150000;
    total=harga*N;
    cout<<" Total Harga     = Rp"<<total;
    cout<<"\n";
}
else
    if (kode==8)
{
    cout<<" Nama Barang     = Lampu Philips\n";
    cout<<" Harga           = Rp. 30000,-\n";
    cout<<" Jumlah Barang   = ";
    cin>>N;
    harga=30000;
    total=harga*N;
    cout<<" Total Harga     = Rp"<<total;
    cout<<"\n";
}
else
    if (kode==9)
{
    cout<<" Nama Barang     = Terminal kuningan\n";
    cout<<" Harga           = Rp. 25000\n";
    cout<<" Jumlah Barang   = ";
    cin>>N;
    harga=25000;
    total=harga*N;
    cout<<" Total Harga     = Rp"<<total;
    cout<<"\n";
}
else
    if (kode==10)
{
    cout<<" Nama Barang     = Lampu Hias\n";
    cout<<" Harga           = Rp. 15000\n";
    cout<<" Jumlah Barang   = ";
    cin>>N;
    harga=15000;
    total=harga*N;
    cout<<" Total Harga     = Rp"<<total;
    cout<<"\n";
}
else
    if (kode==11)
{
    cout<<" Nama Barang     = Ac Portable Trends\n";
    cout<<" Harga           = Rp. 2400000\n";
    cout<<" Jumlah Barang   = ";
    cin>>N;
    harga=2400000;
    total=harga*N;
    cout<<" Total Harga     = Rp" << total;
    cout<<"\n";
}
else
{
    cout<<"-Invalid Number-\a";
goto ulang;
}
bayar=bayar+total;
}
    cout<<"\nTotal Bayar\t\t        = Rp"<<bayar<<",-";
    cout<<"\n\n\Masukan Pembayaran  = Rp";cin>>duit;
if((bayar>1000000)){
diskon = bayar*0.10;
cout<<"\nKamu Dapat Diskon 10%\t";
}else
    if((bayar>=501000)&& (bayar<=1000000)){
diskon = bayar*0.05;
cout<<"\nKamu Dapat Diskon 5%\t";
}else
    if((bayar<501000)){
diskon = 0;
cout<<"\nKamu Dapat Diskon 0%\t";
}
else {
diskon = 0;
}
akhir       =bayar-diskon;
kembalian   =duit-akhir;

cout<<"\nKamu Dapat Diskon\t  = Rp"<<diskon<<",-";
cout<<"\nCash Back\t          = Rp"<<kembalian<<",-";
cout<<"\n\n\t\t\t(((( ===== TERIMA KASIH ===== ))))";
cout<<"\n\n\n\n\nPembelian Baru [y/t] ";cin>>pembelian;
if (pembelian=='y'||pembelian=='Y')
goto atas;
else
cout<<"\n\n\t\t\tProgram Logging Off....";
}

```

#Berikut flowchartnya

![img](https://github.com/fahmieka21/pratikum04/blob/master/flowchart.png)


#Berikut Hasil Run Nya

#Discount 0%

![img](https://github.com/fahmieka21/pratikum04/blob/master/hasillatihan1.png)
![img](https://github.com/fahmieka21/pratikum04/blob/master/hasillatihan2.png)


#Discount 5%

![img](https://github.com/fahmieka21/pratikum04/blob/master/hasillatihan3.png)
![img](https://github.com/fahmieka21/pratikum04/blob/master/hasillatihan4.png)


#Discount 10%

![img](https://github.com/fahmieka21/pratikum04/blob/master/hasillatihan5.png)
![img](https://github.com/fahmieka21/pratikum04/blob/master/hasillatihan6.png)