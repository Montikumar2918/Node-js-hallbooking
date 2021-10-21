Nodejs-HallBooking :-

use the link https://hall-books.herokuapp.com/createrooms with post method
the request body should be like below:-

{  
  "roomname" : "Sweedon",
	"seats" : 50,
	"amenties" : "WIFI,LED,Ac,Referigrator,projector",
	"price(1hr)" : "500"
}


For booking rooms:-
use the link with post method https://hall-books.herokuapp.com/bookrooms/{insertedid}
( https://hall-books.herokuapp.com/bookrooms/61711dc8b90789473a673de5)
the request body should be like below:-
{
   "customerName" : "Monti kumar",
   "date" : "2-112021",
   "startTime" : "10 am",
   "endTime" :"11 pm"   		
}

For getting Rooms with customer details:-
use the link with get method https://hall-books.herokuapp.com/bookrooms/rooms

For getting customers with their booked rooms
use the link with get method https://hall-books.herokuapp.com/bookrooms/customers
