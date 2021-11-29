# İndirilecekler Listesi

[Kurulum rehberine atla](#Neyi-nasıl-kurarım)

1\. Ders ve sonrası için:
   - Dev-C++ [Nasıl Kurulur](#Dev-Cpp)
3\. Ders ve sonrası için:
   - Arduino IDE [Nasıl Kurulur](#Arduino-IDE)
   - SimulIDE [Nasıl Kurulur](#SimulIDE)
6\. Ders ve sonrası için:
   - Visual Studio Code [Nasıl Kurulur](#Visual-Studio-Code)
   - Zeal [Nasıl Kurulur](#Zeal)
7\. Ders ve sonrası için:
   - İnternetiniz olsun, internetten dosyalara bakıcaz :)

# Neyi nasıl kurarım?

**UYARI:** Bu rehber Windows kullandığınızı varsayarak yazılmıştır, ancak kullanılan programlar Mac ve Linux işletim sistemlerine uyumlu versiyonları kendi sayfalarında vardır. Bir sorunuz olduğunda [bana mail atabilirsiniz.][mailme]

## Dev-Cpp

Dev-C++ programını [bu linke][dev-cpp-download] girdikten sonra yeşil "Download" butonu ile indireceğiz.

Taşınabilir halini indirmek isteyen arkadaşlar [bu linkten][dev-cpp-portable] "Dev-Cpp X.XX TDM-GCC x64 X.X.X Portable.7z" linkine tıklayarak indirebilirler. X ile gösterilen kısım versiyon numarasıdır, yazdığıma benziyen en üstteki dosyayı indirebilirsiniz.
Taşınabilir halini açmak için ayrıca 7-Zip File Manager programına ihtiyaç duyacaksınız.

Kurulumu yaparken Dil kısmını English olarak bırakıyoruz, sonrasında sırayla **Ok**, **I Agree**, **Next >** ve **Install** tuşlarına bastıktan sonra kurulumun bitmesini bekliyoruz. Ardından gelen ekranda **Finish** tuşuna basıp İlk Açılış ekranının gelmesini bekliyoruz.

İlk açılış ekranında dili Türkçe yapıp ilerliyoruz, editör açıldıktan sonra programı kapatıyoruz.

## Visual Studio Code

### Kendisini kurmak için

Visual Studio Code'un [bu linkten][vscode-download] indireceğiz.
Mimariniz büyük ihtimalle `64 bit`tir ancak kontrol etmekten de zarar gelmez.
E tamamda; 3 tane sürüm var, bu sürümlerden hangisini indireceksin?

- Bilgisayar seninse: **System Installer**.
  En az sıkıntı çıkaracak versiyon bu.
  Dosyayı açın, kurun, kurarken; 

  - **Add to PATH**

  - **Add "Open with Code"** (...) **"directory context menu"**

    kutularını işaretlemenizi öneririm.

  Ardından Visual Studio Code programını açın.

- Bilgisayar ortak kullanılıyor ama dosyalar kalıyorsa: **User Installer**
  *System Installer*'daki gibi indirin ve kurun. "Kurarken" kısmındaki kutuları işaretlemeyin.

- Bilgisayar kütüphaneninse (sıfırlandığında dosyalar gidiyor): **.zip**
  Buradan indirdiğiniz dosyayı flaş belleğinize ayıklayın.
  Flaş belleğinizin hızı sabit diskten daha yavaş olabileceği için programın daha yavaş çalışabileceğini unutmayın.
  Klasörün içindeki `Code.exe`yi çalıştırın.
  *İpucu:* Klasörleri veya dosyaları bu Code versiyonu ile açmak için açmak istediğiniz şeyi Code.exe üzerine **sürükleyip bırakın**.

### Kurulacak eklentiler

Visual Studio Code içinde `Ctrl + P` yaparak komutu yapıştırarak eklenti kurabilirsiniz.

- Arduino: [`ext install vsciot-vscode.vscode-arduino`](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino) Arduino IDE'ye pratik komutlar göndermemizi sağlıyor. İsteğe bağlı.
- C/C++: [`ext install ms-vscode.cpptools`](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools) Yazacağımız C kodunu program yapmadan kontrol etmemizi sağlıyor.
- Code Spell Checker: [`ext install streetsidesoftware.code-spell-checker`](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) İngilizce yazım hatalarını kontrol eden bir eklenti, aşağıdaki eklenti için gerekli. 
- Turkish - Code Spell Checker: [`ext install streetsidesoftware.code-spell-checker-turkish`](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker-turkish) Türkçe yazım hatalarını kontrol eden bir eklenti.
- Dash: [`ext install deerawan.vscode-dash`](https://marketplace.visualstudio.com/items?itemName=deerawan.vscode-dash) Zeal ile hızlı bir şekilde belge araması yaptırıyor. İsteğe bağlı.

## Arduino IDE

Arduino IDE'yi [bu linkten][arduino-download] edinin. Taşınabilir hali "ZIP file" yazandır. Kurun veya ayıklayın.

## SimulIDE

Programı [bu linkten][simulide-download] indirin ve ayıklayın. Program `bin` klasörü içindedir.
Program sadece taşınabilir modda geliyor ancak çok aktif olarak açacağımız bir program da değil.

## Zeal

### Kendisi

Zeal'i [bu linkten][zeal-download] indirin.
[Visual Studio Code](#Visual-Studio-Code) kurulumunda olduğu gibi bunda da Portable (Taşınabilir) sürüm var, internet hızınız gittiğiniz kütüphanede yavaş ise çok kez yararlanacaksınız. Bilgisayarda 7zip uygulaması yoksa **ZIP indirmesi yapın.** Yeni bir kurulum yapmadığınız sürece [Visual C++ 2015 Redist][vcpp13redist] kurulumu yapmanıza gerek olmayacaktır. (Kontrol etmek için Program Ekle/Kaldır) menüsünden **Visual C++ 2015** ile başlayan bir program arayın, varsa kurmanıza gerek yok.

### Kurmanızı istediğim paketler

- C: C'nin header dosyalarındaki fonksiyonlar ne işe yarar + bazı basit C işlevlerinin detaylı açıklamaları.
- Arduino: Arduino.h kütüphanesi ve çoğu C işlevlerinin basit açıklamaları var. Ayrıca örnek Arduino kodu da dahil.



[vscode-download]: https://code.visualstudio.com/download
[mailme]: mailto:arda.aydin@operationsilkscarf.com
[zeal-download]: https://zealdocs.org/download.html
[vcpp13redist]: https://www.microsoft.com/tr-tr/download/details.aspx?id=52685
[simulide-download]: https://www.simulide.com/p/downloads.html
[arduino-download]:https://www.arduino.cc/en/software
[dev-cpp-download]:https://sourceforge.net/projects/orwelldevcpp/
[dev-cpp-portable]:https://sourceforge.net/projects/orwelldevcpp/files/Portable%20Releases/

