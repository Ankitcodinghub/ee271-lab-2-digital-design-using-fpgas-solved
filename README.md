# ee271-lab-2-digital-design-using-fpgas-solved
**TO GET THIS SOLUTION VISIT:** [EE271 Lab 2-Digital Design using FPGAs Solved](https://www.ankitcodinghub.com/product/ee271-lab-2-digital-design-using-fpgas-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99222&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE271 Lab 2-Digital Design using FPGAs Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Digital Design using FPGAs

</div>
</div>
<div class="layoutArea">
<div class="column">
Lab Objectives

</div>
</div>
<div class="layoutArea">
<div class="column">
1. Developing more complex designs on the DE1_SoC board.

2. Using RTL Verilog, where you identify what you want the output to look like and the

Boolean algebra is automatically done for you.

Task 1: Design Problem – Multi-level logic on the DE-1 FPGA.

In order to speed up the processing of returns at Nordstrom’s, the customer service department wants an electronic detector device. Its goal is to both determine those items that have been discounted so that the proper rebate can be calculated, as well as help find shoplifters returning their ill-gotten gains.

There are six products being sold. The UPC code for each is shown, as well as whether it was ever on sale (i.e. sold at a discounted price), and whether it is expensive, and thus is marked when sold.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Item Name

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
UPC Code

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Discounted?

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Expensive?

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Shoes Jewelry

Bike Business Suit Winter Coat Socks

</div>
<div class="column">
00 0 00 1 01 1 10 0 10 1 1 10

</div>
<div class="column">
No Yes No No Yes No No Yes Yes Yes Yes No

</div>
</div>
<div class="layoutArea">
<div class="column">
Note that since there are only 6 items, not all UPC codes are used. The behavior of your circuit for these situations is unimportant (i.e. Don’t Care).

You will be given the UPC code of the item under test (signals “U”, “P”, and “C” for simplicity), and a detector will check for a secret mark (“M”). Your circuit should have one “discounted” light that lights up whenever a discounted item’s UPC code is applied, as well as a “stolen” light that lights up whenever a theft is detected.

Nordstrom’s has a special method for finding shoplifters. Whenever they sell an expensive item, they put a secret mark onto it. Thus, expensive items that are purchased are specially marked, while stolen expensive items will not be so marked (inexpensive items are never

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
marked since it is too expensive to mark everything sold). When there is a return, we want to make sure someone didn’t steal the item, then return the stolen item for cash.

With the rules given, there are four cases for the stolen light logic to consider:

• An expensive item with the mark is not stolen.

• An expensive item without the mark is stolen.

• A non-expensive item without the mark is not stolen.

• A non-expensive item with the mark will never occur, so is a Don’t Care.

Design this circuit and minimize the output equation(s) and write a SystemVerilog code for the design. Implement the design and simulate it in Quartus and ModelSim. Name the folder of your Quartus project lab2a. Finally, download the design to the FPGA, and use the switches and lights on the board to connect to the circuit.

Please use switch Sw9, Sw8, Sw7 for U, P, C, respectively, and Sw0 for the secret Mark.

Task 2: Seven-segment display

The code for the seven-segment display is given below. Create a copy of your lab2a project and call it lab2b, then enter the code below into a new System Verilog file. Then, create a new module that instantiates the seg7 code taking input from SW9 – SW6 and displaying on Hex0

the corresponding digit. Simulate in ModelSim.

<pre>   module seg7 (bcd, leds);
   input  logic  [3:0] bcd;
</pre>
<pre>    output logic  [6:0] leds;
</pre>
<pre>    always_comb begin   case
   (bcd)
</pre>
<pre>      //          Light: 6543210
      4'b0000: leds = 7'b0111111; // 0
      4'b0001: leds = 7'b0000110; // 1
      4'b0010: leds = 7'b1011011; // 2
      4'b0011: leds = 7'b1001111; // 3
      4'b0100: leds = 7'b1100110; // 4
      4'b0101: leds = 7'b1101101; // 5
      4'b0110: leds = 7'b1111101; // 6
      4'b0111: leds = 7'b0000111; // 7
      4'b1000: leds = 7'b1111111; // 8
      4'b1001: leds = 7'b1101111; // 9
      default: leds = 7'bX;   endcase
</pre>
<pre>    end
   endmodule
</pre>
As mentioned in lab1, the 7-segment display on the DE-1 is ACTIVE LOW. That means putting a FALSE on the wire makes it light up, while a TRUE means that light is off. You will have to adjust your design accordingly. (The figure below gives you a correct mapping of the HEX digits to its corresponding positions on the display.)

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Finally, create a new module that hooks task1 with task2 together, so the system simultaneously computes the HEX0 display and the Sale and Stolen lights. Since we only have six items, we only need 3 switches for UPC. Change your design to allow SW8-SW6 to represent the UPC. You still need SW0 for the secret mark to compute the ‘stolen’ and ‘sale’ lights but it doesn’t have anything to do with the HEX0 display. Test and debug with ModelSim, then load onto your board. (If you only feed SW8-6 into your seg7 module, the observable HEX patterns should only range from 0 to 7).

(Extra Credit) Task 3: Design Problem – UPC code to display

In task1 we built a system that took in a UPC code and output whether the item was on sale and whether it was stolen. A neighboring store, Fred’s House of Useful Stuff, wants a similar system but has found that people are changing the UPC sticker on their stuff. To combat that, they’d like you to add a display on Hex5 – Hex0 that describes each product when it is entered – if the description is different from the product actually entered, they know someone is trying to cheat! Note that, since Fred pays his employees embarrassingly little, they tend to be not the brightest folks, so the Hex display should be as simple as possible.

Since Fred doesn’t want to pay for a redesign of the circuit for task1, we will use the same UPC codes, On Sale values, and Expensive markings as before BUT, Fred is willing to sell whatever products you will like him to (Hint: pick products that make good Hex displays!), though the expensive ones must use UPC codes designated “expensive”, and the inexpensive ones must use UPC codes designated “inexpensive”. BE CREATIVE! And you MUST sell 6 items.

Determine your items and Hex displays. You can use any or all of the lights on the hex display you choose, upper and lower case, pictograms, whatever. So, for example, you could put in “Dress Shoes” as an item and have the hex display show “ShOE”. Note that some letters are not representable in HEX. For example, i or t, so you can choose to avoid those.

Once you have figured out what you’ll display, create a high-level design for the circuit. It will be similar to the seg7 module, with 3 inputs (U, P, and C), but up to 6 7-bit outputs (for each of the 7seg displays). Simulate it in ModelSim, then hook it to the switches and lights of your board to make sure it works. Create a module that combines task1 with this task such that the system simultaneously computes the HEX display, and the Sale and Stolen lights. Test and debug with ModelSim, then load onto your board.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
ModelSim Tip: When you put your entire design together and simulate in ModelSim, you’ll probably need some help organizing all your signals. A couple of tips:

<ol>
<li>1.) &nbsp;ModelSim can have signals from multiple modules displayed at the same time. Simply select in the left pane the module whose signals you want to display, then drag the signals you want from the middle pane to the waveform window.</li>
<li>2.) &nbsp;To order the signals, you can click and drag names in the waveform window.</li>
<li>3.) &nbsp;To organize signals for each module, highlight all of the signal names related to one module in the waveform window, right-click on one of the signal names, and select “Group”. Give it a memorable name, then hit okay. You can now move the signals
as a group, and hide/expose them easily.
</li>
</ol>
Lab Demonstration and Submission Requirements

</div>
</div>
<div class="layoutArea">
<div class="column">
•

</div>
</div>
<div class="layoutArea">
<div class="column">
• •

</div>
<div class="column">
Submit a video demonstrating the tasks. Your video is expected to be around 1-2 minutes.

In the video demonstrate the functionality on the board using the switches and LEDs and

the 7-segment display.

Submit a short lab report (about 3 pages and it’s ok if you go above 3 pages) that should include 3 main sections, detailed below.

Procedure

<ul>
<li>– &nbsp;Describe how you approached the problem and include any visuals (like block diagrams, truth tables, schematics, ..etc)
Results
</li>
<li>– &nbsp;Include screenshots of ModelSim results</li>
<li>– &nbsp;Describe what you tested in the simulation, and what the results in the screenshot show</li>
<li>– &nbsp;Give a brief overview of the finished project, compared to what was asked
Appendix
</li>
</ul>
– Include screen shots of your code

On Padlet, write about a problem you had in the lab and the fix to it, share a tip or trick you learned while working on the lab. You can also share an aha moment that you discovered while working on the lab. Avoid duplicating comments made by your classmates. NO videos for this

padlet task, please use textual comments. The link to the padlet is here

Submit the SystemVerilog files (files with extension .sv). Make sure to follow the commenting guide provided. A significant amount of grade will depend on the commenting style.

Submit your report, video and programs to Canvas.

</div>
</div>
</div>
