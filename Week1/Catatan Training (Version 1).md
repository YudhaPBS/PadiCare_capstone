> [!NOTE]
> **Detail training model Version 1**
* epoch: 50
* accuracy: 0.6692
* loss: 0.8013
* val_accuracy: 0.1282
* val_loss: 4.2438
* learning_rate: 3.1623e-08
* time: 30269.5s
* GPU: none

> [!IMPORTANT]
> **Kesimpulan training model Version 1**
* **Very Bad**. Training membutuhkan waktu lama (faktor GPU), nilai accuracy kurang dan tidak konsisten selama training

> [!TIP]
> **Solusi yang akan dicoba pada versi selanjutnya**
* Penggunaan GPU saat melakukan training
* Mengurangi shear dan zoom range 
* Mengurangi ukuran batch dari 32 ke 16
* Mengurangi kompleksitas model dengan mengurangi jumlah filter di setiap layer konvolusi

