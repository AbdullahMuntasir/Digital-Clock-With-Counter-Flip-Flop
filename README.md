# Digital-Clock-With-Counter-Flip-Flop 

This project focuses on designing a **digital clock** using **flip-flops, counters, logic gates, and a 7-segment display**. The circuit accurately tracks and displays **hours, minutes, and seconds** by sequentially counting time using **binary-coded decimal (BCD) counters**.  

### **Working Principle**  
1. **Generating Clock Pulses**:  
   - A **555 Timer IC** operates in astable mode to generate 1Hz pulses, acting as the clock signal.  

2. **Counting Seconds, Minutes, and Hours**:  
   - **Flip-Flops and Decade Counters (74LS76, 4026 ICs)** count time in binary.  
   - **Logic Gates (AND, NAND)** control transitions and reset counters at specific limits (e.g., 60 seconds → 1 minute).  

3. **Displaying Time**:  
   - **BCD to 7-segment decoders (74LS48, 4026)** convert binary values to numeric digits, which are shown on **7-segment displays**.  

### **Key Features & Future Scope**  
- Accurately tracks time with **synchronized counters**.  
- Can be enhanced with **alarm functionality, LCD display, and backup power**.  

This project demonstrates **sequential logic design and digital electronics** principles, making it a practical learning tool for timekeeping circuits.
