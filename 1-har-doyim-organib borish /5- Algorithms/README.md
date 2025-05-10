

Quyida siz uchun **"Start to Middle Level Algorithms Roadmap"** tayyorladim. Bu roadmap:

- Oddiydan murakkabga qarab tuzilgan
- Har bir mavzu uchun izoh, misol va kerakli amaliy mashqlar bor
- PHP tilini asos qilib olgan holda (siz uchun)

---

# 🧠 **Algorithms Roadmap – Start to Middle Level**

## 🔹 Nima Uchun Algoritmlarni Bilmalik Kerak?

- Dastur tezligini oshiradi
- Katta hajmli ma'lumotlar bilan ishlashni o'rgatadi
- Tech intervyularda keng so'raladigan mavzu
- Real loyihalarda optimallashtirish imkonini beradi

---

## 🟡 MODUL 1: Kirish & Asosiy Tushunchalar (Week 1)

### Mavzular:
| Mavzu | Izoh |
|------|------|
| Algoritm nima? | Ma'lum bir vazifani bajarish uchun ketma-ket buyruqlar to'plami |
| Time Complexity (Big O Notation) | Kodning tezligini o'lchash usuli |
| Space Complexity | Xotirani qancha egallashi |
| Recursion | O'zini o'zi chaqiruvchi funksiya |

### Amaliy Mashqlar:
- `n` sonining faktorialini rekursiv yozing
- Fibonachchi sonlarini rekursiya vs iterativ tarzda hisoblang
- Big O toping: quyidagi kod uchun (`O(n^2)` yoki `O(1)`)

---

## 🟢 MODUL 2: Sortlash Algoritmlari (Week 2–3)

### Mavzular:
| Algoritm | Vaqt Murakkabligi | Izoh |
|---------|--------------------|------|
| Bubble Sort | O(n²) | Eng oddiy, lekin sekin |
| Selection Sort | O(n²) | Minimal elementni topib joylashtiradi |
| Insertion Sort | O(n²) | Qo'l kartalari tartiblashga o'xshaydi |
| Merge Sort | O(n log n) | Divide and Conquer |
| Quick Sort | O(n log n) avg | Pivot bo'yicha ajratadi |
| Counting Sort | O(n + k) | Butun sonlar uchun juda tez |
| Radix Sort | O(nk) | Sonlarni xona-xona tartiblaydi |

### Amaliy Mashqlar:
- Massivni Merge Sort yordamida tartibla
- QuickSort algoritmini yozing
- `array_sort()` ni o'zgartirish orqali turli sort algoritmlarini solishtiring

---

## 🔵 MODUL 3: Qidiruv Algoritmlari (Week 4)

### Mavzular:
| Algoritm | Vaqt Murakkabligi | Izoh |
|---------|---------------------|------|
| Linear Search | O(n) | Birma-bir tekshirish |
| Binary Search | O(log n) | Tartiblangan massivda qidirish |
| Ternary Search | O(log₃ n) | Rare foydalaniladi |
| Jump Search | O(√n) | Cheklarni sakrab o'tish |

### Amaliy Mashqlar:
- Tartiblangan massivda Binary Search yordamida qiymat toping
- So'z topish o'yinida linear vs binary searchni taqqoslang

---

## 🔴 MODUL 4: Graph Algoritmlari (Week 5–6)

### Mavzular:
| Algoritm | Foydalanish joyi |
|---------|------------------|
| BFS (Breadth First Search) | Eng qisqa yo'l, level order traversal |
| DFS (Depth First Search) | Rekursiv, connected component, cycle detection |
| Dijkstra’s Algorithm | Weighted graphda eng qisqa yo'l |
| Floyd-Warshall | Barcha node’lar orasidagi eng qisqa yo'l |
| Prim & Kruskal | MST (Minimum Spanning Tree) topish |
| Topological Sorting | Dependency bilan ishlash (masalan: task tartibi) |

### Amaliy Mashqlar:
- BFS yordamida social networkdagi do'stlarni toping
- DFS bilan sikl bor-yo'qligini aniqlang
- Dijkstra’s algoritmi bilan Google Maps model yaratish

---

## 🟣 MODUL 5: Greedy, DP, Backtracking (Week 7–8)

### Mavzular:
| Algoritm | Izoh |
|---------|------|
| Greedy Algorithms | Har safar eng yaxshi tanlov qilinadi |
| Dynamic Programming (DP) | Murakkab masalani maydaroq qismga bo'lib yechish |
| Memoization | Eski natijalarni eslab qolish |
| Tabulation | Iterativ DP |
| Backtracking | Masala yechimini sinovdan o'tkazish |

### Amaliy Mashqlar:
- Coin Change (greedy vs dynamic programming)
- Knapsack problem (DP)
- N-Queen (backtracking)
- Fibonacci sonlarini memoization bilan yozish

---

## 🟤 MODUL 6: String Matching (Week 9)

### Mavzular:
| Algoritm | Foydalanish joyi |
|---------|------------------|
| Naive Pattern Matching | Oddiy qidiruv |
| KMP (Knuth-Morris-Pratt) | Keyingi tekshiruvlarni optimallashtiradi |
| Rabin-Karp | Hash yordamida pattern qidiruv |
| Trie with Autocomplete | Avtomatik to'ldirish |
| Regular Expressions | Matn ichida pattern qidirish |

### Amaliy Mashqlar:
- So'z matnda necha marta takrorlanayotganini hisoblovchi funksiya yozing
- KMP algoritmini PHPda implement qiling

---

## 🟠 MODUL 7: Amaliy Masalalar (Week 10)

Bu modul orqali hamma narsani amalda qo'llashingiz mumkin.

### Misol masalalar:
- Two Sum (Hash Table)
- Longest Substring Without Repeating Characters (Sliding Window)
- Merge Intervals
- Find Cycle in a Linked List
- LRU Cache Implementation
- Anagram tekshirish
- Palindrome tekshirish
- Spiral Matrix traversal

---

## 📚 Manbalar (Uzbek tilida ham topishingiz mumkin):

### Ingliz tilida:
- [GeeksforGeeks - Algorithms](https://www.geeksforgeeks.org/fundamentals-of-algorithms/)
- [freeCodeCamp YouTube - JavaScript Data Structures and Algorithms](https://www.youtube.com/watch?v=zg-ddPbzcKM)
- [The Algorithm Design Manual (Steven Skiena)](https://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693)

### O'zbek tilida:
- YouTube: "Algoritmlar", "DSA in Uzbek"
- Telegram: @dasturchilar_uchun, @programming_books_uz

---

## ✅ Yakuniy Natija

Agar ushbu reja bo'yicha har kuni 1-2 soat ajratgan bo'lsangiz:

✅ **Middle levelga mos Algoritmlarni mukammal o'zlashtirasiz**  
✅ **Kod yozishda tezlik, xotira foydalanishini optimallasiz**  
✅ **Tech intervyuda keng qamrab olinadigan savollarga tayyorgarlik ko'rasiz**  
✅ **Real proyektlarda samarali masalalarni hal etasiz**

---

> 💡 **Maslahat:** Har bir algoritm uchun alohida test loyiha yoki notebook oching. Masalan:
> - `bubble_sort.php`
> - `binary_search.php`
> - `fibonacci_memoization.php`

---

