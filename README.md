ASP.NET Core Uyarlaması – Teknik Açıklama

Bu proje, daha önce masaüstü ortamı için geliştirilmiş bir uygulamanın, ASP.NET Core mimarisine uyarlanmış sürümüdür. Uyarlama sürecinde, uygulamanın temel iş mantığı korunarak web tabanlı bir yapıya taşınması hedeflenmiştir.

Geliştirme ortamı olarak Visual Studio Code kullanılmıştır. Proje, .NET 8 SDK kurulu bir sistem üzerinde oluşturulmuş ve çalıştırılmıştır.

Proje Oluşturma ve Yapılandırma

.NET 8 SDK kurulumunun ardından, proje oluşturma işlemi bir terminal aracılığıyla gerçekleştirilir. Terminal, Visual Studio Code üzerinden veya işletim sisteminin varsayılan terminali kullanılarak açılabilir.

Öncelikle proje için bir çalışma dizini oluşturulur ve bu dizine geçilir:

Emeklilik


Daha sonra, aşağıdaki komut kullanılarak ASP.NET Core Web App şablonu oluşturulur:

dotnet new webapp -o Emeklilik


Bu komut, Razor Pages tabanlı bir ASP.NET Core uygulama iskeleti oluşturur.

Proje Yapısı ve Kod Bileşenleri

Hesaplamalar.cs
Uygulamada kullanılan temel hesaplama ve iş mantığı bu sınıf içerisinde yer almaktadır.

Pages/Index.cshtml
Kullanıcı arayüzüne ait Razor sayfasını içerir.

Pages/Index.cshtml.cs
Index sayfasının arka plan kodlarını (page model) barındırır.

Bu dosyalarda yapılan değişiklikler, oluşturulan ASP.NET Core projesine dahil edilerek uygulamanın işlevselliği sağlanmıştır.

Uygulamanın Çalıştırılması

Uygulamayı yerel ortamda çalıştırmak için, terminal üzerinden proje dizinine girilir ve aşağıdaki komut çalıştırılır:

dotnet run


Bu komut, ASP.NET Core uygulamasını derler ve yerel geliştirme sunucusu üzerinde çalıştırır.

Bu çalışma, masaüstü uygulamalarının ASP.NET Core tabanlı web uygulamalarına dönüştürülmesine yönelik teknik bir örnek niteliği taşımakta olup, eğitim ve inceleme amaçlı referans olarak değerlendirilebilir.
