# cse102-assignment-10-the-tower-of-hanoi-solved
**TO GET THIS SOLUTION VISIT:** [CSE102 Assignment 10-The Tower of Hanoi Solved](https://www.ankitcodinghub.com/product/cse102-assignment-10-the-tower-of-hanoi-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101996&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE102 Assignment 10-The Tower of Hanoi Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
The Tower of Hanoi is a mathematical puzzle. It consists of three poles and a number of disks of different sizes which can slide onto any poles. The puzzle starts with the disk in a neat stack in ascending order of size in one pole, the smallest at the top thus making a conical shape.

The puzzle has the following two rules:

1. You can’t place a larger disk onto a smaller disk 2. Only one disk can be moved at a time

</div>
</div>
<div class="section">
<div class="section">
<div class="layoutArea">
<div class="column">
#define STACK_BLOCK_SIZE 10

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
typedef struct { data_type * array; int currentsize; int maxsize} stack;

int push(stack * s, data_type d); /* the stack array will grow STACK_BLOCK_SIZE entries at

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
a time */

data_type pop(stack * s); /* the stack array will shrink STACK_BLOCK_SIZE entries at a time */

stack * init_return(); /* initializes an empty stack */

int init(stack * s); /* returns 1 if initialization is successful */

</div>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Using this, implement a solution to tower-of-hanoi problem without recursion and using stack. Your solver should be able to take any size tower.

</div>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Example for size 3:

</div>
</div>
<div class="layoutArea">
<div class="column">
Example output for size 3:

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
General Rules:

Obey the style guidelines.

Do not change the provided function prototypes (you will not get any credits).

The program must be developed on Ubuntu using GCC compiler (version provided in class), compilation problems due to the use of another OS or compiler is your responsibility (you will not get any credits).

Your program should work as expected. Do not expect partial credit if your code works only in some cases but not in all cases as expected.

You can ask your questions about the homework by posting on the forum in Teams. Handing in your work:

Hand in your work using the appropriate class Teams assignment site. No

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
late submissions will be accepted.

Pack this directory into a zip file named 20180000001_X_Z.zip

When unpacked as above in Ubuntu (version provided in class) it should allow executing the following commands in a shell:

▪ “$make clean” removes everything except makefile, source code (.c ) and other resource files (if any) – all compiling results and intermediate files should be removed.

▪ “$make compile” should compile the code.

▪ “$make run” should run the code along with any parameters needed.

</div>
</div>
</div>
