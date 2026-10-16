QueueLess — Updated single-site prototype

Open index.html. Admin login is in the top-right.
Demo username: admin2026
Demo password: Qless#26

Updates:
- Optional service fees: leave blank for no fee; each service can have its own fee.
- Fees are shown on the service card and generated ticket only when configured.
- Admin can add services, edit fee and working days, set counter count/names, and delete services.
- Government services can be marked as closed on Saturdays and Sundays. Booking is blocked on those days with an English notice. Other services follow their own Sunday setting.
- Existing token history remains if a service is deleted.

Important: this is a browser-based prototype. Data is stored in the current browser only and is not shared across devices. Admin credentials are checked in frontend JavaScript, so connect a secure backend/database before public production use. QR generation uses an external QR image service and needs an internet connection.
