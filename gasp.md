Gasp için  her 5 dakikada bir  dener. Boş yer bulursa işlemi tamamlar

    wget https://github.com/Madmin27/Ubuntu-22.04-notlarim/blob/main/gasprun.sh
    chmod +x /root/gasprun.sh

Şimdi aşağıdaki komutla crontab içerisine gireceksiniz
    
    crontab -e

En alta bu satırı paste edin ve CTRL +X ile çıkın

    */5 * * * * /root/gasprun.sh

  artık her 5 dakikada bir gasp için "run.sh opt-in " komutunu çalıştırıp, yer var mı kontrol edecek ve sonucu log doyanıza yazacak.
  Arasıra girip  gasp.log dosyanızın en alttaki çıktılarını kontrol edin

        nano /root/gasp.log

yeşildeki gibiyse tamam
crontab içerisindeki satırı silinki denemeye devam etmesin


![image](https://github.com/Madmin27/Ubuntu-22.04-notlarim/assets/94014225/ea2e296e-cfa3-400e-b1fc-54745bfa4e4f)

