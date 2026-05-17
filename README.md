# 🛍️ Birmarket E-ticarət Data Analitika Paneli (Power BI)

Bu interaktiv Power BI paneli "Birmarket" e-ticarət platformasının satış performansını, strukturunu və ödəniş dinamikasını izləmək və biznes qərarlarını optimallaşdırmaq üçün hazırlanmışdır.

---

### 1. 🖥️ Ön İzləmə (Giriş Paneli)
*  Bu səhifə menecerlər üçün ümumi biznes vəziyyətini bir baxışda xülasə edir. Üst hissədə əsas KPI-lar (**Xalis Gəlir: 490.37K**, **Ümumi Satış: 498.95K**, **Sifariş Sayı: 3140**) qeyd olunub. **Bosch** brendinin satış lideri olduğu, sifarişlərin yarıya yaxınının (~49.59%) hələ emal / çatdırılma mərhələsində (Marketpleys tərəfindən) olduğu və noyabr ayının 21-də satış trendində kəskin artım (pik nöqtəsi) yaşandığı vizual olaraq əks olunub.
  
<img width="1235" height="694" alt="1" src="https://github.com/user-attachments/assets/1ebc478f-4acd-4554-ad07-bc802abe5517" />

---

### 2. 📈 Satış Performansı və Brend Analizi
*  Satışların zamana görə dəyişməsini və brendlərin töhfəsini dərindən analiz edən səhifədir. Sol tərəfdəki bar qrafikində brendlərin Ümumi Satış və Xalis Gəlir fərqləri müqayisə olunur (**Bosch** və **Tmakota** bazarda dominantlıq edir). Sağ tərəfdəki xətti qrafik (Trend Line) isə 30 günlük satış dinamikasını göstərir; burada Noyabrın 5-də **54K** ilə rekord satış həcmi müşahidə olunur ki, bu da xüsusi kampaniya və ya endirim günlərindən xəbər verir.

<img width="1235" height="694" alt="2" src="https://github.com/user-attachments/assets/bbe8285c-f0f3-4778-8842-b9d2c5d867dd" />

---

### 3. 📊 Satışın Strukturu və Məhsul Kateqoriyaları
*  Sifarişlərin status, ödəniş üsulu və məhsul kateqoriyalarına görə bölünməsini təqdim edir. Matrix cədvəlindən görünür ki, **Qaynaq avadanlığı** (72.6K) və **Elektrik alətlər dəstləri** (36.8K) dövriyyəyə ən çox pul gətirən kateqoriyalardır. Ödəniş üsullarında həm satış həcminə, həm də sifariş sayına görə **Kuryerə kreditlə** seçimi açıq ara fərqlə birincidir.

<img width="1235" height="696" alt="3" src="https://github.com/user-attachments/assets/e9dd1b3b-e767-4e34-af00-f4f9874b4729" />

---

### 4. 💳 Ödəniş və Zaman Matrisi Analizi (Sankey & Heatmap)
*  Bu səhifə daha qabaqcıl vizuallaşdırmalar ehtiva edir. **Sankey Diagramı** vasitəsilə Ümumi Satışın hansı ödəniş üsulu, sifariş statusu və kateqoriyalar üzərindən necə axdığı (data flow) zəncirvari şəkildə izlənilir. Aşağıdakı **Heatmap (İstilik xəritəsi)** isə həftənin günləri və saatlar üzrə sifariş sıxlığını göstərir; platformada ən aktiv saatların **günorta 13:00 - 14:00** və **axşamüstü 17:00 - 20:00** aralığı olduğu, xüsusilə Bazar ertəsi axşam saatlarında sifarişlərin kəskin artdığı aydın görünür.

<img width="1231" height="694" alt="4" src="https://github.com/user-attachments/assets/70fd588b-10b2-4fe9-ba65-b47591796b0a" />

---

---

## 🛠️ Layihədə Peşəkar UX və Texniki Həllər (Tooltips)

Bu paneldə istifadəçi təcrübəsini (UX) artırmaq və hesabat səhifələrini vizual olaraq yükləməmək üçün **Xüsusi Səhifə Tooltip-ləri (Custom Page Tooltips)** tətbiq edilmişdir.

<img width="493" height="373" alt="6" src="https://github.com/user-attachments/assets/d1016b55-941d-4819-a909-57d1d50966e3" />


* **Nə üçün istifadə olundu?** Standart Power BI tooltip-ləri yalnız quru rəqəmləri göstərdiyi halda, xüsusi dizayn olunmuş tooltip səhifələri vasitəsilə istifadəçi siçanı (mouse) hər hansı bir brendin və ya kateqoriyanın üzərinə gətirdikdə, həmin obyektə aid alt analitika (məsələn, brendin ən çox satılan top 3 məhsulu və ya xalis mənfəət marjası) kiçik bir pop-up pəncərədə vizual qrafiklərlə açılır.
* **Biznes dəyəri:** Bu funksionallıq hesabatı oxuyan menecerlərə əsas səhifədən ayrılmadan, sadə bir hərəkətlə daha dərin (drill-down) məlumatlar əldə etməyə imkan verir.
