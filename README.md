# algoritma
algoritma dasar pemrograman bahasa python

#program rumus bangun datar

nama = str(input("Nama : "))
print("HI!", nama, "hope u have a nice day :)")

def rumus() :
    print("mau menghitung apa ? ")
    print("1. luas lingkaran ")
    print("2. luas persegi ")
    print("3. keliling persegi")
    print("4. luas persegi panjang")
    print("5. keliling persegi panjang")

rumus()
pilihan = int(input("masukkan nomor yang ingin dihitung "))
if pilihan == 1:
    phi = 3.14
    r = float(input("masukkan jari-jari lingkaran "))
    luas = phi * r * r
    print("luas lingkaran adalah ", luas, type(luas))

elif pilihan == 2:
    sisi = float(input("masukkan sisi persegi "))
    luas = sisi * sisi
    print("luas persegi adalah ", luas, type(luas))

elif pilihan == 3:
    sisi = float(input("masukkan sisi persegi "))
    keliling = sisi * 4
    print("keliling persegi adalah ", keliling, type(keliling))

elif pilihan == 4:
    p = float(input("masukkan ukuran panjangnya "))
    l = float(input("masukkan ukuran lebarnya "))
    luas = p * l
    print("luas persegi panjang adalah ", luas, type(luas))
    
else :
    p = float(input("masukkan ukuran panjangnya "))
    l = float(input("masukkan ukuran lebarnya "))
    keliling = 2 * (p + l)
    print("keliling persegi panjang adalah ", keliling, type(keliling))
    
