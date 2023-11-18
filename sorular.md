# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
	Git bir versiyon kontrol sistemidir. Bir proje üzerinde yapılan değişiklikleri tarihsel ve olaysal sıraya koymaya yarar. 
	Birden fazla programcının aynı proje üzerinde çalışmasını mümkün kılan bir şeydir.
	
2. Git ile GitHub arasında ne fark var?
	Github git programını kullanan bir platformdur. Git'te bulunmayan birçok özelliği barındırır. Örneğin sadece git'i kullanarak internet üzerinde
	bir repository oluşturamayız.

3. Neden bir branch oluşturuyoruz?
	Projeyi etkilemeden o projeyi baz alan yeni bir fikri denemek, deneme başarılı ise projeye sonradan dahil edebilmek için.

4. Pull Request'in amacı nedir?
	Yeni bir branch'i projenin main branchine dahil etme isteğidir. Proje üzerinde çalışan programcıların kendini ilgilendiren bölümü değiştirdiklerini
	iletmek	ve diğer programcıları bu durumdan haberdar etme amacı taşır. Ayrıca open source bir projeyi forklayıp yeni bir branch açarak bu projeye
	katkı sağlayacağı düşünülen kodlar yazılabilir. Projeye katkı sağlayacağı düşünülen bu yeni kodlar pull request ile proje sahibine bildirilir, 
	gerekli şartlar sağlanıyor ise bu branch projeye proje sahibi tarafından dahil edilebilir.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
	git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
	git fetch: 
		serverdaki repository'deki değişiklikleri local'e çeker fakat localdeki dosyalarda bir değişiklik yapmaz. git status komutuyla 
		local repo ile serverdaki repo arasındaki farklılıkları görebiliriz.
	git merge: 
		branchleri birleştirmeye yarar
	

	git pull:
		git fetch ile git merge birleşimi gibidir. serverdaki repoyu locale çeker, 
		ve localdeki dosyalara serverdaki dosyalara yapılan değişiklikleri uygular
		

7. Merge conflict nedir?
	Aynı dosya üzerinde farklı kişilerin farklı işlemler uygulaması sebebiyle bir tutarsızlık çıkması olayına verilen isimdir.
	örneğin birinin değişiklik uyguladığı dosyayı başka birinin silmesi, aynı dosyada bir satırda bir kişinin if x > 5 başka birinin if x < 5 
	yazması.

8. Merge conflict'i nasıl çözeriz?
	Çelişen durumları düzelterek.
