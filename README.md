I have a requirement to parse out the taobao items, price, shipment tracking number and this script is an attempt to solve this.

First, lunch the script and scan your QR to get yourself login.
Script will move to "my order" page and parse order_id, price, and shipping no one by one.

[update] as of Aug 11 2020
instead of doing this in one single step, the updated script is to parse item, order, shipping url first and save into a sql db, the 2nd script is to just to get out the tracking info which left undo by 1st script.
