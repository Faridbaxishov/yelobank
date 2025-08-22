# YeloBank  
**Test Planı**

---

## 1. Məqsəd
Yelo Bank **kredit sifarişi** modulunun funksionallığının düzgünlüyünü və validasiya qaydalarını yoxlamaq.  
Kredit məbləği, müddət və faiz dərəcəsi əsasında **aylıq ödənişin hesablanması** və istifadəçiyə düzgün göstərilməsi təmin olunmalıdır.  

---

## 2. Əhatə dairəsi
**Test ediləcək funksiyalar:**
- Kredit məbləğinin input sahəsi *(min: 400 AZN, max: 50 000 AZN)*  
- Müddət input sahəsi *(min: 1 ay, max: 36 ay)*  
- Faiz dərəcəsi input sahəsi *(min: 10.9%, max: 36%)*  
- Hesablanma nəticəsində aylıq ödənişin düzgün göstərilməsi  

---

## 3. Test yanaşması
- Positive Testing  
- Negative Testing  
- Boundary Testing  
- UI / UX Testing  
- Calculation Testing  

---

## 4. Test mühiti
- **Platforma:** Web  
- **Brauzerlər:** Chrome  
- **Backend:** Test API serveri  

---

## 5. Risklər
- Yanlış faiz və müddət hesablanması  
- Input validasiyasının düzgün işləməməsi  
- Səhv xəbərdarlıq mesajlarının göstərilməsi  

---

## 6. Çıxış kriteriyaları
- Bütün əsas test ssenariləri icra olunub  
- Kritik və yüksək prioritetli bug-lar həll olunub  
- Aylıq ödəniş hesablamaları düzgün işləyir  
- Input validasiyası uğurla test edilib  

---
