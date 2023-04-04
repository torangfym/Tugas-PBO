#Contoh program fungsional programming di Python:
#Menggunakan lambda function untuk mengalikan bilangan dengan 2
result = list(map(lambda x: x*2, [1, 2, 3, 4, 5]))
print(result) # [2, 4, 6, 8, 10]

#Contoh program OOP di Python:
class Motor:
    def __init__(self, merek, model, warna):
        self.merek = merek
        self.model = model
        self.warna = warna
        
    def info_motor(self):
        print("Merek:", self.merek)
        print("Model:", self.model)
        print("Warna:", self.warna)

#membuat objek motor dari kelas Motor
mobil1 = Motor("Honda", "Scoopy", "Putih")

#memanggil metode info_motor pada objek motor
mobil1.info_motor()
