# FSAD-End-Sem-lab-exam

1. Add Booking
2. 1. Add Booking
Method: POST
URL:
http://localhost:8080/booking/add

{  
"bookingId": 101,
"name": "Kishor", 
"bookingDate": "2026-04-27",  
"status": "Confirmed", 
"email": "kishor@gmail.com", 
"phoneNumber": "9876543210"
}

2. Delete Booking
Method: DELETE
URL:
http://localhost:8080/booking/delete/101

**Expected Output**:
POST Output
Booking added successfully
DELETE Output
Booking deleted successfully

