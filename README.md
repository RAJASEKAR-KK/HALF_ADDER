# HALF_ADDER
# Aim:
To stimulate and synthesis the half adder using verilog.
# Apparatus Required:
Vivado Xilinx 14.7 Spartan 6 FPGA.
# Procedure:
```
STEP 1: Start the vivado software and select the name and the project.
STEP 2: Select the device family,device,package and speed.
STEP 3:  Select new source in the new project and select verilog module as the source type.
STEP 4: Type the file name and module name and click next and then finish button. Type the code and save it.
STEP 5: Select the run simulation and then run behavioural simulation in the source window and click the check syntax.
STEP 6: Click the simulation to stimulate the program and give the inputs and verify the outputs as per the truth table.
STEP 7: Compare the output with the truth table.
```
# Truth Table
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/fe672c28-5c6a-4355-b70f-b40bce63880d)
# Circuit Diagram
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/5f1a79a7-73c2-4b99-a40d-afa2a20c74ac)
# Sum = A XOR B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/020e1531-1c11-42e5-9f27-f09ba459984d)
# Carry = A AND B
![image](https://github.com/RESMIRNAIR/HALF_ADDER/assets/154305926/988ae131-0822-4d23-941b-eaafad349a72)
# Program:
```
module Half_adder(a,b,sum,carry);
input a,b;
output sum,cary;
xor g1(sum,a,b);
and g2(carry,a,b);
endmoudle
```
# Output:
![Half adder](https://github.com/RESMIRNAIR/HALF_ADDER/assets/165815233/3ef15d7c-21ef-4136-8750-454874c31ccf)
# Result:
Thus the verilog program for half adder has been stimulated and verified successfully.

