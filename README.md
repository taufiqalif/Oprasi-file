#Oprasi File
w = write mode / mode menulis dan menghapus file lama, jika file tidak ada maka akan dibuatkan otomatis
r = read mode only / hanya bisa baca
a = appeding mode / menambahkan data di akhir baris
r+ = write and read mode

##Membuat file text

	file = open("data.txt",'w')
	file.write("ini adalah data text yang dibuat")
	file.write("\nini adalah baris kedua")
	file.write("\nini adalah baris ketiga")
	file.write("\nini adalah baris keempat")

	file.close()

##Membuat file text

	file2 = open("data.txt",'r')

	print(file2.read())
	print(file2.readline()) #ini untuk menampilkan baris pertama di text

	file2.close()

##Appending mode

	file3 = open("data.txt",'a')
	file3.write("\nbaris ini menggunakan mode append")

	file3.close()

##Gambar

![01.png](/gambar/01.png)

file text yang di buat 

![02.png](/gambar/02.png)

hasil output dari read

![03.png](/gambar/03.png)