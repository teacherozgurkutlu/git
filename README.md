# git
git komutlarının kullanımını açıklayan repo<br/>

<b>Github üzerinde var olan bir repoyu bilgisayarımıza indirmek ve 
üzerinde değişiklikler yaparak tekrar github'a yüklemek için:</b><br/>

İndirme işlemi yapmak istediğiniz klasöre gidin (masaüstü yada d sürücüsü gibi)<br/>

      git clone https://github.com/.....<br/>

.... yerine indirmek istediğiniz klasörün adresi yazılmalıdır<br/>

Üsteki komut sonrasında repo isminde bir klasör oluşacaktır. Bu klasör içerisine girerek aşağıdaki komutları yazınız<br/>

      git status<br/>
          

Dosyalarda istediğiniz değişikleri yapın<br/>

      git status<br/>

      git config --global user.name "kullanıcı adınız"<br/>
      git config --global user.email mailadresiniz@gmail.com<br/>

      git config --list<br/>

      git commit -a -m "kayıtlar eklendi"<br/>

      git remote<br/>

      git remote -v<br/>

      git push origin master<br/>

İlk sefer için kullanıcı adı ve şifre girilir. Dosyalar Github hesabımızda ilgili repoya upload edilir.

<b>Bilgisayarımızda bulunan bir proje dosyasını github üzerinde bulunan bir repoya yüklemek için:</b><br/>

Proje klasörünün içerisine girilir.<br/>

      git init<br/>

      git add dance.txt<br/>

      git add .<br/>

      git status<br/>

      git commit -m "Dosya yada dosyalar eklendi"<br/>

      git remote add origin https://github.com/.....<br/>

origin dısında başka remote adresleri eklenebilir. Bu adresler push işlemi sırasında istenen adrese yüklemek için kullanılır.<br/>

      git remote remove origin<br/>

<b>Github web sayfası üzerinden dosyalar üzerinde yapılan değişiklikleri local klasörümüze almak için:</b> <br/>

      git pull origin master<br/>

<b>Branch oluşturmak ve değişiklik yapmak için:</b><br/>

      git branch graphics<br/>

      git checkout graphics<br/>

      git pull keegehan graphics<br/>

      git commit -m "keegehan merge işlemi"<br/>

      git checkout master<br/>

      git merge graphics<br/>

      git push origin master












