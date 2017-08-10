#Scope of this file
This file explains the database set up and the reasoning for the choice in fields.

#Database tech
The database is in MySQL.

#Tables
There will be two tables, a table with the users and a second table with the books or materials.

#User table
Very simple and clean, this will have three fields, username, role and (hashed and salted) password. The password field will remain empty as long as it is a single computer system with no network integration.

##Wait, no passwords at first?
The system is supposed to be very simple and low barrier of use at first. The pi will not be connected to the school network nor have a keyboard supplied. The only mode of entry will be a touchscreen (with touchscreen keyboard out of reach) and a barcode scanner. Thus security doesn't need to be more complicated than necessary. Login will involve scanning a barcode on a card supplied to each user. This barcode simply states the username that is matched to the corresponding name in the table.

#Books table
*The name is WiP.*
Fields are going to be: title, publishing house, author, year, edition, number of the copy, borrower.
Publishing house being more important than the author due to textbooks being written in committee and bigger differences existing between publishers.
