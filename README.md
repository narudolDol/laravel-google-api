
## Google

- [ไปที่ Google Api Console.](https://console.cloud.google.com/apis).
- เลือกเมนู Dashborad -> คลิกที่ Enable apis and service ->ค้นหา google calendar api -> enable.
- เลือกเมนู Credentials -> คลิกที่ Create credentials และเลือก Service account-> ตั้งชื่อ service ตามต้องการ และกด done.
- หลังจากสร้าง service account แล้วจะ redirect มาในหน้า list รายการ ให้ทำการเลือก service account ที่เราสร้างขึ้นมา -> คลิกที่ Add key และเลือก Create new key -> เลือก format JSON
- Rename file JSON เป็น service-account-credentials.json แล้ว copy file ไปที่ storage/app/google-calendar/service-account-credentials.json
- [Ref.](https://github.com/spatie/laravel-google-calendar)

## Laravel
- composer install.
- php aritsan serv
- Server start:127.0.0.1:8000/


