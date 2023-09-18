# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
->Bir sürüm kontrol sistemi, farklı kişilerin yaptığı değişikliklerin geçmişini izler.

2. Git ile GitHub arasında ne fark var?
->Git repoları için bulut tabanlı bir barındırma hizmeti sunar.
 
3. Neden bir branch oluşturuyoruz?
->Yerel bilgisayarda çalıştığımız kaynak kodun bir kopyasını oluşturarak geliştirmelerin orijinal koddan bağımsız ilerlemesini sağlar.

4. Pull Request'in amacı nedir?
->Bir deponun yerel sürümünü remote olarak güncellemek için kullanılır.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
-> git checkout main

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu komutlar ne yapar açıklayınız.
->git fetch, remotetaki tüm değişiklikleri locale indirir ve depolar. Ama birleştirmez. Birleştirmeden önce local ve remotetaki değişiklikleri görebiliriz.
git merge, yerel ve remote değiştiyse bunları birleştirmek için kullanırız.
git merge, fetch ten sonra birleştirmek için bunu kullanırız.
git pull, fetch ve merge birleşimi diyebiliriz.

7. Merge conflict nedir?
->Aynı satırda farklı değişiklikler yapıldığında veya birisinin düzenlediği bir dosyayı başkası sildiğinde yaşanır.

8. Merge conflict'i nasıl çözeriz?
->Hangi değişikliklerin yeni işleme dahil edileceğine karar vermeliyiz. 
