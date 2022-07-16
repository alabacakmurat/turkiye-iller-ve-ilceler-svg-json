# Türkiye İl/İlçeler JSON/SVG verisi
Türkiye'nin il ve ilçelerine yönelik basit kapsamlı json verisidir.

Adana iline ait örnek şablon aşağıda verilmiştir. Gerekli kontrollerin yapılması gerekmektedir. Boş değer girilmiş veriler mevcut olabilir. Fark edildiği takdirde güncelleme yapılacaktır.
```json
[
  {
    "plate": "1",
    "slug": "adana",
    "name": "Adana",
    "zipcode": "0322",
    "population": "2.220.125",
    "region": "Akdeniz",
    "area": "13.844",
    "male_population": "1.106.811",
    "male_population_percentage": "49.15%",
    "female_population": "1.113.314",
    "female_population_percentage": "50.15%",
    "population_overall_percentage": "2,71%",
    "districts": [
      {
        "slug": "imamoglu",
        "name": "\u0130mamo\u011flu",
        "population": "28.239",
        "area": "445",
        "male_population": "14.140",
        "female_population": "14.099",
        "path": "M 408.5345 200.8885 408.75 200.7417 408.987 200.504 409.1242 200.4172 409.2736 200.421 409.3437 200.4617 409.5845 200.7874 409.7158 200.8762 409.9941 200.9275 410.157 200.8834 410.2743 200.7955 410.3666 200.5649 410.3688 200.3262 410.299 200.1479 410.1823 200.085 410.0549 200.1003 409.9925 200.2142 410.0106 200.442 409.8896 200.4856 409.7756 200.3764 409.5678 200.1117 409.5281 200.0183 409.5574 199.8743 409.6492 199.6902 409.8219 199.502 409.96 199.4479 410.3013 199.4604 410.3891 199.4437 410.4772 199.352 410.5122 199.251 410.4469 199.1118 410.0667 198.7671 409.6306 198.4166 409.4864 198.1468 409.3759 198.0049 408.7963 197.367 408.679 197.2882 408.4723 197.2378 408.4095 197.1851 408.407 197.0708 408.5679 196.883 408.6923 196.8651 408.7852 196.9052 409.0608 197.0919 409.2401 197.1435 409.2989 197.0342 409.042 196.4672 408.8133 196.1985 408.8217 196.0939 409.1823 195.6225 409.2916 195.7372 409.7176 195.9135 409.889 195.9282 410.271 195.9918 410.4766 196.0457 410.604 196.1387 410.8684 196.1779 411.1475 196.1828 411.5393 196.2367 411.8968 196.2318 412.0976 196.3199 412.1367 196.4717 412.1269 196.7999 412.0976 196.9027 412.2182 197.3055 412.31 197.7609 412.3798 197.8931 412.5561 197.9849 412.7617 198.209 412.9601 198.3302 413.096 198.4734 413.511 198.8113 413.8966 199.039 414.3006 199.1933 414.7083 199.208 414.9874 199.1529 415.1894 199.0794 415.7844 199.0207 416.2986 199.0243 416.7541 198.9288 417.0442 198.9031 417.3784 198.9325 417.551 198.9178 417.6502 198.8627 417.7788 198.6975 418.0359 198.4183 418.2011 198.3669 418.539 198.3596 418.6859 198.444 418.7961 198.6056 419.0569 198.7599 419.3691 198.9692 420.3093 199.5055 420.3864 199.5863 420.4158 199.7112 420.3938 199.8764 420.2836 200.1262 420.1514 200.3649 420.1844 200.5302 420.2652 200.6367 420.8492 200.846 421.5617 200.9048 421.7013 200.9379 421.7711 201.0995 421.8372 201.1766 422.2926 201.3382 422.4065 201.4557 422.4322 201.6283 422.7334 201.7789 422.928 201.9332 423.0198 202.0581 423.1484 202.0911 423.3047 202.1987 423.2114 202.3462 423.0318 202.5659 422.7965 202.6007 422.5667 202.7923 422.0468 203.0624 421.382 203.1691 420.7664 203.2998 420.6432 203.6101 420.6774 203.9695 420.4996 204.1547 419.624 204.2419 418.9537 204.3345 418.0371 204.4979 417.5241 204.8138 416.4365 204.792 416.1013 205.0208 415.6088 205.1733 415.1847 205.2224 414.8231 205.1504 414.5479 205.1811 413.9638 205.3597 413.6861 205.5293 413.481 205.2319 413.3545 204.9653 413.293 204.7738 413.4127 204.6713 413.4849 204.5551 413.5977 204.232 413.5336 203.8629 413.4567 203.6834 413.4233 203.5116 413.2311 203.2988 413.1234 203.2604 412.4235 203.4296 412.0671 203.4527 411.6775 203.5655 411.5698 203.6629 411.3596 203.7142 411.1827 203.8552 410.9724 203.9526 410.7956 203.991 410.4546 204.2397 410.0752 204.291 410.0034 204.3679 409.7624 204.4217 409.6188 204.5012 409.283 204.5166 408.7856 204.5089 408.5587 204.4542 408.3331 204.3722 408.152 204.3585 407.8272 204.2901 407.3452 204.2047 406.9419 203.9791 406.8633 203.8184 406.7197 203.6407 406.7641 203.3091 406.7205 203.1696 406.9979 203.1147 407.1383 203.041 407.284 202.8694 407.3305 202.7374 407.2615 202.5337 407.2174 202.2722 407.2887 202.1275 407.3701 202.0459 407.5596 201.9253 408.0761 201.7523 408.0982 201.6386 408.0316 201.5286 407.9829 201.3413 408.0368 201.131 408.1855 201.0254 408.5345 200.8885 Z",
        "polygon": "408.5,200.9,408.8,200.7,409,200.5,409.1,200.4,409.3,200.4,409.3,200.5,409.6,200.8,409.7,200.9,410,200.9,410.2,200.9,410.3,200.8,410.4,200.6,410.4,200.3,410.3,200.1,410.2,200.1,410.1,200.1,410,200.2,410,200.4,409.9,200.5,409.8,200.4,409.6,200.1,409.5,200,409.6,199.9,409.6,199.7,409.8,199.5,410,199.4,410.3,199.5,410.4,199.4,410.5,199.4,410.5,199.3,410.4,199.1,410.1,198.8,409.6,198.4,409.5,198.1,409.4,198,408.8,197.4,408.7,197.3,408.5,197.2,408.4,197.2,408.4,197.1,408.6,196.9,408.7,196.9,408.8,196.9,409.1,197.1,409.2,197.1,409.3,197,409,196.5,408.8,196.2,408.8,196.1,409.2,195.6,409.3,195.7,409.7,195.9,409.9,195.9,410.3,196,410.5,196,410.6,196.1,410.9,196.2,411.1,196.2,411.5,196.2,411.9,196.2,412.1,196.3,412.1,196.5,412.1,196.8,412.1,196.9,412.2,197.3,412.3,197.8,412.4,197.9,412.6,198,412.8,198.2,413,198.3,413.1,198.5,413.5,198.8,413.9,199,414.3,199.2,414.7,199.2,415,199.2,415.2,199.1,415.8,199,416.3,199,416.8,198.9,417,198.9,417.4,198.9,417.6,198.9,417.7,198.9,417.8,198.7,418,198.4,418.2,198.4,418.5,198.4,418.7,198.4,418.8,198.6,419.1,198.8,419.4,199,420.3,199.5,420.4,199.6,420.4,199.7,420.4,199.9,420.3,200.1,420.2,200.4,420.2,200.5,420.3,200.6,420.8,200.8,421.6,200.9,421.7,200.9,421.8,201.1,421.8,201.2,422.3,201.3,422.4,201.5,422.4,201.6,422.7,201.8,422.9,201.9,423,202.1,423.1,202.1,423.3,202.2,423.2,202.3,423,202.6,422.8,202.6,422.6,202.8,422,203.1,421.4,203.2,420.8,203.3,420.6,203.6,420.7,204,420.5,204.2,419.6,204.2,419,204.3,418,204.5,417.5,204.8,416.4,204.8,416.1,205,415.6,205.2,415.2,205.2,414.8,205.2,414.5,205.2,414,205.4,413.7,205.5,413.5,205.2,413.4,205,413.3,204.8,413.4,204.7,413.5,204.6,413.6,204.2,413.5,203.9,413.5,203.7,413.4,203.5,413.2,203.3,413.1,203.3,412.4,203.4,412.1,203.5,411.7,203.6,411.6,203.7,411.4,203.7,411.2,203.9,411,204,410.8,204,410.5,204.2,410.1,204.3,410,204.4,409.8,204.4,409.6,204.5,409.3,204.5,408.8,204.5,408.6,204.5,408.3,204.4,408.2,204.4,407.8,204.3,407.3,204.2,406.9,204,406.9,203.8,406.7,203.6,406.8,203.3,406.7,203.2,407,203.1,407.1,203,407.3,202.9,407.3,202.7,407.3,202.5,407.2,202.3,407.3,202.1,407.4,202,407.6,201.9,408.1,201.8,408.1,201.6,408,201.5,408,201.3,408,201.1,408.2,201,408.5,200.9,408.5,200.9"
      },
    ],
]
```

