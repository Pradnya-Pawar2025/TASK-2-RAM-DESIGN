# TASK-2-RAM-DESIGN
**COMPANY** CODETECH IT SOLUTIONS

**NAME** PRADNYA BHAGWAN PAWAR

**INTERN ID** CT08FVW

**DOMAIN** VLSI

**BATCH DURATION** December 25th, 2024 to January 25th, 2025.

**MENTOR NAME** NEELA SANTHOSH

# ENTER DESCRIPTION OF THE TASK
Module Functionality
Ports:

clk: The clock signal for synchronization of read and write operations.
we: Write Enable signal; determines if the RAM will perform a write operation.
addr: Address input for specifying the memory location to read from or write to.
data_in: Input data to be written into memory when we is asserted.
data_out: Output data that provides the contents of the memory at the specified address.
Behavior:

On the rising edge of the clock:
If we is 1, the data_in value is written to the memory location specified by addr.
If we is 0, the data_out is updated with the value stored in the memory location specified by addr.
Simulation Scenarios
Write Operation:

Set we = 1, specify addr, and provide the value on data_in.
On the next clock edge, the value is stored in the memory at the specified addr.
Read Operation:

Set we = 0, specify addr.
On the next clock edge, the value at the memory location addr is available on data_out.
Advantages
Simplicity: Easy to implement and simulate for small-scale designs.
Clock Synchronization: Ensures reliable and predictable operation.
Flexibility: Can be extended for larger memory sizes by increasing addr and data_in/data_out widths.

# OUTPUT

