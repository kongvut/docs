# เอกสารและคู่มือสำหรับ Laravel 7.x

นี่คือเอกสารของ Laravel เวอร์ชั่นภาษาไทยที่แปลจากเอกสารหลัก https://github.com/laravel/docs

- Prologue
    - [Release Notes](releases.md)
    - [Upgrade Guide](upgrade.md)
    - [Contribution Guide](contributions.md)
    - [API Documentation](https://laravel.com/api/7.x)
- Getting Started
    - [Installation](installation.md)
    - [Configuration](configuration.md)
    - [Directory Structure](structure.md)
    - [Homestead](homestead.md)
    - [Valet](valet.md)
    - [Deployment](deployment.md)
- Architecture Concepts
    - [Request Lifecycle](lifecycle.md)
    - [Service Container](container.md)
    - [Service Providers](providers.md)
    - [Facades](facades.md)
    - [Contracts](contracts.md)
- The Basics
    - [Routing](routing.md)
    - [Middleware](middleware.md)
    - [CSRF Protection](csrf.md)
    - [Controllers](controllers.md)
    - [Requests](requests.md)
    - [Responses](responses.md)
    - [Views](views.md)
    - [URL Generation](urls.md)
    - [Session](session.md)
    - [Validation](validation.md)
    - [Error Handling](errors.md)
    - [Logging](logging.md)
- Frontend
    - [Blade Templates](blade.md)
    - [Localization](localization.md)
    - [Frontend Scaffolding](frontend.md)
    - [Compiling Assets](mix.md)
- Security
    - [Authentication](authentication.md)
    - [Authorization](authorization.md)
    - [Email Verification](verification.md)
    - [Encryption](encryption.md)
    - [Hashing](hashing.md)
    - [Password Reset](passwords.md)
- Digging Deeper
    - [Artisan Console](artisan.md)
    - [Broadcasting](broadcasting.md)
    - [Cache](cache.md)
    - [Collections](collections.md)
    - [Events](events.md)
    - [File Storage](filesystem.md)
    - [Helpers](helpers.md)
    - [HTTP Client](http-client.md)
    - [Mail](mail.md)
    - [Notifications](notifications.md)
    - [Package Development](packages.md)
    - [Queues](queues.md)
    - [Task Scheduling](scheduling.md)
- Database
    - [Getting Started](database.md)
    - [Query Builder](queries.md)
    - [Pagination](pagination.md)
    - [Migrations](migrations.md)
    - [Seeding](seeding.md)
    - [Redis](redis.md)
- Eloquent ORM
    - [Getting Started](eloquent.md)
    - [Relationships](eloquent-relationships.md)
    - [Collections](eloquent-collections.md)
    - [Mutators](eloquent-mutators.md)
    - [API Resources](eloquent-resources.md)
    - [Serialization](eloquent-serialization.md)
- Testing
    - [Getting Started](testing.md)
    - [HTTP Tests](http-tests.md)
    - [Console Tests](console-tests.md)
    - [Browser Tests](dusk.md)
    - [Database](database-testing.md)
    - [Mocking](mocking.md)
- Official Packages
    - [Cashier (Stripe)](billing.md)
    - [Cashier (Paddle)](cashier-paddle.md)
    - [Cashier (Mollie)](https://github.com/laravel/cashier-mollie)
    - [Dusk](dusk.md)
    - [Envoy](envoy.md)
    - [Horizon](horizon.md)
    - [Passport](passport.md)
    - [Sanctum](sanctum.md)
    - [Scout](scout.md)
    - [Socialite](socialite.md)
    - [Telescope](telescope.md)
    
## แนวทางการร่วมแปลเอกสาร (Contribution)

หากท่านต้องการร่วมช่วยแปลเอกสาร Laravel เป็นภาษาไทย สามารถทำได้ทั้งนี้

1. ท่านจำเป็นต้องขอเข้าร่วม Trello ผ่านลิงก์นี้ https://trello.com/b/MA84SE9
2. จากนั้นให้เลือกหัวข้อที่ท่านสนใจแล้วเพิ่ม Task ที่หมวดหมู่ "กำลังทำ" พร้อม Assign เป็น User ตัวเองที่รับผิดชอบ
3. ขั้นตอนต่อมาให้ Fork โปรเจคนี้ไปเป็นของตัวเอง
4. เมื่อแปลเอกสารเสร็จเรียบร้อยแล้วส่งให้ Pull request มาที่ Branch `7.x-TH`
5. เมื่อผู้ดูแลโปรเจคตรวจสอบความถูกต้องเรียบร้อยแล้วจะทำการ Merge pull request มาที่ Repository นี้เป็นอันเสร็จเรียบร้อย
