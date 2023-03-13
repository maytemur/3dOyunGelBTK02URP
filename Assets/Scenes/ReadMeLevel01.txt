Duvarda delik pencere kapı vs açmak için,
önce face selection'ı pro builder 'dan seçiyoruz sonra duvarın 2 yüzünü seçip scale toolu aktif edip ebatları ayarlıyoruz,
sonra backspace ile siliyoruz.

Probuilder'ın experimental'ı açmak için edit preferences'dan enable experimental'ı açmak gerekiyor.
Experimental boolean ilede aynı işlem yapılabiliyor. Rhino booelan gibi.

Oda Lambası flörans prefabı: 
Aslında ışık yaymayan ve emisyon özelliği üzerinden yayıyormuş gibi gözüken prefablardır. Kapanması için emisyon özelliğinin kapatılması
yeterli gerçekten ışık yayması için posprocess denilen volume-global volume altında yeni profil-add overwrite diyi post processing
menüsünden bloom ekleyerek yapıyoruz. Daha sonra detayına inilecek.