# Wallpaper_Changer


Python dilinde yazılmış windows için arkaplan değiştirici


Yapmanız gereken random olarak değişicek resimleri bir klasörde toplamanız ve o klasörü Wallpaper_Changer'a tanıtmanız.   


Bilgisayarı her başlattığınızda veya programı her çalıştırdığınızda seçtiğiniz resimlerden herhangi birini random olarak seçip arkaplanınıza atamaya yarar.

# Kullanım:

Öncelikle bir klasör oluşturup beğendiğiniz resimleri bu klasöre koymalısınız. 


Program klasörün içindeki resimlerden herhangi birini, programı her çalıştırdığınızda arkaplana atar.


Resimleri koyduğunuz klasörün tam yolunu programda Directory="" değişkenine tanıtmalısınız.


Artık kullanıma hazır ama başlangıçta herhangi bir hatayla karşılaşmamak adına böyle kullanmak yerine exe'ye çevirip kullanmanızı öneririm.

## Exe'ye çevirme işlemi:

Pyinstaller kullanarak exe'ye çevirebiliriz.
## Pyinstaller indirme ve komutları:

Cmd ile aracı indirelim    :    pip install pyinstaller


Projemizin python dosyasının da bulunduğu yerde cmd üzerinden    :    pyinstaller Wallpaper_Changer.py --onefile -- noconsole --icon "İcon dosyamızın tam yolu"


--icon paramteresi oluşturuğumuz exe'ye bir icon koymamızı sağlar. 


Artık program exe'ye çevrildi ve çalışmaya hazır.




