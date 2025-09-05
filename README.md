
# YeloBank – Test Plan

---

## 1. Məqsəd  
Yelo Bank **kredit sifarişi** modulunun funksional düzgünlüyünü və validasiya qaydalarını yoxlamaq. Kredit məbləği, müddət və faiz dərəcəsi əsasında aylıq ödənişin hesablanması və istifadəçiyə düzgün göstərilməsinin təmin olunması.

---

## 2. Əhatə dairəsi  

**Test ediləcək funksiyalar:**
- Kredit məbləği input sahəsi (min: 400 AZN, max: 50,000 AZN)  
- Müddət input sahəsi (min: 1 ay, max: 36 ay)  
- Faiz dərəcəsi input sahəsi (min: 10.9%, max: 36%)  
- Hesablanma nəticəsi – aylıq ödənişin düzgün göstərilməsi  

---

## 3. Test yanaşması  

- Positive testing  
- Negative testing  
- Boundary value testing  
- UI/UX testing  
- Calculation testing  

---

## 4. Test mühiti  

- **Platforma:** Web və Mobil App  
- **Brauzerlər:** Chrome, Safari, Edge  
- **Backend:** Test API serveri  

---

## 5. Risklər  

- Yanlış faiz və müddət hesablanması  
- Input validasiyasının düzgün olmaması  
- Səhv xəbərdarlıq mesajı göstərilməsi  
- Fərqli cihazlarda UI problemləri  

---

## 6. Çıxış kriteriyaları  

- Bütün əsas funksional testlərin keçirilməsi və nəticələrinin uğurlu olması  
- Bütün kritik və yüksək prioritetli bug-ların həll edilməsi  
- Hesablama nəticələrinin düzgünlüyünün təsdiqlənməsi  
- UI/UX testlərində əsas səhvlərin aradan qaldırılması  


