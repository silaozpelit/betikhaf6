# betikhaf6
class hesapmakinesi:
    def __init__(self,say1,say2): #Bu constructor (kurucu metod).Bir nesne oluşturulduğunda ilk çalışan fonksiyon.
        self.say1=say1 #self.say1 → nesnenin içindeki değişken / say1 → dışarıdan gelen değer
        self.say2=say2

    def topla(self):
        sonuc=self.say1 + self.say2
        #return sonuc
        print(sonuc)

    def carp(self):
        sonuc=self.say1 * self.say2
        #return sonuc
        print(sonuc)
        

class hesapmakinesi:
    def __init__(self,say1,say2): #Bu constructor (kurucu metod).Bir nesne oluşturulduğunda ilk çalışan fonksiyon.
        self.say1=say1 #self.say1 → nesnenin içindeki değişken / say1 → dışarıdan gelen değer
        self.say2=say2
        self.memory=[] #yapılan işlemlerin sonuçlarını tutan liste.Sonuçlar burada saklanacak.

    def topla(self):               #Bu fonksiyon: iki sayıyı toplar,sonucu memory listesine ekler,sonucu ekrana yazdırır
        sonuc=self.say1 + self.say2
        self.memory.append(sonuc)
        #return sonuc
        print(sonuc)

    def carp(self):
        sonuc=self.say1 * self.say2
        self.memory.append(sonuc)
        #return sonuc
        print(sonuc)

class hesapmakinesi:
    def __init__(self,say1,say2): #Bu constructor (kurucu metod).Bir nesne oluşturulduğunda ilk çalışan fonksiyon.
        self.say1=say1 #self.say1 → nesnenin içindeki değişken / say1 → dışarıdan gelen değer
        self.say2=say2
        self.memory=[] #yapılan işlemlerin sonuçlarını tutan liste.Sonuçlar burada saklanacak.

    def topla(self):               #Bu fonksiyon: iki sayıyı toplar,sonucu memory listesine ekler,sonucu ekrana yazdırır
        sonuc=self.say1 + self.say2
        self.memory.append(sonuc)
        #return sonuc
        print(sonuc)

    def carp(self):
        sonuc = self.say1 * self.say2
        self.memory.append(sonuc)
        # return sonuc
        print(sonuc)

    def cikar(self):
        sonuc = self.say1 - self.say2
        self.memory.append(sonuc)
        print(sonuc)

    def bol(self):
        if self.say2 == 0:
            print("0'a bölme hatası")
        else:
            sonuc = self.say1 / self.say2
            self.memory.append(sonuc)
            print(sonuc)

    def yazdir(self,n):
        a = self.say1
        b = self.say2

        for i in range(1, n):
            r = a * (b + i)
            sonuc = '{} x {} = {}'.format( a, b + i, r)
            print(sonuc,"\n")












