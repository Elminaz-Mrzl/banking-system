# 🏦 Core Java Banking Simulation

Bu layihə Java proqramlaşdırma dilinin təməl prinsiplərini (OOP) real biznes ssenarisi üzərində tətbiq etmək üçün hazırlanmışdır.

## 🎯 Layihənin Memarlıq Özəllikləri
- **Layered Architecture:** Kodun idarəolunması üçün model, service, exception və util paketlərinə bölünməsi.
- **Abstraction & Polymorphism:** `Account` abstract class və `BankOperations` interfeysi vasitəsilə çevik struktur.
- **Data Integrity:** `Map` və `List` strukturlarından istifadə edərək məlumatların sürətli axtarışı və tarixçənin saxlanılması.
- **Custom Exception Handling:** Sistemin dayanıqlılığı üçün xüsusi `BankSystemException` sinfinin tətbiqi.

## 🛠 Texniki Detallar
- **Transaction History:** Hər bir hesab üçün fərdi əməliyyat tarixçəsinin (mədaxil/məxaric/transfer) izlənilməsi.
- **Validation Logic:** Transfer zamanı mənfi məbləğ, mövcud olmayan hesab və kifayət etməyən balans yoxlamaları.
- **UUID Logic:** Hesablar üçün unikal identifikatorların avtomatik yaradılması.

## 📈 Gələcək Planlar
- Məlumatların fayllarda (Database simulyasiyası) saxlanılması.
- JUnit ilə vahid (Unit) testlərin yazılması.
- Multi-threading vasitəsilə eyni anda çoxlu əməliyyatların dəstəklənməsi.

---
*Bu layihə mənim Java inkişaf yolumda ilk peşəkar addımımdır.*
