# Python_MachineLearning

### Bölüm-1: Derslerle ilgili önemli notlar 
Kullanacağımız metodoloji (yöntem biçimi): CRISP-DM' dir. 

CRISP-DM veri madenciliği için sektörler arasında standart süreç anlamına gelmektedir. En popüler metodolojilerden biridir ve yaygın olarak kullanılmaktadır. Veri analizi süreçlerinde yol haritası oluşturma açısından önemli bir yere sahiptir. 

- CRISP-DM metodoloji 6 adımda gerçekleşir.                                                                 
1. Business Understanding     
Business Understanding aşamasında yapılacak proje, projenin gerçekleştirileceği sektörün, şirketin ihtiyaçları ve amaçlarına ne kadar katkı sağlayabilir, proje sırasında oluşabilecek sorunlar nelerdir, hangi araçları ve kaynakları kullanmalıyız? Sorularına cevaplar aranmaktadır. Kısaca yapacak olduğumuz analiz sürecinin mini planının hazırlanma kısmıdır. 

2. Data Understanding     
Data Understanding yani veriyi anlama aşamasında karar verdiğimiz, mini planını hazırladığımız proje hakkında verileri toplamaya başlarız. Bu aşamada topladığımız verileri anlamlandırmak, verilerin kalitesini belirlemek, verilerde herhangi bir eksiklik ya da gürültü veriler var mı bunun saptaması yapılır. 
Gürültü veri: Veride hata olması durumudur. 

3. Data Preparation 
Bu aşamada topladığımız veriler modelleme aşamasına hazırlanır. Önceki aşamada verilerde saptadığımız eksik veriler, hatalar düzeltilir. Veriler modelleme için elverişli duruma gelir. 

4. Modeling        
Modelleme adım yapılacak projenin hedefine ulaşması açısından oldukça önemlidir. Hazırladığımız verilere ve ulaşmak istediğimiz sonuca yönelik algoritma modeli belirlenir. Seçmiş, uygulamış olduğumuz test aşamasına hazırlanır. 

5. Evaluation          
Oluşturmuş olduğumuz modeli uygulamaya koymadan önce değerlendirdiğimiz, seçmiş olduğumuz modelin performansını test ettiğimiz aşamadır. Modelin nasıl çalıştığını gözlemleriz. Modelin doğruluk yüzdesi ne kadar yüksek ya da hedefimize ne kadar yakın olursa gerçek hayata o kadar uygundur diyebiliriz. İstediğimiz oranı veya sonucu yakalayamazsak süreç tekrar gözden geçirilir. 

6. Deployment 
Deployment adımında problemin çözümüne yönelik oluşturduğumuz modelin performansının yüksek çıkması ve gerçek hayata uygunluğu sonucunda modeli canlıya alırız, bir başka deyişle günlük kullanıma açmış oluruz.                                                                                                                                                                                                                                                                                                                                Bölüm 2: Veri Ön İşleme (Data Preprocessing) 

- Kütüphanelerin Yüklenmesi: NumPY, Pandas ve MathPlot Yüklenmesi 
```python
import pandas as pd 

import numpy as np 

import matplotlip.pyplot as plt 
```
 

 
