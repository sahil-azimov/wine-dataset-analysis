Wine Quality Analysis & EDA
Bu layihə çərçivəsində şərab verilənlər bazası (Wine Dataset) üzərində ilkin məlumatların təmizlənməsi (Data Cleaning), kəşfiyyat xarakterli məlumat təhlili (EDA) və vizuallaşdırma işləri həyata keçirilmişdir.

🚀 Görülən İşlər (Workflow)
Məlumatların Oxunması və İlkin Baxış: Datasetin yüklənməsi, strukturunun yoxlanılması (info(), describe()).

Məlumatların Təmizlənməsi (Data Cleaning):

Çatışmayan (missing/null) dəyərlərin yoxlanılması və emalı.

Dublikat sətirlərin təmizlənməsi.

Səhv və ya kənar dəyərlərin (outliers) müəyyənləşdirilib tənzimlənməsi.

Qrafiklər və Vizuallaşdırma (EDA):

Xüsusiyyətlər (features) arasındakı əlaqələri göstərən korrelyasiya matrisası (heatmap).

Dəyişənlərin paylanmasını (distribution) göstərən histoqramlar.

Keyfiyyət göstəriciləri ilə digər parametrlər arasındakı əlaqəni əks etdirən qrafiklər.

🛠️ İstifadə Olunan Kitabxanalar
Pandas & NumPy (Məlumatların manipulyasiyası və analizi)

Matplotlib & Seaborn (Qrafiklər və vizuallaşdırma)

📂 Layihə Strukturu
Plaintext
├── data/               <- Şərab dataset faylı (.csv)
├── notebooks/          <- Təmizləmə və qrafiklərin qurulduğu Jupyter Notebook
└── README.md           <- Layihə təsviri
