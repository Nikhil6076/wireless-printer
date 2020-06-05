# wireless-printing server
A common problem that people face is having many systems and a single printer for all those systems. As we cannot afford a printer for each and every system we use LAN and connect those systems and then to a common system which acts as a printing server and then to printer.


But even it may have some disadvantages. So if we can access a single printer via wireless network it could be in a more effective manner. Hence making this as a main objective we use a printer which can be accessed by many systems without using LAN cables. In this proposed work, we use Raspberry Pi to achieve our objective.


The Raspberry Pi will be connected to printer and then files will be printed through printer.

Here basically what we are doing is that, we are creating a web page where the user uploads the file that needs to be printed and clicks on print.

Whenever the user clicks on print button the files will be sent to a default mail account and on the other side the raspberry pi which is connected to the printer keeps on checking the same mail for unread mails. Whenever it finds a new unread mail then it just downloads the attachment and gives it to the printer and the printer prints the file. 
