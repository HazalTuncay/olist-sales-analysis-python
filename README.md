# 🛒 Olist E-Commerce Data Analysis (Python)

Bu çalışma, Brezilya’nın en büyük e-ticaret platformlarından biri olan Olist veri seti kullanılarak hazırlanmış kapsamlı bir Python veri analizi projesidir.  
Amaç; sipariş davranışlarını, fiyat dağılımlarını, teslimat sürelerini, müşteri memnuniyetini ve ödeme yöntemlerinin tamamlanma oranlarını incelemektir.

---

## 🛠️ Tools & Technologies
- Python (Google Colab)
- Pandas • NumPy
- Plotly Express
- Matplotlib • Seaborn
- SciPy (İstatistiksel Testler)
- EDA • Feature Engineering

---

## 📥 1. Data Loading & Preparation
Kullanılan veri dosyaları:

- `olist_orders_dataset.csv`
- `olist_order_items_dataset.csv`
- `olist_products_dataset.csv`
- `olist_customers_dataset.csv`
- `olist_sellers_dataset.csv`
- `olist_order_payments_dataset.csv`
- `olist_order_reviews_dataset.csv`

Tüm veri setleri pandas DataFrame olarak yüklendi, eksik/gürültülü veriler temizlendi ve tarih alanları dönüştürüldü.

---

## 🔍 2. Exploratory Data Analysis (EDA)

### ✔️ Sipariş Fiyatları
- Ortalama ürün fiyatı  
- Sepet bazında toplam tutar  
- En yüksek / en düşük fiyatlar  
- Kategoriye göre fiyat karşılaştırmaları  

### ✔️ Ürün Kategorileri
- En çok sipariş edilen kategoriler  
- En yüksek gelir getiren kategoriler  
- Fiyat ortalaması yüksek kategori davranışları  

### ✔️ Teslimat Süreleri
- Satın alma → teslimat tarih farkı  
- Ortalama teslim süresi  
- Geciken sipariş oranı  
- Gecikmenin yorum puanına etkisi  

---

## 📊 3. Visualizations (Plotly & Matplotlib)
Projenin çıktıları arasında:

- Sepet tutarı dağılımı  
- Kategori bazında fiyat grafiği  
- Teslimat süresi histogramı  
- Kategori popülerliği  
- İnceleme puanı dağılımı  
- Ödeme yöntemlerinin tamamlanma oranı  

---

## 📈 4. Statistical Testing — Chi-Square
**Hipotez:**

- **H0:** Ödeme yöntemi siparişin tamamlanma oranını etkilemez  
- **H1:** Ödeme yöntemi siparişin tamamlanma oranını etkiler  

Yapılan chi-square testi sonucunda:

- **p < 0.05** bulundu  
- ➡️ **Ödeme yöntemi sipariş iptallerini anlamlı şekilde etkilemektedir.**  
- Kredi kartı işlemleri en yüksek tamamlanma oranına sahiptir.

---

## 💡 5. Key Insights
- Teslimat süresi uzadıkça **yorum puanı düşüyor**  
- **Kredi kartı**, en güvenilir ödeme yöntemi  
- Gecikme → memnuniyette ciddi düşüş  
- Bazı kategoriler (ör. *Informática Acessórios*) daha yüksek fiyat ortalamasına sahip  
- Büyük sipariş hacmine sahip kategoriler en yüksek geliri oluşturuyor  

---

## 🧠 6. Business Recommendations
- Lojistik gecikmeleri azaltacak optimizasyonlar yapılmalı  
- Yüksek gelir potansiyeli olan kategoriler desteklenmeli  
- Ödeme ekranlarında **kredi kartı önerisi** gösterilebilir  
- Gecikme riski yüksek bölgeler için özel SLA tanımlanabilir  
- Müşteri memnuniyeti düzenli olarak review-score analizleriyle takip edilmeli  

---

## 👩‍💻 Author
**Dirayet Hazal Tuncay – Data Analyst**  
Python • SQL • Power BI • BigQuery • Looker Studio
