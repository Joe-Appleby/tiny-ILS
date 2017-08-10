# tiny-ILS
**All I need is a database that tracks who has which book.**

*A very small library system intended to run on a pi and use 1D barcodes to manage log in and book checked out material. A catalogue will follow later on.*

The name is still subject to change.
This system will be designed to run on a Raspberry Pi 3.
The Pi will have a some form of screen attached and a simple 1D barcode scanner.

## Requirements
- database with all books in the history department's library
- user database with all history teachers
- user log in via 1D barcode
- log books via 1D barcode
- two/three button interface
- self-contained system, everything runs on one single Pi
- provide list of borrowed books and corresponding users on an admin page automatically displayed on admin login

## Feature creep
- catalog website
- expansion to whole school and all books
  - separate server
  - full interface
  
## Alternatives
None that work easily on a Raspberry Pi.

## Technologies used
- PostgreSQL
- Python
- HTML
