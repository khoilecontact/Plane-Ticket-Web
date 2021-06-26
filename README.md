# PlaneTicket_Web.
DA SE104

## Aplication Structure:
```bash

.
|
|_ public
|       |_ images
|       |_ styles
|       |_ script
|
|_ views
|       |_ home.pug
|       |_ bill.view
|                   |_ billDeposit.view.pug
|                   |_ billFullPaid.view.pug
|       |_ discovery.view
|                       |_ HCM.view.pug
|                       |_ HaNoi.view.pug
|                       |_ DaNang.view.pug
|                       |_ PhuQuoc.view.pug
|                       |_ QuyNhon.view.pug
|
|
|
|_ controller
|           |_ admin.controller
|           |_ user.controller
|           |_ public.controller
|
|_ routes
|       |_ users.route
|                   |_ myProfile.route/ myProfile.route.js
|                   |_ ticket.route
|                               |_ ticketDeposit.route.js
|                               |_ ticketFullPaid.route.js
|       |_ admin.route
|                   |_ revenueReport.route.js
|                   |_ flightSettings.route.js
|       |_ public.route
|                   |_ bookInfor.route
|                                   |_ book.route
|                                               |_ book.route.js
|                                               |_ booking.route.js //BM2
|                                               |_ seatBooking.route.js //BM3
|                                               |_ question.route.js
|                                   |_ condition.route
|                                                   |_ policy.route.js
|                   |_ flight.route
|                               |_ flightSearching.route / flightSearching.route.js //BM5
|                               |_ airport.route
|                                               |_ localairport.route.js
|                                               |_ globalairport.route.js
|                               |_ luggage.route
|                                               |_ signedLuggage.route.js
|                                               |_ handedLuggage.route.js
|                                               |_ lostLuggage.route.js
|                   |_ discovery.route
|                                   |_ discovery.route.js
|                   |_ service.route
|                                   |_ cuisine.route.js
|                                   |_ tips.route.js
|
|                   |_ login.
|
app.js //server.
db.json //database.

by KhoiLe.
```

## Contributors:
<a href="https://www.facebook.com/tsone.ylov">
    <img src="https://avatars.githubusercontent.com/u/69576826?v=4" width="50px" />
</a>

<a href="https://www.facebook.com/khoi.le.quan">
    <img src="https://github.com/khoilecontact.png?size=400" width="50px" />
</a>

<a href="https://www.facebook.com/profile.php?id=100015743228561">
    <img src="https://avatars.githubusercontent.com/huyvouit" width="50px"/>
</a>

<a href="https://www.facebook.com/profile.php?id=100015655094206">
    <img src="https://gamek.mediacdn.vn/133514250583805952/2020/3/4/photo-1-15833137511761959128634.jpg" width="50px" height="50px"/>
</a>

<a href="https://www.facebook.com/profile.php?id=100010591908074">
    <img src="https://avatars.githubusercontent.com/u/80504187?s=400&u=28c5b2ded2fb2a567a2ccb49d7fba444af0e3660&v=4" width="50px" height="50px"/>
</a>
