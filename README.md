class Motor:
    def __init__(self, merek, model, warna):
        self.merek = merek
        self.model = model
        self.warna = warna
        
    def info_motor(self):
        print("Merek:", self.merek)
        print("Model:", self.model)
        print("Warna:", self.warna)

# membuat objek motor dari kelas Motor
mobil1 = Motor("Honda", "Scoopy", "Putih")

# memanggil metode info_motor pada objek motor
mobil1.info_motor()
