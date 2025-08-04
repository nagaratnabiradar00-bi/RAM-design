# RAM-design
A RAM has a data bus (sometimes called width of RAM) form which we can access content from the RAM or we can put a content on this, and if we give write command to the RAM, it'll write RAM with the content on the data bus. RAM has lots of addresses (sometimes called depth of RAM) and these addresses can be accessed by the address bus.

Other than data and address bus, RAM has one more input read/write. If it's state is changed, let's say if it is high, the content at data bus is written to the address provided to the RAM from address bus else the content of the address provided by address bus is reflected to the data bus.

Below is the code of 1 kilo byte RAM describe using Verilog HDL. The width of the RAM is 8-bit and depth is 1024 (which is 1 kilo). For making the code simple, there are two similar data bus, one will be used to read the content from the RAM and another is used to provide content to the data bus and, when read write input is high, this content is written to the address of the RAM FPGA development softwareVerilog online course
