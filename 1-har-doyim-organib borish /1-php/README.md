# PHP va OOP Bo‘yicha To‘liq Qo‘llanma (Fundamental Bilimlar Uchun)

Bu qo‘llanma PHP va OOPni chuqur o‘rganish uchun mo‘ljallangan. Laravel bilan ishlashni boshlashdan oldin, yoki umumiy dasturlash madaniyatini oshirish uchun PHP tilining o‘zini yaxshi tushunib olish zarur. Quyidagi yo‘l xarita orqali siz PHPni mustahkam o‘rganib olishingiz mumkin.

---

## 1. PHP Asoslari

### 1.1. PHP Sintaksisi

* PHP fayl boshlanishi: `<?php`
* Echo va print: `echo "Hello";`, `print "Salom";`
* Izohlar: `//`, `/* */`
* O'zgaruvchilar: `$ism = "Azizbek";`

### 1.2. Ma'lumot turlari

* Integer, Float, String, Boolean, Null
* Array: Indexed, Associative va Multidimensional
* Type juggling (PHPda avtomatik tip o‘zgarishi)
* Type hinting (PHP 7+)

### 1.3. Operatorlar

* Arifmetik: `+`, `-`, `*`, `/`, `%`
* Taqqoslash: `==`, `===`, `!=`, `<`, `>`
* Mantiqiy: `&&`, `||`, `!`
* Bitwise, Ternary operator (`? :`), Null coalescing operator (`??`)

### 1.4. Shart va Takrorlash

* `if`, `else`, `elseif`, `switch`
* `while`, `do-while`, `for`, `foreach`

### 1.5. Funktsiyalar

* Oddiy funksiyalar
* Default qiymatlar
* Scope (local va global o‘zgaruvchilar)
* `return` operatori
* Anonymous (lambda) funksiyalar
* Callback funksiyalar

### 1.6. Fayl bilan ishlash

* `fopen`, `fread`, `fwrite`, `fclose`
* `file_get_contents`, `file_put_contents`
* JSON bilan ishlash: `json_encode`, `json_decode`

### 1.7. Superglobal o‘zgaruvchilar

* `$_GET`, `$_POST`, `$_REQUEST`, `$_SESSION`, `$_COOKIE`, `$_FILES`, `$_SERVER`

### 1.8. Error Handling

* `try`, `catch`, `finally`
* `throw new Exception()`
* PHP Error Levels

---

## 2. PHP OOP Asoslari

### 2.1. Class va Object

* Sinf yaratish
* Ob’yektdan foydalanish (`new` kalit so‘zi)
* `$this` operatori

### 2.2. Access Modifiers

* `public`, `private`, `protected`
* Getter va Setter funksiyalar orqali xususiyatlarni boshqarish

### 2.3. Constructor va Destructor

* `__construct()` va `__destruct()` funksiyalari

### 2.4. Static Xususiyatlar va Metodlar

* `static` kalit so‘zi
* `self::` va `ClassName::`

### 2.5. Inheritance (Meros olish)

* `extends` kalit so‘zi
* `parent::` orqali ota klassga murojaat qilish

### 2.6. Interfaces va Abstract sinflar

* `interface` va `implements`
* `abstract class` va `abstract function`
* Nega kerak? - Arxitekturaviy soddalashtirish uchun

### 2.7. Traits

* `trait` kalit so‘zi
* Traitlar orqali kodni qayta ishlatish

### 2.8. Namespaces

* `namespace` kalit so‘zi
* `use` orqali import qilish

### 2.9. Autoloading

* PSR-4 standarti
* Composer `autoload`

---

## 3. PHPda Amaliy OOP Misollar

* **Model-Controller tuzilmasi (mini-MVC)**
* **Kichik loyiha yaratish:** Mahsulotlar katalogi, foydalanuvchi ro‘yxatdan o‘tishi
* **Fayl yuklash**, **formani validatsiya qilish**, **sessions** bilan ishlash

---

## 4. PHPda Clean Code yozish

* DRY (Don't Repeat Yourself)
* KISS (Keep It Simple, Stupid)
* SRP (Single Responsibility Principle)
* Kodni bo‘lish (fayllarga, modullarga ajratish)

---

## 5. Composer va Paketlar

* Composer nima?
* `composer.json`, `require`, `autoload`
* Paket o‘rnatish va o‘z paketini yaratish

---

## 6. Test yozish (Optional, lekin foydali)

* PHPUnit asoslari
* Oddiy test yozish
* Unit va Integration testlar

---

## 7. Yakuniy Maslahatlar

* PHP rasmiy dokumentatsiyasi: [php.net](https://www.php.net/)
* PHP Cheat Sheet tayyorlab olish
* 1-2ta real loyiha qilish: form validatsiyasi, session orqali login, file upload
* `spl_autoload_register`, `__toString`, `__call` kabi sehrli metodlar bilan tanishib chiqish

---

Bu yo‘l xarita senga PHP va OOPni **frameworklarsiz ham mustaqil o‘rganish** uchun to‘liq asos beradi. Laravelga o‘tganingda bu bilimlar juda foydali bo‘ladi.
