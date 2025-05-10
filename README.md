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
