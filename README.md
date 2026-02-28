## “Invoice-Friendly Override”

---
Sebuah instansi kecil baru berlangganan aplikasi layanan internal dari vendor lokal. Semalam vendor mengirim pesan yang (katanya) menenangkan:

<img width="50%" height="50%" position="center" alt="image" src="https://github.com/user-attachments/assets/dff0bf28-5ded-403d-8195-b668d834c83f" />


> “Minor patch ya, cuma perbaikan tampilan + optimasi performa 🙏”

Pagi harinya, dashboard admin **nggak bisa login**. Semua akun admin mentok di pesan:
**OVERRIDE REQUIRED**

Helpdesk langsung menghubungi vendor.

Vendor membalas cepat. Terlalu cepat. Dan terlalu… santai.

> Ticket #0214  
> Subject: “Admin override tool (fast build)”  
> Body:
> 
> “Saya lampirkan tool untuk mengeluarkan kode override.  
> Saya compile cepat dari Linux, outputnya masih default (belum sempat dirapihin).  
> Mohon jangan dishare 🙏”
>
> Attachment: `a.out`

Lima menit kemudian, ada email kedua (yang membuat ruangan mendadak sunyi):

> “Btw, kami lihat invoice bulan lalu masih outstanding.  
> Mungkin sistem otomatis masuk mode ‘pembatasan fitur’.  
> Tapi tenang, override tool ini bisa membantu sementara 🙂”

<br>

Setelah itu? Vendor menghilang.

Yang tersisa cuma:
- satu binary bernama **`a.out`** (ya, itu nama default hasil compile),
- dan satu instansi kecil yang butuh sistemnya hidup lagi **hari ini**.

Karena mereka nggak punya pilihan lain, tim kamu diminta melakukan hal yang jarang dilakukan di rapat koordinasi:
**membaca isi program tanpa diberi source code.**

---

<br>

> **Notes:** unduh file dari GitHub dalam mode **raw** (bukan preview) agar isi file tidak berubah.

---

## Objektif
1. Temukan **password** yang diminta program.
2. Dapatkan **flag/kode override** yang ditampilkan program.

---
