#  Hotel Demand Cancel Prediction

Di dalam bisnis perhotelan, memastikan ketersediaan kamar hotel di suatu waktu dan untuk beberapa waktu yang akan datang sangat penting dalam mengoptimalkan pendapatan. Informasi mengenai ketersediaan kamar yang akurat dan aktual dapat menghindarkan hotel dari berbagai kerugian, semisal kerugian yang disebabkan oleh tamu yang membatalkan pesanan atau tidak melakukan check in di waktu kedatangannya.
Tamu yang membatalkan penginapannya, baik setelah mengabari pihak hotel terlebih dahulu (misalkan menghubungi sendiri atau dihubungi pihak hotel) maupun tidak, menyebabkan kekosongan kamar yang seharusnya mereka inapi. Kamar-kamar ini sebenarnya masih dapat disewakan kembali ke tamu yang lainnya, namun akan lebih sulit untuk memutuskan dengan segera kamar mana saja yang dapat disewakan kembali apabila kabar pembatalan oleh tamu diterima pihak hotel secara mendadak, semisal beberapa saat sebelum waktu check in.

### 1. Problem Framing
**Business objective** yang akan dicapai pada case study ini yaitu memaksimalkan ocupansi kamar hotel agar digunakan oleh orang yang sudah booking/pesan dengan tidak membatalkan kamar yang telah dipesan. karena akan sangat berpengaruh terhadap revenue dari pemilik hotel dan 
rantai yang terlibat dari bisnis perhotelan seperti makanan, ketersediaan consumable produk seperti : sikat gigi, odol, sabun madni dll. 

**Output dari machine** learning ini yaitu memperdiksi apakah end user akan membatalkan booking atau tidak

**Machine learning** yang digunakan dalam kasus ini adalah binary classification : Logistic regression, Knn, dan RandomForrest, dikarenakan hanya ada dua opsi yaitu mencancel atau tidak, serta tingkatan model machine learning dari yang paling sederhana 

**Perfomnce meassure** yang digunakan pada kasus machine learning ini adalah f1 score, recall, dan precission

**Resiko** yang mungkin diakibatkan dari kesalahan pemodelan yaitu, false negatif dalam prediksi
