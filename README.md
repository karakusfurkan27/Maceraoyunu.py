# Orman Macerası Oyunu README

## Genel Bakış

Bu, kullanıcının seçimlerine dayalı bir macera oyunudur. Oyuncu, bir ormanda kaybolmuş bir karakteri kontrol eder ve çeşitli yol seçimleri yaparak ormandan çıkmaya çalışır. Oyunun amacı, doğru seçimlerle macerayı tamamlayarak güvenli bir yere ulaşmaktır.

## Oynanış

Oyuncu, oyunda farklı yollardan birini seçerek ilerler. Her yol seçimi, yeni bir hikaye ve seçenek sunar. Oyuncu, bu seçenekler arasından birini seçer ve seçimlerine göre hikaye devam eder. İki ana yol vardır:

1. **Sol Yol**: Bir nehirle karşılaşır ve köprüyü geçip geçmeme kararı verir.
2. **Sağ Yol**: Bir mağara bulur ve mağaraya girip girmeme kararı verir.

Her iki yolun sonunda da başarılı bir şekilde çıkışa ulaşmak mümkündür.

## Kurulum

1. Python yüklü bir sisteminizin olduğundan emin olun.
2. Bu Python betiğini herhangi bir metin düzenleyicisi ile açın ve kaydedin (örneğin, `macera_oyunu.py`).
3. Komut satırında dosyanın bulunduğu dizine gidin ve aşağıdaki komutu çalıştırın:

    ```
    python macera_oyunu.py
    ```

4. Oyuna başladığınızda, komut satırında seçimler yaparak oyunu oynayabilirsiniz.

## Oyun Akışı

1. **Başlangıç**: Oyuncu, ormanın içinde kaybolduğunu ve çıkış yolunu bulması gerektiğini öğrenir.
2. **İlk Seçim**: Oyuncuya, iki yol (sol veya sağ) arasından birini seçmesi istenir.
3. **Sol Yol**: Eğer sol yol seçilirse, oyuncu bir nehirle karşılaşır ve köprüyü geçip geçmemeye karar verir.
4. **Sağ Yol**: Eğer sağ yol seçilirse, oyuncu bir mağara bulur ve mağaraya girip girmemeye karar verir.
5. **Kazanan**: Hem köprüden geçen hem de mağaraya giren oyuncular başarılı bir şekilde macerayı tamamlar ve oyunu kazanır.

## Kullanıcı Seçimleri

- **Sol Yol (S)**: Sol yolu seçmek için 'S' tuşuna basın.
- **Sağ Yol (Sağ)**: Sağ yolu seçmek için 'Sağ' tuşuna basın.
- **Köprüyü Geç (K)**: Nehrin karşısına geçmek için 'K' tuşuna basın.
- **Geri Dön (G)**: Geri dönmek için 'G' tuşuna basın.
- **Mağaraya Gir (G)**: Mağaraya girmek için 'G' tuşuna basın.

## Hata Mesajları

Eğer geçersiz bir seçim yapılırsa, kullanıcıya tekrar doğru bir seçim yapması gerektiği bildirilir ve aynı seçim ekranı tekrar gösterilir.

## Oyun Sonları

1. **Başarılı Son (Köprü veya Mağara)**: Köprüyü geçmek veya mağaraya girmek oyuncuyu güvenli bir alana ulaştırır ve oyuncu kazanır.
2. **Yeniden Başlama**: Yanlış seçimler yaparak geri dönüldüğünde oyun başlangıcına döner.

## Katkıda Bulunma

Bu projeye katkıda bulunmak istiyorsanız, kodunuzu iyileştirebilir veya yeni senaryolar ekleyebilirsiniz. Yapmak istediğiniz değişiklikleri pull request olarak gönderebilirsiniz.

## Lisans

Bu proje MIT lisansı altında lisanslanmıştır.
