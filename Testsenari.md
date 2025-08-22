# 🔹 Yelo Bank Kredit Sifarişi – Yüksək Səviyyəli Test Ssenariləri

---

## Senari 1 – Uğurlu kredit sifarişi
1. İstifadəçi tətbiqdə **“Kredit sifarişi”** bölməsinə daxil olur  
2. Tələblərə uyğun **məbləğ, müddət və faiz dərəcəsi** daxil edir  
3. Sistem **aylıq ödənişi düzgün hesablayır** və nəticəni göstərir  
4. İstifadəçi sifarişi təsdiqləyir  

**Nəticə:** Kredit sifarişi uğurla yaradılır və status göstərilir  

---

## Senari 2 – Limit daxilində minimum dəyərlərlə müraciət
1. İstifadəçi minimum dəyəğ (400 AZN), minimum müddət (1 ay), minimum faiz (10.9%) ilə müraciət edir  
2. Sistem qəbul edir və nəticə göstərilir  

**Nəticə:** Kredit sifarişi uğurla icra olunur  

---

## Senari 3 – Limit daxilində maksimum dəyərlərlə müraciət
1. İstifadəçi maksimum məbləğ (50 000 AZN), maksimum müddət (36 ay), maksimum faiz (36%) ilə müraciət edir  
2. Sistem qəbul edir və nəticə göstərilir  

**Nəticə:** Kredit sifarişi uğurla icra olunur  

---

## Senari 4 – Limitdən kənar məlumatlarla müraciət
1. İstifadəçi məbləğ, müddət və ya faiz dərəcəsini icazə verilən hədlərdən kənarda daxil edir  
2. Sistem **xəbərdarlıq mesajı** göstərir və müraciət göndərilmir  

**Nəticə:** Kredit sifarişi rədd edilir  

---

## Senari 5 – Boş məlumatlarla müraciət
1. İstifadəçi input sahələrini boş buraxır və müraciət etməyə çalışır  
2. Sistem xəbərdarlıq göstərir  

**Nəticə:** Kredit sifarişi icra olunmur  

---

## Senari 6 – Hesablama dəqiqliyi
1. İstifadəçi düzgün məlumatları daxil edir  
2. Sistem aylıq ödənişi hesablamaq üçün **faiz dərəcəsini və müddəti tətbiq edir**  

**Nəticə:** Aylıq ödəniş real maliyyə formuluna uyğun olur  

---

## Senari 7 – Sistem səhvi və ya bağlantı problemi
1. İstifadəçi məlumatları daxil edib müraciət göndərir, amma server cavab vermir və ya internet yoxdur  
2. Sistem uyğun **error mesajı** göstərir  

**Nəticə:** Kredit sifarişi tamamlanmır, amma istifadəçiyə aydın məlumat verilir  

---

## Senari 8 – Multi-device və Cross-browser yoxlaması
1. İstifadəçi eyni prosesi **mobil tətbiq** və **veb sayt** üzərindən sınayır  

**Nəticə:** Bütün platformalarda eyni davranış və nəticə alınır  
