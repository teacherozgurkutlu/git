# git
git komutlarının kullanımını açıklayan repo<br/>

<b>Github üzerinde var olan bir repoyu bilgisayarımıza indirmek ve 
üzerinde değişiklikler yaparak tekrar github'a yüklemek için:</b><br/>

İndirme işlemi yapmak istediğiniz klasöre gidin (masaüstü yada d sürücüsü gibi)<br/>

      git clone https://github.com/.....<br/>

.... yerine indirmek istediğiniz klasörün adresi yazılmalıdır<br/>

Üsteki komut sonrasında repo isminde bir klasör oluşacaktır. Bu klasör içerisine girerek aşağıdaki komutları yazınız<br/>

      git status
          

Dosyalarda istediğiniz değişikleri yapın<br/>

      git status

      git config --global user.name "kullanıcı adınız"
      git config --global user.email mailadresiniz@gmail.com

      git config --list

      git commit -a -m "kayıtlar eklendi"

      git remote

      git remote -v

      git push origin master

İlk sefer için kullanıcı adı ve şifre girilir. Dosyalar Github hesabımızda ilgili repoya upload edilir.

<b>Bilgisayarımızda bulunan bir proje dosyasını github üzerinde bulunan bir repoya yüklemek için:</b><br/>

Proje klasörünün içerisine girilir.<br/>

      git init

      git add dance.txt

      git add .

      git status

      git commit -m "Dosya yada dosyalar eklendi"

      git remote add origin https://github.com/.....

origin dısında başka remote adresleri eklenebilir. Bu adresler push işlemi sırasında istenen adrese yüklemek için kullanılır.<br/>

      git remote remove origin

<b>Github web sayfası üzerinden dosyalar üzerinde yapılan değişiklikleri local klasörümüze almak için:</b> <br/>

      git pull origin master

<b>Branch oluşturmak ve değişiklik yapmak için:</b><br/>

      git branch graphics

      git checkout graphics

      git pull keegehan graphics

      git commit -m "keegehan merge işlemi"

      git checkout master

      git merge graphics

      git push origin master

<b>Merge işlemi ile ilgili sorun olursa</b>

      git fetch         //Dosyaların repoyla farklılık gösterip göstermediğini kontrol eder
      
      git merge origin/master
  










