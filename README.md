# Row_and_Column_flutter


## Review sebelumnya 

<hr>


### AxisAlignment :memo:
<hr>  

#### MainAxisAlignment 

- #### Row :white_check_mark:

![Logo Row](https://belajarflutter.com/wp-content/uploads/2020/08/row-diagram.png)

- #### column :white_check_mark:

![Logo column](https://belajarflutter.com/wp-content/uploads/2020/08/column-diagram-139x300.png)


Digunakan untuk penempatan Widget secara vertical sesuai dengan Row Maupun colomn ,ada 5 **MainAxisAligment** :


- MainAxisAligment.center 

    Digunakan untuk memindahkan widget ke area tengah secara vertical 

- MainAxisAligment.end
   
   Digunakan untuk memindahkan widget ke area paling akhir secara vertical

- MainAxisAlignment.start

   Memposisikan widget mengikuti posisi widget pertama

- MainAxisAlignment.spaceround

   Memberi jarak antar widget secara merata namun hanya memberikan setengah jarak pada awal dan akhir widget

- MainAxisAlignment.spaceEvenly

  Memberi jarak antara masing-masing child secara merata pada ruang yang tersedia


### CrossAxisAlignment :memo:
<hr>
Cross axis tentu memilki makna berlawanan dari main axis. Pada row, cross axis berarti sumbu vertical. Terdapat beberapa value yang bisa digunakan untuk properti ini, seperti berikut:

- CrossAxisAlignment.start 

  value ini akan membuat child ditampilkan pada sisi bagian atas widget parent
- CrossAxisAlignment.end
 
  value ini akan membuat child ditampilkan mulai pada bagian bawah widget parent.

- CrossAxisAlignment.center
  
   value ini akan membuat child berada pada bagian tengah vertical dari widget parent.

- CrossAxisAlignment.baseline
 
  value ini akan menyesuaikan ketinggian yang dimiliki oleh child. Misalkan terdapat satu widget yang memiliki ketinggian 180 sebagai widget tertinggi diantara widget lainnya, maka widget lainnya akan berada di tengah secara horizontal dari ketinggian tersebut.

- CrossAxisAlignment.stretch
 
  value ini akan memaksa child memiliki tinggi dari sisi atas hingga sisi bawah widget parent.


## Widget Row :white_check_mark:
<hr>

Widget yang telah saya pelajari adalah sebuah code dimana widget ini untuk membentuk horizontal 

``` dart
Row(
    children: <Widget>[
    Text("Text 4"),
    Text("Text 5"),
    Text("Text 6")
],
)

```



## Widget column :white_check_mark:v

widget ini digunakan untuk membentuk widget vertical

``` dart 

 body: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          crossAxisAlignment: CrossAxisAlignment.start,
          children: <Widget>[
            Text("Text 1"),
            Text("Text 2"),
            Text("Text 3"),

```

#### MainAxisSize

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
