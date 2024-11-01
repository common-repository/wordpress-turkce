=== WordPress Türkçe ===
Contributors: unsalkorkmaz
Tags: turkish, turkce, language, url, post, posts, categories, category, tag, tags, taxonomy
Requires at least: 3.0
Tested up to: 3.5.1
Stable tag: 1.2.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

WordPress yazı,etiket veya kategori gibi adreslerde Türkçe karakterlerin (ŞşİıĞğÜüÖöÇç) kullanımına izin veren eklenti.

== Description ==

Şu an için WordPress'de yazı,etiket veya kategori gibi adreslerde **ŞşİıĞğÜüÖöÇç** karakterlerini kullanmaya çalıştığınızda **ssiigguuoocc** haline gelmektedir. Kullanıcı adlarında ise bu karakterlere izin verilmemektedir.
Bu eklenti sayesinde Türkçe karakterleri(ŞşİıĞğÜüÖöÇç) WordPress yazı,etiket veya kategori adreslerinde kullanabilmekteyiz. 
Bu eklentiyi yükleyip etkinleştirmeniz yeterlidir. 
Hiçbir ayar gerekmektedir. Tüm sorularınızı [wordpress.org forumlarında](http://wordpress.org/tags/wordpress-turkce?forum_id=10) sorabilir veya bana http://www.unsalkorkmaz.com adresinden ulaşabilirsiniz.

= İleri düzey kullanıcılar dikkat: = 
* Türkçe karakterlere kullanıcı adlarında da izin vermek için;

 `define( 'WPTURKCE_USER', true );`
* Türkçe karakterlere blog adreslerinde de izin vermek için;

 `define( 'WPTURKCE_BLOG', true );`

 Bu tanımlamaları wp-config.php dosyanıza veya mu-plugins dosyalarında veya eklentilerinizde tanımlayabilirsiniz.

== Installation ==

1. `wordpress-turkce` klasörünü `/wp-content/plugins/` klasörü içine ekleyin veya WordPress yönetim panelindeki 'Eklentiler' bölümünde 'Yeni Ekle' linkine tıklayarak 'Eklenti Kur' sayfasında 'WordPress Türkçe' olarak arama yapın ve bu eklentiyi seçip 'Şimdi Kur' ile kurabilirsiniz.
2. WordPress yönetim panelindeki 'Eklentiler' bölümünden WordPress Türkçe'yi etkinleştirin.


== Changelog ==

= 1.2.1 =
* Bug fix

= 1.2 =
* Kullanıcı adlarında ve blog adreslerinde Türkçe desteği

= 1.1 =
* Kullanıcı adlarında türkçe karakter desteğini kaldırdım. Multisite'da gerekli bazı değişiklikler oluncaya kadar beklemek lazım.

= 1.0 =
* İlk yayın


