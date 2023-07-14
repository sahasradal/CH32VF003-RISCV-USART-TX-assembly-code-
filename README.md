# CH32VF003-RISCV-USART-TX-assembly-code-
test code to send a string with USART (CH32VF003) 38400 baud
CH32V003 USART TX RISCV assembly language code with BRONZEBEARD assembler get bronzebeard assembler from https://github.com/theandrew168/bronzebeard WINDOWS To create a virtual environment, decide upon a directory where you want to place it, and run the venv module as a script with the directory path: python3 -m venv tutorial-env This will create the tutorial-env directory if it doesn’t exist, and also create directories inside it containing a copy of the Python interpreter and various supporting files. A common directory location for a virtual environment is .venv. This name keeps the directory typically hidden in your shell and thus out of the way while giving it a name that explains why the directory exists. It also prevents clashing with .env environment variable definition files that some tooling supports. Once you’ve created a virtual environment, you may activate it. On Windows, run:

tutorial1-env\Scripts\activate.bat

if GPIO_asm and CH32V003_reg1.asm (inc files) are on desktop ( both files should be in the same folder) use command

bronzebeard --hex-offset 0x08000000 Desktop/GPIO_asm.asm

Use WCH_LINK_UTILITY to upload the assembled bb.out.hex file to CH32V003 chip by connceting gnd, 3.3v,DIO pins. if successful led on PD4 pin flashes
