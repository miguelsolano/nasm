The Art of Assembly Language 2nd Edition
-----------------------------

##### Intel CPU Family
- is generally classified as a Von Neumann Arch Machine
- Von Neumann Machines have three main building blocks: CPU, memory, I/O devices
- Those components are interconnected using the system bus
- Three buses? System, Data, and Control Bus? 
- CPU registers in 80x86 break down to 4: general purpose, special purpose application-accessible,segment, special-purpose kernel mode
-  special-purpose kernel mode: writing system level tools ex: debuggers or os apps
- general purpose registers are not independent
- EFLAGS 32 bit register that encapsulates several single-bit boolean values
- 8 of the EFLAGS interest application programmers: overflow, direction, interrupt disable, sign, zero, aux carry, parity, carry
- Condition codes: overflow, carry, sign, zero

