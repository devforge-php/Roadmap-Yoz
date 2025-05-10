## 3 Oylik Go Backend Developer Rejasi (Junior+ darajaga yetish uchun)

**Maqsad:** 3 oy ichida Junior+ Go Backend Developer bo‘lish, 3-oydan keyin haqiqiy loyihalarni muhitida ishlash (microservices va/yoki monolit arxitekturasi), qo‘shimcha vositalar bilan tanishish va Udevs kompaniyasiga middle darajada topshirishga tayyor bo‘lish.

---

### 1-OY: Go tili va asosiy backend konseptlar (Junior darajaga)\*\*

#### 1-Hafta – Go asoslari

* Go o‘rnatish, IDE sozlash (VS Code/GoLand)
* `package`, `func`, `main`
* O‘zgaruvchilar, shart operatorlari, `for`, `switch`
* `array`, `slice`, `map`, `struct`

*Natija:* Kichik CLI dastur yozing (ma'lumotni slice-ga saqlash va konsolga chiqarish).

#### 2-Hafta – Go chuqur

* Pointerlar, `interface`, `defer`, `panic`/`recover`
* Fayl I/O va JSON parse qilish
* Goroutines va Channels, `select`

*Natija:* JSON faylni o‘qiydigan va paralel ravishda log yozuvchi mini-servis.

#### 3-Hafta – REST API va router

* `net/http` bilan CRUD endpointlar
* Router: `gin` yoki `chi`
* Middleware (logging, recovery)

*Natija:* Todo API: Create, Read, Update, Delete.

#### 4-Hafta – Test va loyiha tuzilishi

* Unit test (`testing` package)
* Project structure: `cmd/`, `internal/`, `pkg/`
* Logger (`logrus` yoki `zap`)
* Config (.env bilan `viper`)

*Natija:* Test qoplamasi ≥70% bo‘lgan kichik API loyiha.

---

### 2-OY: Ma'lumotlar bazasi, Auth, konteynerizatsiya (Junior+ bosqich yakuni)\*\*

#### 5-Hafta – PostgreSQL va ORM

* PostgreSQL o‘rnatish
* SQL asoslari (`SELECT`, `JOIN`, `INSERT`)
* ORM: `gorm` yoki `sqlx`
* Migratsiyalar: `golang-migrate`

*Natija:* User-Post-Comment CRUD API.

#### 6-Hafta – Auth va xavfsizlik

* JWT token: yaratish, tekshirish
* Auth middleware
* Role-Based Access Control

*Natija:* Faqat ro‘yxatdan o‘tgan foydalanuvchi post qo‘sha oladigan API.

#### 7-Hafta – Docker & Docker-Compose

* Dockerfile yozish
* `docker-compose` bilan Go + Postgres
* Environment variables boshqarish

*Natija:* Lokalda Docker orqali to‘liq ishlaydigan servis.

#### 8-Hafta – CI/CD boshlang‘ich

* GitHub Actions bilan pipeline (test → build → docker image)
* README.md to‘liq hujjat

*Natija:* Har commit keyin CI ishlaydigan repo.

---

### 3-OY: Microservices, Monolit, Qo‘shimcha Vositalar va Deploy (Junior+ → Mid-Level tayyor)\*\*

#### 9-Hafta – Monolit vs Microservices

* Monolit arxitektura: afzallik/ Kamchilik
* Microservices: afzallik/ Kamchilik
* Service interfeysi: HTTP/gRPC

*Natija:* Bir monolit API-ni microservice-ga bo‘lish reja diagrammasi.

#### 10-Hafta – Message Broker va gRPC

* RabbitMQ yoki Apache Kafka kirish
* gRPC service yozish va client bilan bog‘lash
* Synchronous vs asynchronous kommunikatsiya

*Natija:* gRPC orqali inter-service call qiladigan ikki xizmat (auth va user profile).

#### 11-Hafta – Kubernetes va observability

* Kubernetes basics: Pod, Deployment, Service
* Helm chart yozish
* Monitoring: Prometheus metrics va Grafana dashboard basics

*Natija:* K8s klasterda deploy qilingan microservice va unga monitoring.

#### 12-Hafta – Final deployment & Portfolio

* Cloud deploy: AWS/GCP/Render/Fly.io
* Domain va SSL (Let’s Encrypt)
* API dokumentatsiya: Swagger/OpenAPI
* GitHub portfolio va matchay CV

*Natija:* 2 xil arxitekturadagi (monolit va microservices) loyiha, CI/CD, monitoring, dokumentatsiya bilan.

---

## Roadmap yakuni va baholash

* **Junior daraja (1-oy oxiri):** Go asoslari, CRUD API, test yozish.
* **Junior+ daraja (2-oy oxiri):** DB, Auth, Docker, CI/CD.
* **Mid-level tayyor (3-oy oxiri):** Microservices yoki monolit kompleks loyiha, gRPC, broker, Kubernetes, observability, deploy.

Agar ushbu bosqichlarni to‘liq bajarsang, 3-oy oxirida real loyiha muhitida ishlash uchun yetarli tajriba va portfolio bo‘ladi. Udevs kompaniyasiga Middle Go Developer sifatida topshirishing mumkin.

**Omad tilayman!**
