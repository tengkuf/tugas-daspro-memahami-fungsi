def hitung_gaji_lembur(gaji_pokok, total_jam_kerja) :
    if total_jam_kerja > 40 :
        jam_lembur = total_jam_kerja - 40
        upah_lembur = jam_lembur * 50000
        total_gaji = gaji_pokok + upah_lembur
    else :
        total_gaji = gaji_pokok
    return total_gaji

# input
gaji_pokok = int(input("masukan gaji pokok: "))
total_jam_kerja = int(input("masukan total jam kerja: "))

hasil = hitung_gaji_lembur(gaji_pokok, total_jam_kerja)

print("total gaji yang diterima adalah ", hasil)
