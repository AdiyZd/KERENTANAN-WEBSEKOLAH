# Daftar Kerentanan Sistem Sekolah (.sch.id)

⚠ **Disclaimer**:  
Laporan ini hanya untuk tujuan edukasi keamanan siber. **Jangan gunakan untuk aktivitas ilegal**. Peneliti wajib mengikuti [Responsible Disclosure](https://en.wikipedia.org/wiki/Responsible_disclosure).

---

## 🔍 Daftar Kerentanan

### 1. SMKN 1 Sampang
- **URL**: [https://smkn1sampang.sch.id/login](https://smkn1sampang.sch.id/login)
- **Kerentanan**: SQL Injection
- **Observasi**: Proses backend lambat (indikasi SQLi time-based)
- **Rekomendasi**: 
  ```sql
  ' OR SLEEP(5)--

  ``` 
### 2. makhamzanwadi2nw
- **URL**: [https://makhamzanwadi2nw.sch.id](https://makhamzanwadi2nw.sch.id/blog/admin/admin.php?page=add)
- **Kerentanan**: FREE ACCES
- **Observasi**: -

### 3. smakstlouis1sby
- **URL**: [https://smakstlouis1sby.sch](https://pcpdb.smakstlouis1sby.sch.id/notice)
- **Kerentanan**: -
- **Observasi**: CEK PAKAI BRUIP SUITE LOGIN NYA DI GANTI ADMIN
  ``` burp suite
  ` intercept dan ubah data user jadi admin dan coba login sebagai admin
  ```
  
### 4. smkn2-wnb
- **URL**: [https://smkn2-wnb.sch.id](https://smkn2-wnb.sch.id/masuk/)
- **Kerentanan**: RENTAN SQL LOGIN
- **Observasi**: 403
  ``` burp suite
  ` intercept dan coba bypass 403 
  ```

### 5. smp.baiturrahman-df
- **URL**: [https://smp.baiturrahman-df](https://psb.smp.baiturrahman-df.sch.id/login)
- **Kerentanan**: RENTAN SQL ' OR 1=1 #
- **Observasi** : 403
  ``` burp suite
  ` intercept dan coba bypass 403 
  ```

### 6. smkn1bukateja 
- **URL** : [https://smkn1bukateja](https://smkn1bukateja.sch.id/login/)
- **Kerentanan**: RENTAN SQL DAN BYPASS 403
- **Observasi** : BYPASS 403
   ``` burp suite
  ` intercept dan coba bypass 403 
  ```

### 7. smkn2singaraja
- **URL** : [https://www.smkn2singaraja.sch.id](https://www.smkn2singaraja.sch.id/index.php/jicon/login?source=%2Findex.php%2Fjicon%2Fissue%2Fview%2Freqwest%2Findex)
- **Kerentanan**: 403
- **Observasi** : Belum di coba bypass
  ``` burp suite
  ` intercept dan coba bypass 403 
  ```

### 8. www.smkn2singaraja.sch.id
- **URL** : [https://www.smkn2singaraja.sch.id](https://www.smkn2singaraja.sch.id/index.php/rcs/login)
- **Kerentanan**: 403
- **Observasi** : Belum di coba bypas dan sql
  ``` burp suite
  ` intercept dan coba bypass 403 
  ```

### 9. smakstmariamalang.sch.id
- **URL** : [https://smakstmariamalang.sch.id](https://smakstmariamalang.sch.id/wp-content/uploads/calendarize-it/calendarize-it-profile/admin/error_log)
- **Kerentanan**: 403
- **Obervasi** : Belum di coba sql dan belum bypass 403
  ``` burp suite
  ` intercept dan coba bypass 403 
  ```

---
