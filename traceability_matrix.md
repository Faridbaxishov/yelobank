# Yelo Kredit Sifarişi – Traceability Matrix

| Scenario ID | Scenario Title                             | Related Test Cases |
|-------------|---------------------------------------------|--------------------|
| **SC-01**   | Uğurlu kredit sifarişi                     | TC-AMT-02 (Məbləğ valid), TC-DUR-02 (Müddət valid), TC-INT-02 (Faiz valid), TC-SUB-01 (Uğurlu sorğu göndərişi) |
| **SC-02**   | Minimum dəyərlərlə müraciət                | TC-AMT-02 (Minimum məbləğ), TC-DUR-02 (Minimum müddət), TC-INT-02 (Minimum faiz) |
| **SC-03**   | Maksimum dəyərlərlə müraciət               | TC-AMT-05 (Maksimum məbləğ), TC-DUR-05 (Maksimum müddət), TC-INT-05 (Maksimum faiz) |
| **SC-04**   | Limitdən kənar məlumatlarla müraciət       | TC-AMT-01 (Məbləğ çox az), TC-AMT-06 (Məbləğ çox böyük), TC-DUR-01 (Müddət çox az), TC-DUR-06 (Müddət çox böyük), TC-INT-01 (Faiz çox az), TC-INT-06 (Faiz çox böyük), TC-SUB-02 (Xəta mesajının çıxması) |
| **SC-05**   | Boş məlumatlarla müraciət                  | TC-VAL-01 (Məbləğ boş), TC-VAL-02 (Müddət boş), TC-VAL-03 (Faiz boş), TC-VAL-04 (Bütün inputlar boş), TC-SUB-03 (Validation error göstərilməsi) |
| **SC-06**   | Hesablama dəqiqliyi                        | TC-AMT-03 (Faiz + müddət hesablaması), TC-DUR-03 (Müddət üzrə dəqiq hesab), TC-INT-03 (Faiz dərəcəsi düzgün tətbiqi), TC-CALC-01 (Ümumi kredit məbləğinin düzgün hesablanması) |
| **SC-07**   | Sistem səhvi və ya bağlantı problemi        | TC-SYS-01 (Server error – 500), TC-SYS-02 (Timeout vəziyyəti), TC-SYS-03 (İnternet bağlantısı kəsilməsi), TC-SYS-04 (Error mesajının düzgün göstərilməsi) |
| **SC-08**   | Multi-device və Cross-browser yoxlaması     | TC-COMP-01 (Chrome), TC-COMP-02 (Firefox), TC-COMP-03 (Safari), TC-COMP-04 (Edge), TC-MOB-01 (iOS cihazları), TC-MOB-02 (Android cihazları), TC-MOB-03 (Tablet ekran ölçüsü uyğunluğu) |
