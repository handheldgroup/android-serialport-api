The current Android SDK does not provide any API for reading and writing to the Linux TTY serial ports. You may find such serial ports on the connector of HTC Android phones.

This project wants to provide a simple API to connect, read and write data through theses serial ports.

The supported features are:

listing the available serial ports on the device, including USB to serial adapters
configuring a serial ports (baudrate, stop bits, permission, ...)
providing standard InputStream and OutputStream Java interfaces
What is NOT possible with this project:

receiving/sending data through an USB slave interface
Please have a look on the Wiki for more information. You may also find relevant information in users comments.

An application sample is available for download in the release section.