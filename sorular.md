## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?

Yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir. Git sayesinde yapacağımız projelerin adım adım versiyonlarının kopyalarını alırız. Daha sonra ihtiyaç duyduğumuz zaman aldığımız kopyalara yani versiyonlara kolayca dönebilmemizi sağlıyor.
 
2. Git ile GitHub arasında ne fark var?

GitHub kalabalık bir ekibin veri kontrol sisteminde bir yazılım geliştirirken kullanabilecekleri internet tabanlı bir depolama servisidir.Tüm ekibin aynı proje üzerinde çalışmasına olanak tanır.

3. Neden bir branch oluşturuyoruz? 
Ana projeyi etkilemeyecek değişiklikleri yapabilme alanı sağlamak için branch oluştururuz.Birden fazla kişi aynı proje üstünde çalıştığında çakışan yerler olabilir bunları görmemiz sağlar.

4. Pull Request'in amacı nedir?

Pull request talebi aslında branch’dan sorumlu kişiden kodumuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğimizi görmesine de yardımcı olur.Bir alanda yapılan değişikliğin aşka bir alanda birleştirilme isteği.

5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.

git checkout

6. `git fetch`, `git merge` ve `git pull` arasındaki farkları açıklayınız. Bu konutlar ne yapar açıklayınız.

Git fetch--yerel depomu uzaktaki deponun içeriğine ekle.
Git merge--bir branch i etkin branch ile birleştirmek için kullanılır. Pull request onayı sonrası birleştirme ve ana projeye ekleme
Git pull--Uzak depoda bulunan tüm değişiklikleri yerel çalışma dizinine birleştirmek için kullanılır.

7. Merge conflict nedir?

İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git bunu fark eder ve otomatik olarak merge edemezse bu durumda conflict e yani çakışmaya neden olacaktır. 

8. Merge conflict'i nasıl çözeriz?
Bir çakışma yaşanıyorsa buna sebep olan kodaları yazanlar ve gerekirse ekipteki herkes oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.