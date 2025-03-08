Tugas 1:
Luas Persegi Panjang
Input: Panjang = 5, Lebar = 3
Output: Luas = 15

def luas_persegi_panjang(panjang, lebar):
    return panjang * lebar

Tugas 2: 
Properti Lingkaran
Input: Jari-jari = 5
Output: Diameter = 10, Keliling = 31.4159, Luas = 78.539

import math
def properti_lingkaran(jari_jari):
    diameter = 2 * jari_jari
    keliling = 2 * math.pi * jari_jari
    luas = math.pi * jari_jari ** 2
    return diameter, keliling, luas

Tugas 3: 
Sudut Segitiga
Input: Sudut A = 80, Sudut B = 65
Output: Sudut Ketiga = 35

def sudut_ketiga(a, b):
    return 180 - (a + b)

Tugas 4: 
Perbedaan Tanggal dalam Hari
Input: Tanggal1 = 2024-03-19, Tanggal2 = 2024-03-21
Output: Perbedaan dalam Hari = 2

from datetime import datetime
def perbedaan_tanggal(tanggal1, tanggal2):
    format_tanggal = "%Y-%m-%d"
    t1 = datetime.strptime(tanggal1, format_tanggal)
    t2 = datetime.strptime(tanggal2, format_tanggal)
    delta = t2 - t1
    return delta.days

Tugas 5: 
Mencetak Inisial dalam Huruf Besar
Input: Nama = John Doe
Output: Inisial = JD

def inisial(nama):
    return ''.join([bagian[0].upper() for bagian in nama.split()])
