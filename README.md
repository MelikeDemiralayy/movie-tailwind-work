# Tailwind Movie Project

Bu proje, modern bir web uygulaması oluşturmak için [Tailwind CSS](https://tailwindcss.com/docs/installation) kullanarak geliştirilmiştir. Proje, kullanıcı dostu bir arayüz tasarlamaya odaklanmıştır ve responsive tasarım prensiplerine uygun olarak oluşturulmuştur.
Tailwnd Css konusundaki yetkinliklerimi pekiştirmek amacıyla oluşturulmuştur.
## İçindekiler

- Kurulum
- Teknolojiler
- Tailwind css 
- Dark mode kullanımı
- Proje Özellikleri
- Responsive Tasarım
- Flex ve Grid Yapıları
- @apply Kullanımı

## Kurulum
- Projenin yerel ortamda çalıştırılması için aşağıdaki adımları takip edebilirsiniz:

```bash
git clone <repository-url>
cd <project-directory>
```
- Gerekli paketleri yükleyin:

```bash
npm install
```
- Geliştirme sunucusunu başlatın:
  
```bash
npm run build:css
npm run
```

## Teknolojiler
- Html5: Yapısal İçerik.
- TailwindCSS: Hızlı ve etkili stil oluşturmak için.
- JavaScript: Dinamik içerik yönetimi için.
- Font Awesome: İkon kullanımı için.
## Proje Özellikleri:
Bu projede şu özellikler bulunmaktadır:
- Responsive Tasarım: Uygulama, farklı ekran boyutlarına uyum sağlayacak şekilde tasarlanmıştır. Tailwind CSS'in sınıflarını kullanarak, mobil öncelikli bir yaklaşım benimsenmiştir.
- Kullanıcı Dostu Arayüz: Basit ve çekici bir kullanıcı deneyimi sağlamak için estetik bir tasarım yapılmıştır.
### Responsive Tasarım:
Proje, farklı cihazlar ve ekran boyutları için optimize edilmiştir. Tailwind CSS'in sağladığı yardımcı sınıflar sayesinde, elementlerin boyutları ve düzenleri farklı ekran boyutlarına göre kolayca ayarlanmıştır.
#### Örnek kullanım:
```bash
<div class="container mx-auto px-4 lg:px-0">
  <h1 class="text-2xl">Başlık</h1>
  <p class="text-sm">Bu bir açıklama metnidir.</p>
</div>

```
### Flex ve Grid Yapıları:
- Projenin layout düzeni, Tailwind CSS'in flex ve grid yapıları kullanılarak oluşturulmuştur. Bu sayede, içerik düzeni esnek ve dinamik bir şekilde ayarlanabilir. Örneğin:
#### Flex kullanımı:
```bash
<div class="flex justify-between">
  <div class="basis-1/3">Öğe 1</div>
  <div class="basis-1/3">Öğe 2</div>
  <div class="basis-1/3">Öğe 3</div>
</div>
``` 

#### Grid Kullanımı:
```bash
<div class="grid grid-cols-3 gap-4">
  <div>Öğe 1</div>
  <div>Öğe 2</div>
  <div>Öğe 3</div>
</div>

```
### Dark Mode Desteği
Projede dark mode desteği sağlanmıştır. Kullanıcılar, arayüzü karanlık bir tema ile kullanabilmektedir. Tailwind CSS'in dark mode sınıfları sayesinde bu özellik kolayca uygulanmıştır.
```bash
<div class="bg-white dark:bg-gray-800 text-black dark:text-white">
  <h1>Başlık</h1>
</div>

```
### @apply desteği
Tailwind CSS, kullanıcıların stilleri özelleştirmesine olanak tanır. @apply direktifi ile, belirli stilleri bir araya getirip yeniden kullanabiliriz. Bu sayede, kod tekrarını azaltarak daha temiz bir CSS yapısı oluşturulmuştur.
```bash
@layer components {
  .btn {
    @apply bg-gega-red text-white py-2 px-4 rounded;
  }
}

```
