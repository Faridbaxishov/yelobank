Bu Portfolio tipi test case yazma bacarigini numayis etdirmek ucundu istifade etdiyin texnika Boundary Value test usuludur.
| Test Case ID | Title                  | Steps                                                                        | Expected Result                               |
| ------------ | ---------------------- | ---------------------------------------------------------------------------- | --------------------------------------------- |
| TC-AMT-01    | Məbləğ 399 daxil et    | 1. Kredit məbləği inputuna `399` daxil et <br> 2. Hesablama düyməsinə bas    | Sistem rədd etməli, error mesajı göstərilməli |
| TC-AMT-02    | Məbləğ 400 daxil et    | 1. Kredit məbləği inputuna `400` daxil et <br> 2. Hesablama düyməsinə bas    | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-AMT-03    | Məbləğ 401 daxil et    | 1. Kredit məbləği inputuna `401` daxil et <br> 2. Hesablama düyməsinə bas    | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-AMT-04    | Məbləğ 58,999 daxil et | 1. Kredit məbləği inputuna `58,999` daxil et <br> 2. Hesablama düyməsinə bas | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-AMT-05    | Məbləğ 59,000 daxil et | 1. Kredit məbləği inputuna `59,000` daxil et <br> 2. Hesablama düyməsinə bas | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-AMT-06    | Məbləğ 59,001 daxil et | 1. Kredit məbləği inputuna `59,001` daxil et <br> 2. Hesablama düyməsinə bas | Sistem rədd etməli, error mesajı göstərilməli |

| Test Case ID | Title              | Steps                                                            | Expected Result                               |
| ------------ | ------------------ | ---------------------------------------------------------------- | --------------------------------------------- |
| TC-DUR-01    | Müddət 0 daxil et  | 1. Müddət inputuna `0` daxil et <br> 2. Hesablama düyməsinə bas  | Sistem rədd etməli, error mesajı göstərilməli |
| TC-DUR-02    | Müddət 1 daxil et  | 1. Müddət inputuna `1` daxil et <br> 2. Hesablama düyməsinə bas  | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-DUR-03    | Müddət 2 daxil et  | 1. Müddət inputuna `2` daxil et <br> 2. Hesablama düyməsinə bas  | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-DUR-04    | Müddət 35 daxil et | 1. Müddət inputuna `35` daxil et <br> 2. Hesablama düyməsinə bas | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-DUR-05    | Müddət 36 daxil et | 1. Müddət inputuna `36` daxil et <br> 2. Hesablama düyməsinə bas | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-DUR-06    | Müddət 37 daxil et | 1. Müddət inputuna `37` daxil et <br> 2. Hesablama düyməsinə bas | Sistem rədd etməli, error mesajı göstərilməli |

| Test Case ID | Title              | Steps                                                            | Expected Result                               |
| ------------ | ------------------ | ---------------------------------------------------------------- | --------------------------------------------- |
| TC-INT-01    | Faiz 10.8 daxil et | 1. Faiz inputuna `10.8` daxil et <br> 2. Hesablama düyməsinə bas | Sistem rədd etməli, error mesajı göstərilməli |
| TC-INT-02    | Faiz 10.9 daxil et | 1. Faiz inputuna `10.9` daxil et <br> 2. Hesablama düyməsinə bas | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-INT-03    | Faiz 11 daxil et   | 1. Faiz inputuna `11` daxil et <br> 2. Hesablama düyməsinə bas   | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-INT-04    | Faiz 35.9 daxil et | 1. Faiz inputuna `35.9` daxil et <br> 2. Hesablama düyməsinə bas | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-INT-05    | Faiz 36 daxil et   | 1. Faiz inputuna `36` daxil et <br> 2. Hesablama düyməsinə bas   | Sistem qəbul etməli, hesablama aparılmalı     |
| TC-INT-06    | Faiz 36.1 daxil et | 1. Faiz inputuna `36.1` daxil et <br> 2. Hesablama düyməsinə bas | Sistem rədd etməli, error mesajı göstərilməli |
