> [!NOTE]
> **Detail training model Version 2**
* epoch: 50
* accuracy: 0.6524
* loss: 0.8176
* val_accuracy: 0.1371
* val_loss: 4.1768
* learning_rate: 3.1623e-08
* time: 11820s
* GPU: T4 x2

> [!IMPORTANT]
> **Kesimpulan training model Version 2**
* **Very Bad**. Training masih membutuhkan waktu lama meski sudah mengugnakan GPU, nilai accuracy kurang dan tidak konsisten selama training

> [!TIP]
> **Solusi yang akan dicoba pada versi selanjutnya**
* Menambahkan augmentasi data yang lebih beragam (rotation_range, brightness_range, vertical_flip)
* Menambahkan callback EarlyStopping untuk mencegah overfitting
* Menggunakan learning rate schedules yang lebih agresif melalui ReduceLROnPlateau
