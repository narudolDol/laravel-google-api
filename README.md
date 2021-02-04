
## Google

- [ไปที่ Google Api Console.](https://console.cloud.google.com/apis).
- เลือกเมนู Dashborad -> คลิกที่ Enable apis and service ->ค้นหา google calendar api -> enable.
- เลือกเมนู Credentials -> คลิกที่ Create credentials และเลือก Service account-> ตั้งชื่อ service ตามต้องการ และกด done.
- หลังจากสร้าง service account แล้วจะ redirect มาในหน้า list รายการ ให้ทำการเลือก service account ที่เราสร้างขึ้นมา -> คลิกที่ Add key และเลือก Create new key -> เลือก format JSON
- Rename file JSON เป็น service-account-credentials.json แล้ว copy file ไปที่ storage/app/google-calendar/service-account-credentials.json
- [ไปที่ google calendar setting](https://calendar.google.com/calendar/u/0/r/settings)
- ทำการสร้าง calendar -> ไปที่เมนูตั้งค่า calendar เลือกcalendar ที่สร้างขึ้นมา-> ไปที่ใช้ร่วมกับบุคคลอื่น แล้ว เพิ่ม google carlendar service ที่สร้างขึ้นมา เช่น         booking@testmikotik.iam.gserviceaccount.com
- copy calendar id ไปใส่ใน .env GOOGLE_CALENDAR_ID="google calendar id"
- [Ref.](https://github.com/spatie/laravel-google-calendar)


## Laravel
- composer install.
- php aritsan serv
- Server start:127.0.0.1:8000/


