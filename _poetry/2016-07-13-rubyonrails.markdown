---
layout: post
title: Ruby on Rails 
date: 2016-07-13 21:33:00
---

<blockquote>
Ruby on Rails'e Giriş...<br>
<a href="http://msazhar.github.io/folios/rails_installation/index.html#slide1" target="blank">#Rails Kurulumu</a>
</blockquote>


Uzem Akademi Yaz Kampı'nın eğitimleri başladı sonunda:) Bugün üçüncü günümüzdü. Ve Bu ilk üç günümüzün konusu Ruby on Rails idi...

Ruby on Rails, Ruby dilini temel alan bir web geliştirme framework'üdür. Ruby on Rails, kısaca Rails, iki temel yazılım geliştirme felsefesi üzerine kuruludur:


   <li> <b><b>Konfigurasyon Üzerine Kabuller (CoC: Convention over Configuration):</b><br> 
Bu kabuller sayesinde uygulamamızı geliştirmeye 1:0 önde başlamış oluruz, yani biz doğrudan işe başlayabiliriz. Bu felsefe sayesinde, Rails ile uygulama geliştirmek diğer hiç bir alternatifinin ulaşamadığı kadar hızlı ve eğlencelidir.
   <li> <b><b>Kendi kendini tekrarlamamak (DRY: Dont't Repeat Yourself):</b></b><br>  
Bu felsefedeki amaç ise, aynı işlevselliğe sahip kodun uygulamanın farklı yerlerinde tekrar tekrar yazılmasını engellemektir. Ruby'nin etkileyici metaprogramming(kısaca kod yazan kodlar) özellikleri sayesinde Rails, DRY felsefesini en üst düzeyde gerçekleştirmektedir. <br> 
Bir de MVC var...<br>
<br>
<h4>MVC (Model - View - Controller)</h4>
<br>
MVC (Model View Controller), çevik (agile) yazılım geliştirme süreçlerine uygun olarak sıklıkla tercih edilen bir yazılım mimarisi desenidir
(software architectural patter). MVC'deki ana düşünce, kullanıcı arayüzü ile arka plandaki işlemlerin birbirinden ayrı tutmak. Bu amaçla, sistemi üç ana rol başlık çatında geliştirmektedir..<br>
<li> <font color="black">Model:</font> Uygulamamızın kullandığı verilerin yaşadığı yerdir. Özel veriler ve bu verilerin arasındaki ilişkilerin, erişim ve düzenleme kurallarının bulunduğu bölümdür. Model, verilerin kullanıcıya ne şekilde sunulacağı ile ilgilenmez.
<li> <font color="black">View:</font> Uygulamamızın arayüz elemanlarını içeren bölümdür. Verilerin nereden geldiğiyle ilgili bir bilgisi yok.
<li> <font color="black">Controller:</font> Kullanıcı isteklerini gerçekleştirmek için gereken görevleri yerine getiren bölümdür. Ve bölümler arasındaki ilişki, Conr-troller ile gerçekleştirilmektedir. Veritabanına erişmekle yükümlü olan bölüm modeldir. Kullanıcı istekleri ise Controller'a iletilir. 

<p>
<center>
Kaynak: "Ruby on Rails" kitabı. (Sıtkı Bağdat)


