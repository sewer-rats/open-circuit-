



# Open Circuits

## User Guide

​		Playing with different electronic components and creating your own circuits online! If you have a question or would like to recommend a feature, please reach out to [contact@opencircuits.io](mailto:contact@opencircuits.io).

## Getting Started with Open Circuits

​		Welcome to Open Circuits. Let's first get familar with the user interface.

 <img src="/Users/imgs/help.svg" alt="help" style="zoom:150%;" /> Help center for more resources                        <img src="/Users/imgs/download.svg" alt="download" style="zoom:150%;" />  Download circuits in *.circuit, *.pdf, or *png file.

 <img src="/Users/imgs/open.svg" alt="open" style="zoom:150%;" /> Import *.circuit files from computer               <img src="/Users/imgs/signin.png" alt="signin" style="zoom: 6%;" /> Sign in using google account.

 <img src="/Users/imgs/save.png" alt="save" style="zoom:3.3%;" /> Save your circuit after you sign in                   <img src="/Users/imgs/lock_open.svg" alt="lock_open" style="zoom:150%;" /> Edit mode                       <img src="/Users/imgs/lock.svg" alt="lock" style="zoom:150%;" /> Lock mode

  <img src="/Users/imgs/tab.png" alt="tab" style="zoom: 5%;" />   Manage circuits and view examples.   	         <img src="/Users/imgs/github.png" alt="github" style="zoom:10%;" />  Github link      			    <img src="/Users/imgs/add.png" alt="add" style="zoom:7.5%;" />  Add components

​		Great! Let's get to know our first circuit! Clicking the <img src="/Users/imgs/tab.png" alt="tab" style="zoom:5%;" /> button and then the Basic AND Gate Setup to load the example circuit. If it's not shown, refresh the page and try again.  

##### 	  																													 									     Example Circuit (Basic AND Gate Setup):

​														<img src="/Users/imgs/circuit.png" alt="circuit" style="zoom:25%;"/> 

​		**Basic**: This example contains two switches<img src="/Users/imgs/switch.png" alt="switch" style="zoom:5%;" />, one AND Gate <img src="/Users/imgs/andgate.png" alt="andgate" style="zoom:5%;" />, and one LED <img src="/Users/imgs/led.png" alt="led" style="zoom:5%;" />. Switch, aside from its original function, also represents power. AND Gate passes the power only if all switches are on, that means all inputs are true. Currently, there're two. Turn up both of them to light up the LED.

<img src="/Users/imgs/edit_circuit.png" alt="edit_circuit" style="zoom:33%;" />

​		**How to edit**: That's lit! Click the AND Gate <img src="/Users/imgs/andgate.png" alt="andgate" style="zoom:5%;" /> and it will show a list of parameters. Below it's a table for the all parameters we support currently. Change whichever you want.

| Pararmeter  |                        Description                        |
| :---------: | :-------------------------------------------------------: |
|    Name     |               Default by its original name.               |
|  Position   |     You could also left click the components to drag.     |
| Input count | Number of component's input. Maximum support is different |
|    Color    |                     Color of the LED                      |
|  Create IC  |                 i don't know what's this.                 |
| Clock Delay |           How often does Clock turn on and off            |

<img src="/Users/imgs/edit_circuit2.png" alt="edit_circuit2" style="zoom:21%;"/>

​		**Add components**: I change input count to three and color to pink. Notice there's one more button here. How? You could just click the add icon  <img src="/Users/imgs/add.png" alt="add" style="zoom:6%;" /> , drag the switch icon<img src="/Users/imgs/switch.png" alt="switch" style="zoom:5%;" /> to the circuit, and connect  the left input of the AND Gate <img src="/Users/imgs/andgate.png" alt="andgate" style="zoom:5%;" />. 

​		**Save the circuit locally**: Clicking the<img src="/Users/imgs/download.svg" alt="download" style="zoom:150%;" />button. You will see three options: 
​	  <img src="/Users/imgs/download.svg" alt="download" style="zoom:150%;" />Download: save as [name].circuit file. Notice that this is the only supported file for import.
​	   <img src="/Users/imgs/pdf_download.svg" alt="pdf_download" style="zoom:120%;" /> Download as PDF						  		![png_download](/Users/imgs/png_download.svg)Download as PNG

​		**Save the circuit online**: Clicking the <img src="/Users/imgs/signin.png" alt="signin" style="zoom: 6%;" /> button and sign in with your google account and then the <img src="/Users/imgs/save.png" alt="save" style="zoom:3.3%;" /> button to save the circuit online. You could always remove it from the cloud by clicking the <img src="/Users/imgs/tab.png" alt="tab" style="zoom: 5%;" /> and ![close-24px](/Users/imgs/close-24px.svg)buttons under "My Circuits" section.





## Supported Components

##### Inputs

<img src="/Users/imgs/constantlow.png" alt="constantlow" style="zoom:15%;" />**Constant Low**: power that is constantly off.<img src="/Users/imgs/constanthigh.png" alt="constanthigh" style="zoom:15%;" />**Constant High**: power that is constantly on.

<img src="/Users/imgs/button.png" alt="button" style="zoom:15%;" />**Button**: Left click to enable power one time.<img src="/Users/imgs/switch.png" alt="switch" style="zoom:15%;" />**Switch**: Left click to switch on/off power .

<img src="/Users/imgs/clock.png" alt="clock" style="zoom:15%;" />**Clock**: Auto-switch on/off power regularly by setting the clock delay.

##### Outputs

<img src="/Users/imgs/led.png" alt="led" style="zoom:15%;" />**LED**: Light up if it connects to the power.    <img src="/Users/imgs/sevensegmentdisplay.png" alt="sevensegmentdisplay" style="zoom:15%;" />**Segment Display**: Display digits.

##### Logic Gates

<img src="/Users/imgs/bufgate.png" alt="bufgate" style="zoom:15%;" />**Buffer Gate**: It passes its input, unchanged, to its output.

<img src="/Users/imgs/notgate.png" alt="notgate" style="zoom:15%;" />**NOT Gate**: It produces an inverted version of the input at its output.

<img src="/Users/imgs/andgate.png" alt="andgate" style="zoom:15%;" />**AND Gate**: It implements logical conjunction (∧) from mathematical logic.

<img src="/Users/imgs/nandgate.png" alt="nandgate" style="zoom:15%;" />**NAND Gate**: It produces an output which is false only if all its inputs are true.

<img src="/Users/imgs/orgate.png" alt="orgate" style="zoom:15%;" />**OR Gate**: It implements logical disjunction (∨) from mathematical logic.

<img src="/Users/imgs/norgate.png" alt="norgate" style="zoom:15%;" />**NOR Gate**: It gives a positive output only when both inputs are negative.

<img src="/Users/imgs/xorgate.png" alt="xorgate" style="zoom:15%;" />**XOR Gate**: It gives a true output when the number of true inputs is odd.

<img src="/Users/imgs/xnorgate.png" alt="xnorgate" style="zoom:15%;" />**XNOR Gate**: It gives true when all of its inputs are true or when all of its inputs are false

##### Flip Flops

<img src="/Users/imgs/srflipflop.png" alt="srflipflop" style="zoom:15%;" />**SR Flip Flops**:

<img src="/Users/imgs/jkflipflop.png" alt="jkflipflop" style="zoom:15%;" />**JK Flip Flops**:

<img src="/Users/imgs/dflipflop.png" alt="dflipflop" style="zoom:15%;" />**D Flip Flops**:

<img src="/Users/imgs/tflipflop.png" alt="tflipflop" style="zoom:15%;" />**T Flip Flops**:

##### Latches: 

<img src="/Users/imgs/dlatch.png" alt="dlatch" style="zoom:15%;" />**D Latches**:

<img src="/Users/imgs/srlatch.png" alt="srlatch" style="zoom:15%;" />**SR Latches**:

##### Other

<img src="/Users/imgs/multiplexer.png" alt="multiplexer" style="zoom:15%;" />**Multiplexer(Mux)**: It's a device that can receive multiple input signals and synthesize a single output signal in a recoverable manner for each input signal.

<img src="/Users/imgs/demultiplexer.png" alt="demultiplexer" style="zoom:15%;" />**Demultiplexer(Demux)**: It takes one single input data line and then switches it to any one of a number of individual output lines one at a time.

<img src="/Users/imgs/encoder.png" alt="encoder" style="zoom:15%;" />**Encoder**: It converts the active data signal into a coded message format or it is a device that coverts analogue signal to digital signals

<img src="/Users/imgs/decoder.png" alt="decoder" style="zoom:15%;" />**Decoder**: It's a combinational circuit as encoder but its operation is exactly reverse as that of the encoder

<img src="/Users/imgs/label.png" alt="label" style="zoom:15%;" />**Label**: a text box that allows you to write any text inside.












Page 3: Use the examples. How to edit the circuits’ parameter, Enable the switch, zoom in zoom out.



Page 4: how to save the circuits, how to sign in, how to input the circuit file.





Page 6: Keyboard shortcuts.

