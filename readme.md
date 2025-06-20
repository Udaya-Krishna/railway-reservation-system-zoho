Write a progam to book train tickets as per the details given below.

The program should first present a menu with the following options:

1. Book Ticket

2. Cancel Ticket

3. Print All

4. Print Availability

5. Exit

Details and conditions that are common

The train has only one coach with 16 berths (4 Lower, 4 Middie, 4 Upper, 2 Side Upper and 2 Side Lower)

14 confirmed tickets will be aloted a berth (4 Lower, 4 Middle, 4 Upper, 2 Side Upper)

The remaining 2 Side Lower berths are issued as 4 RAC tickets (Reservation against Cancellation)

No ticket for infants below 5 years of age

Wait list tickets should be issued for bookings beyond the confirmed 14 and 4 RAC.

There can only be 2 waitlist tickets

Book Ticket

When Book Ticket is chosen

It should prompt for the passenger details like:

Enter Name:

Enter Age

Enter Preference:

Do you want to book one more? (Y/N):

Kiasiinfants below age of 5 should also be accepted the same way.

After entering the details of all the passengers in the group, it should print the

ticket

Conditions for booking a ticket
When no berth preference is given for a passenger, the following rules should be applied:

Passengers with kids should be given a lower berth.

Passengers with age >60 should be alloted a lower berth, if available

if the preferred berth is not available, get confirmation from the passenger before booking the ticket.

Passengers travelling in groups should have the seats allotted together or placed close to each other

A ticket should be generated with a PNR number (can be a random unique number) and the seats allotted with the status

Print the details of the ticket after booking.

Cancel Ticket

Cancel Ticket is based on the PNR number.

After the PNR Number is provided, it should list all the passengers in that ticket as

Namel, Age1, Berth No.

2 Name2, Age 2, Berth No.

and so on

The serial numbers of the passenger whose ticket has to be cancelled is taken as the yout

When a ticket is cancelled, the passengers in RAC, If any, will be alloted that berth and all the other RAC and Waltlist passengers move up in their current position. For example, if 1 confirmed ticket is cancelled, RAC 1 will get a confirmed berth, RAC 2 will become RAC 1 and WL 1 will become RAC 4.

Print All

Print All should print the details of all the booked tickets and the details of the vacant berths. For example

Berth No, PNR, Name, Age

1. 1234, Name1, 25

2. vecant

3. 1235, Name2, 22

4, 1235, Name3, 22

and so on

Print Availability

Should print all the vacant berths with summary. For example

5 Berths and 4 RAC tickets available

Berth No. Status

4, vacant and so on

7. RAC vacant
