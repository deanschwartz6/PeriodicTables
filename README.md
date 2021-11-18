# Dean Schwartz - Periodic Tables Project
This is an app for a mock company Periodic Tables. In is intended to be used by the staff when they get a call from a customer to reserve a table. In this application you can create a reservation, create a new table, search for reservations by phone number, seat a reservation at a valid table, finish a table when the customer is done, and cancel or edit reservations.

### **Links**
Front End
> https://periodic-tables-front-end-dean.herokuapp.com/
Back End
> https://periodic-tables-front-back-dean.herokuapp.com/

# API Documentation  
### ``/reservations``  

``/reservations``  
Returns the list of reservations  
  return
GET ``?date=YYYY-MM-DD``  
Returns a list of reservations made for that date  
Ex. ``?date=2026-12-30``  
Returns:
  {"data":
      [
          {"reservation_id":5,
          "first_name":"Anthony",
          "last_name":"Charboneau",
          "mobile_number":"620-646-8897",
          "reservation_date":"2026-12-30T00:00:00.000Z",
          "reservation_time":"18:00:00",
          "people":2,
          "status":null,
          "created_at":"2020-12-10T08:31:32.326Z",
          "updated_at":"2020-12-10T08:31:32.326Z"}
      ]
  }
