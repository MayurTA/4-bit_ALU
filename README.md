# Design of a 4-bit_ALU in MAGIC
Design of a 4-bit ALU which can perform addition, subtraction, comparison, left shift and right shift by one bit, using MAGIC. The ALU consists of three independant blocks- Adder, Subtractor/Comparator and Left/Right shift. Adder has been designed using four cascaded full adders. And full adders have been designed using half adders and NOR gate. Subtractor is a modification of the adder and comparison of the operands is performed based on the borrow bit obtained after subtraction. Bit shifters have been designed using buffers and multiplexers. 

Basic gates from Vsclib standard cell library have been used to create the circuit. The circuit contains around 40 such gates. Layout has been desinged using over-the-cell routing to minimize the area of the ALU. 
