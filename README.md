# Opal Kelly XEM6310

### ISim simulation in Xilinx ISE and testing on XEM6310 using FrontPanel Loader
[Video-Simulation-in-ISE-and-testing-on-XEM6310](https://www.youtube.com/watch?v=sqyJVjWYPRE&t=1s)

1.Start ISE and create a new project

2.Project setting:
Device: XC6SLX150
(need to choose ISE Design Suite Embedded Edition during install)
Package: FGG484

3.Create VHDL module and define I/O

4.Edit and check syntax 

5.Synthesize the design

6.Create a testbench

7.Edit and simulate in ISim

Solve ISim launching problem:
1)Richt click Simulate behavior model
2)Click process properties 
3)deselect /load glbl/

8.Change CLK frequency for readable output (use 24bit divider)

9.Create pin_assignment in .ucf

10.Generate .bit file

11.Load using FrontPanel API

##### Device:			Spartan-6 xc6slx150	
##### Environment:		Xilinx ISE 14.7 Embedded edition
##### .bit Loader:		FrontPanel API
