# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![WhatsApp Image 2025-10-15 at 10 05 57_9b26e18e](https://github.com/user-attachments/assets/be51ea62-8dcb-41e6-a5d4-dc16cbb64bc3)


Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

/* write all the steps invloved */

**PROGRAM**
<img width="1913" height="667" alt="image" src="https://github.com/user-attachments/assets/84c7e352-a3dd-47da-9ffd-ee56813d8468" />

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by:DWIJESH RAJ SINHA Y RegisterNumber:25013468

*/

**RTL LOGIC FOR SISO Shift Register**
![WhatsApp Image 2025-10-15 at 10 06 02_9121a3e9](https://github.com/user-attachments/assets/f8e5cebc-4a5b-49b7-8964-49785c10f689)
**TIMING DIGRAMS FOR SISO Shift Register**

**RESULTS**
THUS THE LOGIC GIVEN IS STUDIED AND VERIFIED SUCCESSFULLY
