# cis1300---week-2---lab-2---a-brief-look-at-time-solved
**TO GET THIS SOLUTION VISIT:** [CIS1300 – Week 2 – Lab 2 – A Brief Look at Time Solved](https://www.ankitcodinghub.com/product/cis1300-week-2-lab-2-a-brief-look-at-time-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115310&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CIS1300 - Week 2 - Lab 2 – A Brief Look at Time Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
In this lab you will take a program and change it to do various related tasks. The program is in the file dates.c on the CourseLink site in Lab 2. Download this file and open in your favourite editor and you will see:

#include &lt;stdio.h&gt;

#include &lt;stdlib.h&gt;

/*

* Program name: dates.c

* Author: Deb Stacey

* Compilation: gcc -ansi -o dates dates.c

*/

int main ( int argc, char *argv[] ) {

/* Names of the months */

/* The number of days in each month */

int monthLength[12] = { 31, 28, 31, 30, 31, 30, 31, 31, 30, 31, 30, 31 };

int dd = 0; int mm = 0; int yyyy = 0;

if ( argc &lt; 4 ) {

printf ( “Usage: ./dates mm dd yyyy ” ); return ( 1 ); } else {

dd = atoi ( argv[1] ); mm = atoi ( argv[2] ); yyyy = atoi ( argv[3] );

}

/* Remember that arrays like monthName and monthLength start their index at 0 and not 1. */

/* The first entry in the array is monthName[0], monthLength[0] */

printf (“In %s there are %d days “, monthName[mm-1], monthLength[mm-1]);

return ( 0 );

}

Compile and run the program to check on its behaviour:

In the code you will see two very interesting variables:

/* Names of the months */

/* The number of days in each month */

int monthLength[12] = { 31, 28, 31, 30, 31, 30, 31, 31, 30, 31, 30, 31

};

These variables are called arrays. An array stores multiples of the same type, e.g. integers. For example monthLength is an integer array that has room to store 12 integers. monthName stores 12 character strings (this is more complicated and will be explained in another class). The important thing to remember about arrays is how you refer to an individual item within the array. How do I get the first integer in the monthLength array? Each item in an array is “indexed” or “has a number” and you put that number in [ ] after the array name, e.g. monthLength[10]. But the tricky part is that the index starts at 0 and not 1! So the first integer in the monthLength array is monthLength[0].

After you understand what the dates.c program is doing, you need to change it to do the following 4 tasks:

2. Next, add code to check if the month input on the command line is in the range 1 to 12. If it is not then print out the following error message and exit the program. Make sure that your return code is non-zero.

Error – the month entered (13) is not in the proper range (1-12)

3. Next, add code to check if the day input on the command line is in the range 1 to the number of days in the month. If it is not then print out the following error message and exit the program. Make sure that your return code is non-zero.

Error – you entered 31 for the day and that is not in the range

(1-30)

4. Lastly write code to determine if the year (yyyy) is a leap year. The algorithm to check if a year is a leap year is as follows:

Every year that is exactly divisible by four is a leap year, except for years that are exactly divisible by 100 unless they are exactly divisible by 400.

Bonus

Checking Your Work

$ sh checkLab2.sh

$ sh checkL2Bonus.sh

The following are some screen shots that show you how your program should behave:
