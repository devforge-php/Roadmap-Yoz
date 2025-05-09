
Quyida siz uchun **"Start-Middle darajadagi Data Structures Roadmap"** tayyorladim. Bu roadmap:

- Oddiydan murakkabga qarab tashkil etilgan
- Har bir mavzu uchun izoh va misollar bor
- Mustahkamlash uchun amaliy mashqlar ham berilgan

---

# 🧠 **Data Structures Roadmap – Start to Middle Level**

## 🔹 Nima Uchun Ma'lumotlar Tuzilmasini Bilmalik Kerak?

- Dastur tezligini oshirishda yordam beradi
- Katta loyihalarda ma'lumotlarni samarali saqlash va ishlash imkonini beradi
- Interviewlarda ko'p so'raladigan mavzu
- Algoritmlar bilan bog'liq barcha narsaning asosi

---

## 🟡 MODUL 1: Asosiy Tushunchalar (Week 1)

### Mavzular:
| Mavzu | Izoh |
|------|------|
| Ma'lumotlar tuzilmasi nima? | Dasturlashda ma'lumotlarni saqlash usullari |
| Primitive vs Non-primitive turlar | int, float, char → vs → array, list, object |
| Time Complexity (Big O Notation) | Kodning tezligini o'lchash usuli |
| Space Complexity | Xotirani qancha egallashi |

### Amaliy Mashqlar:
- 1 dan N gacha bo'lgan sonlarni yig'indisini hisoblovchi funksiya yozing (O(1) vs O(n) usulda)
- `for`, `while` bilan massiv elementlarini aylangan holda chiqaring

---

## 🟢 MODUL 2: Linear Data Structures (Week 2–3)

Bu yerda ma'lumotlar ketma-ketlikda saqlanadi.

### Mavzular:
| Tuzilma | Foydalanish joyi | Murakkablik (Time) |
|--------|------------------|--------------------|
| Array / Massiv | Bir turdagi ma'lumotlarni saqlash | O(1) - access, O(n) - insert/delete |
| Dynamic Array | O'lchami o'zgaruvchan massiv | O(1) amortized |
| Linked List | Elementlar bog'langan zanjir | O(n) - search, O(1) - insert head |
| Stack | Oxirgi kirgan birinchi chiqadi (LIFO) | Push/pop O(1) |
| Queue | Birinchi kirgan birinchi chiqadi (FIFO) | Enqueue/dequeue O(1) |
| Deque | Ikkala tarafdan o'zgartirish mumkin bo'lgan queue | - |

### Amaliy Mashqlar:
- Stack orqali `palindrome` tekshiruvchi funksiya yozing
- Queue yordamida `BFS (breadth-first search)` algoritmini sinash
- Linked Listga yangi element qo'shish, o'chirish funksiyasini yozing

---

## 🔵 MODUL 3: Tree & Graph (Week 4–5)

### Mavzular:
| Tuzilma | Izoh |
|--------|------|
| Trees (Binary Tree, BST) | Ma'lumotlarni daraxt shaklida saqlash |
| Binary Search Tree (BST) | Qiymatlarga qarab chap/ong sub-tree hosil qilinadi |
| Heap (Min Heap, Max Heap) | Priority queue yaratishda ishlatiladi |
| Hash Table | Key-value tarzida ma'lumot saqlash |
| Graph | Node’lar orasidagi aloqalar (social network, map) |

### Qisqacha Murakkabliklar:
| Struktura | Insert | Search | Delete |
|----------|--------|--------|--------|
| Binary Search Tree | O(log n) | O(log n) | O(log n) |
| Hash Table | O(1) avg | O(1) avg | O(1) avg |
| Heap | O(log n) | O(n) | O(log n) |

### Amaliy Mashqlar:
- BST ga qiymat qo’shish va qidirish funksiyasi yozing
- Hash collisionni hal qiluvchi `chaining` metodi yozing
- Graphga node qo’shish, edge qo’shish funksiyasini yozing

---

## 🔴 MODUL 4: Advanced Structures (Week 6)

### Mavzular:
| Tuzilma | Foydalanish joyi |
|--------|------------------|
| Trie | Avtomatik to'ldirish (search suggestion) |
| Segment Tree | Range query (sum, min, max) |
| Fenwick Tree (Binary Indexed Tree) | Prefix sum tez hisoblash |
| Disjoint Set Union (Union-Find) | Graflarda komponentlarni topish |
| Bloom Filter | Tez tekshiruv uchun ehtimoliy struktura |

### Amaliy Mashqlar:
- So'zlar ro'yxatidan foydalanib `Trie` yaratish
- Union-Find yordamida 2 ta node bog'langanligini tekshirish

---

## 🟣 MODUL 5: Real-life Masalalar (Week 7)

Bu modul orqali hamma narsani amalda qo'llashingiz mumkin.

### Misol masalalar:
- Stack yordamida `valid parentheses` tekshiruvi
- Queue yordamida `rotten oranges` masalasi (matrixda BFS)
- Hash Table yordamida `two sum` masalasi
- BST yordamida `lowest common ancestor` topish
- Graphda `DFS` orqali sikl bor-yo'qligini aniqlash

---

## 📚 Manbalar (Uzbek tilida ham topishingiz mumkin):

### Ingliz tilida:
- [GeeksforGeeks - Data Structures](https://www.geeksforgeeks.org/data-structures/)
- [freeCodeCamp YouTube - Data Structures Full Course](https://www.youtube.com/watch?v=t2CEgPsws3U)
- [The Coding Interview Bootcamp (Udemy)](https://www.udemy.com/course/coding-interview-bootcamp-algorithms-and-data-structure/)

### O'zbek tilida:
- YouTube: "Data Structures in Uzbek", "Algoritmlar" kanallar
- Telegram: @dasturchilar_uchun, @programming_books_uz

---

## ✅ Yakuniy Natija

Agar ushbu reja bo'yicha har kuni 1-2 soat ajratgan bo'lsangiz:

✅ **Middle levelga mos Data Structures**ni mukammal o'zlashtirasiz  
✅ **Kod yozishda tezlik, xotira foydalanishini optimallasiz**  
✅ **Tech intervyuda keng qamrab olinadigan savollarga tayyorgarlik ko'rasiz**  
✅ **Real proyektlarda samarali ma'lumot saqlashni o'rganasiz**

---

> 💡 **Maslahat:** Har bir ma'lumot tuzilmasi uchun alohida test loyiha yoki notebook oching. Masalan:
> - `array_vs_linkedlist.php`
> - `stack_palindrome_check.php`
> - `bst_insert_search.php`

---


