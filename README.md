# csci231-lab-10-solved
**TO GET THIS SOLUTION VISIT:** [CSCI231 Lab 10 Solved](https://www.ankitcodinghub.com/product/csci231-lab-10-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97025&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI231 Lab 10 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Lab 10

Submit your program before the deadline.

1. The average memory access time, AMAT, can be used to measure the memory performance and it includes hit time, miss ratio, and miss penalty (refer to page 478 of textbook/slide 38 of chapter 5).

<pre>  AMAT = Hit time + Miss rate * Miss penalty
</pre>
In this task you will write a program in MIPS assembly language that first defines an array of bytes of size 1024, where each byte is initially set to 0, then somehow ‘updates’ this memory such that after the update the memory looks as in the table below:

Initial contents of 1024 bytes (values are in hexadecimal):

Address value(+0) value(+4) value(+8) value(+c) … 0x1001000 0x00000000 0x00000000 0x00000000 0x00000000 …

After update:

Address value(+0) value(+4) value(+8) value(+c) … 0x1001000 0x01010101 0x01010101 0x01010101 0x01010101 …

For example, one of the ways to get as above result is to add 1 to each byte in the array.

Then using the Data Cache Simulator tool of MARS you need to determine the memory access count, hit rate, miss rate, and calculate AMAT. Then multiply AMAT by the number of memory accesses to get your metric score. Assume that hit time is 1 ns and miss penalty is equal to 1 ns + 15 * (# of words) + (# of words) * 1 ns. For example, if the block size is 1 word then, the miss penalty is 1 + 15*1 + 1 = 17 ns (refer to page 471 of textbook/ slide 34 of Chapter 5).

Note: Bonus points may be given to the top 3 students, who have the lowest metric score.

To activate the Cache and Memory related Tools click on Tools -&gt;Data Cache Simulator. Enable the Runtime Log and then click ’Connect to MIPS’.

You may change only the number of blocks and the cache block size in the Data Cache Simulator Tool. Other parameters like Cache size and Placement policy should be set to the default values.

Write your optimized parameters next to .text as comments like below (if there are no parameters, it will be graded with the default values):

<pre>  .data
  array: .space 1024
  ...
  .text
  #Number of blocks:
  #Cache block size:
  #YOUR METRIC SCORE:
  #The reasons for my optimization
  #In Assembly code:
  #In the configurations of cache parameters:
  ...
  your code goes here
</pre>
</div>
</div>
</div>
