# 🅿️ Slot Booking Module

## ✅ Purpose  
The Slot Booking module manages viewing, reserving, confirming, extending, and releasing parking slots while preventing double-booking.

---

## 🔄 Booking Flow  
1. Check availability  
2. Create a HOLD (valid for 10 minutes)  
3. Confirm booking  
4. Check-in (start parking time)  
5. Extend time (if no conflict)  
6. Check-out (billing)  
7. Auto-expire HOLD if not confirmed  

---

## 📌 Booking Status  
| Status | Meaning |
|--------|---------|
| HOLD | Temporary reservation |
| CONFIRMED | Final booking before user arrives |
| ACTIVE | User checked in |
| COMPLETED | User checked out |
| CANCELLED | User cancelled |
| EXPIRED | HOLD expired |

---

## 🗃️ Required Fields  
- slotId  
- userId  
- startTime  
- endTime  
- status  
- holdExpiresAt  
- checkinTime  
- checkoutTime  
- amount  

---

## 🔌 API Endpoints

### ✅ 1. Get Available Slots  
`GET /slots/available?start=ISO&end=ISO&type=CAR`

---

### ✅ 2. Create HOLD  
`POST /booking/hold`
```json
{
  "slotId": 1,
  "userId": "U123",
  "start": "2025-11-06T10:00",
  "end": "2025-11-06T12:00"
}
