# Windows Users

Windows üzerinden ubuntu kullanmak için, Windows Subsytem Linux(wsl) 'in kurulum aşamalarını anlatacağım.
Burada dikkat edilmesi gereken önemli husus GPU'nuz wsl'i destekliyor mu. 
Bu araştırıldıktan sonra windows + wsl de ilerlenmesi daha sağlıklı olacaktır.

Ama bilgisayarınızı daha optimize kullanabilmek adına OS olarak başlangıçta ubuntu'yu tavsiye ederim. Eğer Kamera ile işlenecek projeler için wsl'i kullanacaksanız.
windows wsl'e porttan gelen datalar için erişim sağlattırmıyor. Bu hususta içinde OS olarak ubuntuya geçmeniz gerekir.  

# Ubuntu Users

Ubuntu users içinde windowsdaki tavsiyeler geçerlidir ide + docker sistemi aynı çalışacaktır.

# INSTALLATION STEPS

Wsl kurulumu için [text](https://learn.microsoft.com/en-us/windows/wsl/install), [video](https://www.youtube.com/watch?v=VUW2pIjDpEk)
version olarak ``` Ubuntu-22.04``` kullanıyoruz. Referans komut: ``` wsl.exe --install Ubuntu-22.04 ```

IDE olarak VSCode [installation](https://code.visualstudio.com/download) kullanıyorum. 


[Docker nedir ?](https://forum.yazbel.com/t/docker-tam-olarak-nedir/13685/2)

Docker [installation](https://docs.docker.com/engine/install/ubuntu/), docker kullanımını da windows docker yerine wsl de yapıyorum Tüm sistemim windowstan bağımsız olmuş oluyor.
Bunu linux sistemine bağlanmış olduğunuz terminalden çalıştırmanız gerekiyor.

# Extensions
extensions'lara iletmiş oldugum [txt](https://github.com/Renbago/sahaRobotikBootcamp/blob/main/niceToHave/extensions.txt) den teker teker indirebilirsiniz. 

Ya da extensions.txt nin bulunduğu dizine gidip ```cat extensions.txt | xargs -L 1 code --install-extension``` ile indirebilirsiniz.



