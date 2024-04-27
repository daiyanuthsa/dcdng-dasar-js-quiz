Manakah dari kode berikut ini yang merupakan kode JavaScript untuk mencetak “Dicoding” ke konsol?
<br>Jawaban: ``` console.log(“Dicoding”); ```
#
JavaScript termasuk ke dalam scripting language, apa maksudnya?
<br>Jawaban: Tidak perlu di-compile agar bisa dijalankan.
#

Perhatikan kode berikut:
```javascript
const stock = 0;
const milkNeeded = 25;
if (stock > milkNeeded) {
  stock = stock - milkNeeded;
  console.log('Processing your order...');
} else {
  console.log('Out of Stock!');
}
console.log('Thank you');
```
Output dari program di atas adalah...

Jawaban:
Out of Stock!
Thank you
#

Perhatikan kode berikut:
```javascript
const name = 'Dicoding';
const language = 'JavaScript';
console.log(`Hello $name. Welcome to $language!`);
```
Apakah yang akan ditampilkan pada konsol ketika kode dijalankan?
Jawaban: Error
#

Manakah output yang tepat dari kode berikut?
```javascript
let myVariable = 12;
myVariable = 30;
myVariable = 5;
console.log(myVariable);
```
Jawaban: 5
#

Manakah pernyataan berikut ini yang benar terkait if statement?
<br>Jawaban: Kita bisa menambahkan blok kode if di dalam if.
#
Diberikan sejumlah elemen yang harus disimpan secara berurutan. Manakah struktur data yang akan Anda gunakan?
<br>Jawaban: Array
#

Terdapat array seperti berikut:
```javascript
const phoneticAlphabet = ["Alpha", "Bravo", "Delta"];
// TODO: Kode untuk menambahkan item Charlie pada index ke-2
console.log(phoneticAlphabet);
```
Manakan kode yang perlu Anda tambahkan pada TODO supaya array phoneticAlphabet akan menampilkan output: [ 'Alpha', 'Bravo', 'Charlie', 'Delta' ] ?
<br>Jawaban: phoneticAlphabet.splice(2, 0, “Charlie”);
#

Perhatikan potongan kode berikut:
```javascript
const capital = {
    "Jakarta": "Indonesia",
    "London": "England",
    "Tokyo": "Japan"
}
capital["New Delhi"] = "Indonesia";
console.log(capital["Indonesia"]);
```
Ketika kode di atas dijalankan, maka outputnya adalah...
Jawaban: undefined
#

Perhatikan kode berikut:
```javascript
function calculate(value) {
    return value < 2 ? value : (calculate(value - 1) + calculate(value - 2));
}
console.log(calculate(3));
```
Jika kode di atas dijalankan, maka manakah hasilnya?
Jawaban: 2 
#

Berapa banyak parameter yang bisa dimiliki oleh suatu function?
Jawaban: Sesuai kebutuhan
#
Perhatikan kode di bawah ini.
```javascript
class Car { }
const car = new Car();
console.log(typeof Car);
```
Apa output yang akan dihasilkan?
Jawaban: Function
#

Perhatikan kode constructor function berikut.
```javascript
function car({ brand, maxSpeed, wheelCount }) {
  this.brand = brand;
  this.maxSpeed = maxSpeed;
  this.wheelCount = wheelCount;
}
const myCar = car({ brand: 'Toyota', maxSpeed: 200, wheelCount: 4 });
```
Jika kode di atas dijalankan, objek myCar gagal dibuat. Apa alasannya?
<br>Jawaban: Pemanggilan constructor function car harus diawali dengan keyword new.
#

Istilah pewarisan pada paradigma Object Oriented Programming biasa dikenal dengan…
<br>Jawaban: Inheritance
#

Berikut ini yang bukan merupakan karakteristik dari functional programming, adalah...
<br>Jawaban: Polymorphism
#

Apakah yang dimaksud dengan Functional Programming?
<br>Jawaban: Paradigma pemrograman di mana proses komputasi didasarkan pada fungsi matematika murni.
#

Bagaimanakah karakteristik API pada Node.js?
<br>Jawaban: Asynchronous
#

Bagaimana cara memeriksa versi NPM yang terinstal saat ini?
Jawaban: ``` npm --version ```
#

Cara yang tepat untuk meng-export beberapa nilai sekaligus dalam module adalah ...
<br>Jawaban: Menyimpan setiap nilai pada object literals.
#

Berikut ini adalah alasan untuk menerapkan module pada project JavaScript, kecuali...
Jawaban: Membebaskan program dari adanya error/bug.
#

Manakah keyword berikut ini yang digunakan untuk membuat error secara manual?
Jawaban: throw
#

Perhatikan kode berikut:
```javascript
let myString = "";
try {
    myString += "a";
    throw Error();
} catch(e) {
    myString += "b";
} finally {
    myString += "c";
    throw Error();
    myString += "d";
}
console.log(myString);
```
Apakah output dari program di atas?
Jawaban: ``` Error ```
#

Perhatikan kode berikut:
```javascript
try {
    const arr = [1, 2, 3, 4];
    for (let i = 0; i <= 4; i++) {
        console.log(arr[i]);
    }
} catch(e) {
    console.log("Out of bounds");
}
```
Output yang akan dihasilkan ketika kode di atas dijalankan adalah...
Jawaban:
```
1
2
3
4
undefined
```
#

Bagaimana proses asynchronous dijalankan pada sebuah program?
Jawaban: Dijalankan tanpa perlu menunggu hasilnya
#

Apa yang dimaksud dengan fungsi promisify pada Node.js dan bagaimana cara menggunakannya?
Jawaban: Fungsi util.promisify digunakan untuk mengubah fungsi asynchronous callback-based menjadi Promise-based pada Node.js. 
Promisify hanya bekerja pada fungsi asynchronous yang menerapkan Node.js callback-style.
#

Apa yang terjadi pada keadaan pending dalam objek Promise?
Jawaban: Objek Promise sedang berjalan.
#

Berikut ini adalah pernyataan yang tepat mengenai dev dependencies, kecuali...
Jawaban: Secara default package npm yang ditambahkan termasuk dalam dev dependencies.
#

Manakah dari pilihan berikut ini yang bukan merupakan fungsi file package-lock.json?
Jawaban: Menyimpan informasi package global yang digunakan.
#

Berikut ini adalah beberapa alasan perlu menerapkan automated testing, kecuali...
Jawaban: Meningkatkan kecepatan dan performa aplikasi.
#

Anda memiliki skenario pengujian seperti berikut:
```javascript
test('should return the minimum number between 3 arguments', () => {
    expect(findMin(1, 2, 3)).toEqual(1);
    expect(findMin(5, 1, 2)).toEqual(1);
    expect(findMin(102, 404, 48)).toEqual(48);
    expect(findMin(-1, 0, -1)).toEqual(-1);
    expect(findMin(2, 2, 2)).toEqual(2);
});
```
Ada banyak cara atau algoritma untuk memenuhi skenario di atas. Pilihlah fungsi yang gagal memenuhi pengujian tersebut!
Jawaban: 
```javascript
function findMin(a, b, c) {
    let minValue = 0;

    if (a < b) {
        minValue = a;
    } else if (b < c) {
        minValue = b;
    } else {
        minValue = c;
    }

    return minValue;
}
```
#
 
