# Deep-Learning
2 sınıflı CNN tabanlı bir derin öğrenme problemi çözülecektir
Dataset için toplamda 300 adet resim kullnılmıştır. 150 gömlek, 150 çorap olarak belirlenmiştir.
A) İLK ADIM : Normal olarak CNN-maxpool olayı sürecinde örneğin 20-30 epoch seçilerek 
		Train/validation accuracy grafiği
		train/validation  loss grafiği
                           
	B) İKİNCİ ADIM: Data augmentation yöntemi ile deney tekrarı
		Train/validation accuracy grafiği
		train/validation  loss grafiği

	C) ÜÇÜNCÜ ADIM: Drop-out  ile deney tekrarı
		train/validation  loss grafiği
                          
	D) Overfitt eden nokta gözleniyorsa train süreci erken bir EPOCH’ta kesilerek  (artık augmentation, drop-out üzerine bir de epoch etkisi gözlenecek!)    
		Train/validation accuracy grafiği
		train/validation  loss grafiği
                         
