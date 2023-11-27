# Membandingkan kota pada saat siang dan malam

akan disediakan dataset yang berisi penggambaran kota pada siang dan malam hari, lalu akan dibandingkan keduanya untuk bisa menghasilkan tampilan siang pada kota malam hari, begitu juga sebaliknya

## Libraries yang Digunakan

Proyek ini menggunakan beberapa library untuk pengolahan data, pembuatan model, visualisasi, dan pemantauan pelatihan model. Berikut adalah daftar library yang digunakan beserta fungsinya:

- `zipfile`: Digunakan untuk bekerja dengan file zip.
- `os`: Digunakan untuk berinteraksi dengan sistem operasi.
- `tensorflow.keras.preprocessing.image.ImageDataGenerator`: Untuk mempersiapkan dan memproses data gambar.
- `tensorflow.keras.models.Sequential`: Untuk membuat model neural network secara berurutan.
- `tensorflow.keras.layers.Conv2D`, `tensorflow.keras.layers.MaxPooling2D`, `tensorflow.keras.layers.Flatten`, `tensorflow.keras.layers.Dense`: Untuk menentukan lapisan-lapisan dalam model neural network.
- `matplotlib.pyplot`: Digunakan untuk membuat visualisasi atau plot data.
- `tensorflow.keras.callbacks.TensorBoard`: Untuk integrasi dengan TensorBoard, alat visualisasi untuk pemantauan pelatihan model.
- `datetime`: Untuk manipulasi tanggal dan waktu.

Dataset ini berisi gambar kota yang diambil pada waktu siang dan malam.
[Link ke Dataset](https://www.kaggle.com/datasets/heonh0/daynight-cityview)

File model .h5. Karena terlalu besar, tidak bisa upload
[Link ke file Model](https://drive.google.com/file/d/1-xAm01IrksPVjSXovfyJnjVXknSOWZx8/view?usp=sharing)
