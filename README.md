# Progam-Bank-Sampah
sistem pengelolaan bank sampah
Deklarasi:
Login pilihan 1 (username dan pass) : string
Karakter pada ‘Input’ dan ‘Print’ : string
Pilih sampah, berat : int
Deskripsi:
strat
print("Selamat Datang di Zero Waste Indonesia!")
saldo=[]
berat=[]
x = 0
while x!=1:
print("Login Sebagai: ")
print("1. Admin Bank Sampah Kabupaten Rembang")
print("2. Nasabah Bank Kabupaten Rembang")
print("3. Keluar")
pilih = int(input("Masukkan pilihan: "))
if pilih == 1:
#username and passwd = AriqNoor
username = input("Username:")
passwd = input("Password: ")
if username == 'AriqNoor' and passwd == 'AriqNoor':
WRITE("1. Total Tabungan admin ")
WRITE("2. Total Berat sampah yang terkumpul")
pilih = int(input("Pilih: "))
if pilih == 1:
PROSES total = sum(saldo)
print("Tabungan Admin saat ini : ", total)
elif pilih == 2:
bt = sum(berat)
print("Berat sampah yang terkumpul yaitu: ", bt, "Kg")
else:
print("Username atau password anda salah")
elif pilih == 2:
print("1. Harga Sampah")
print("2. Setor Sampah")
pilih = int(input(" Pilih : "))
if pilih == 1:print("")
print("|\tJenis\t|\tHarga/kg\t|")
print("|=======================================|")
print("|\tSampah Kemasan sudah dianyam\t|\tRp.10000\t|")
print("|\tSampah Kemasan sudah digunting\t|\tRp.7000\t|")
print("|\tSampah Kemasan botolan\t|\tRp.5000\t|")
elif pilih == 2:
print("|\tPilih jenis sampah:\t|")
print("|1. \tSampah Kemasan sudah dianyam\t|")
print("|2. \tSampah Kemasan sudah digunting\t|")
print("|3. \tSampah Kemasan botolan\t|")
sampah = int(input("Pilih Jenis Sampah: "))
berat_1 = int(input("Masukkan Berat Sampah Anda (kg):"))
berat.append(berat_1)
if sampah == 1:
saldo_1 = berat_1*10000
saldo.append(saldo_1)
print("Uang Anda Terima sebesar: Rp.",saldo_1)
elif sampah == 2:
saldo_1 = berat_1*7000
saldo.append(saldo_1)
print("Uang Anda Terima sebesar: Rp.",saldo_1)
elif sampah == 3:
saldo_1 = berat_1*5000
saldo.append(saldo_1)
print("Uang yang diterima Anda sebesar: Rp.",saldo_1)
elif pilih == 3:
print("\n========-Terima Kasih Pahlawan Lingkungan
ku!:)-========")
print("\nYakin Ingin Keluar y/t ")
READ pilih = input("")
if pilih=='y' or pilih =='Y':
x = 1
elif pilih =='t' or pilih =='T':
print("")
else:
print("Input salah")
else:
print("Menu Tidak Tersedia")
Selesai

