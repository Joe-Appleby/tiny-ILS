# tiny-ILS
*A very small library system intended to run on a pi and use NFC to manage log in and book checked out material. A catalogue will follow later on.

The name is still subject to change.
This system will be designed to run on a Raspberry Pi 2 Model B.
The Pi will have a 3.5" touchscreen attached and either a camera or a NFC reader.

# Requirements
- database with all books in the history department's library
- user database with all history teachers
- user log in via NFC/QR-code
- log books via NFC/QR-code
- two button interface
- self-contained system, everything runs on one single Pi
- provide list of borrowed books and corresponding users

# Feature creep
- catalog website
- expansion to whole school and all books
  - separate server
  - full interface for bigger screen
  
# Alternatives
Use Koha ILS instead of *tiny-ILS* which would make things easier. However Koha doesn't have a tiny interface for the touchscreen and doesn't do NFC nor QR codes out of the box.
