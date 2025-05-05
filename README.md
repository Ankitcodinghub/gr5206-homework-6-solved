# gr5206-homework-6-solved
**TO GET THIS SOLUTION VISIT:** [GR5206 Homework 6 Solved](https://www.ankitcodinghub.com/product/gr5206-homework-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94748&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;GR5206 Homework 6 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Goals: Simulating probability distributions using the Inverse Transform Method and Accept- Reject Method. Built in R distribution functions. Estimate the mathematical constant π using Monte Carlo techniques. More practice writing functions and plotting.

First set your seed as 0, i.e., set.seed(0)

Part 1: Inverse Transform Method

Consider the Cauchy random variable X with probability density function

you to simulate X from U. Note: I will solve this in class.

<ol start="2">
<li>Write a R function called cauchy.sim that generates n simulated Cauchy random variables. The function should have the single input n and should use the inverse- transformation from Part 1. Test your function using 10 draws.</li>
<li>Using your function cauchy.sim, simulate 1000 random draws from a Cauchy distri- bution. Store the 1000 draws in the vector cauchy.draws. Construct a histogram of the simulated Cauchy random variable with fX(x) overlaid on the graph. Note: when plotting the density curve over the histogram, include the argument prob = T.</li>
</ol>
Part 2: Reject-Accept Method

Problem 2

Let random variable X denote the temperature at which a certain chemical reaction takes place. Suppose that X has probability density function

</div>
</div>
<div class="layoutArea">
<div class="column">
fX(x)= 1 1 π(1+x2)

</div>
</div>
<div class="layoutArea">
<div class="column">
, −∞&lt;x&lt;∞.

1. Let U be a uniform random variable over [0,1]. Find a transformation of U that allows

</div>
</div>
<div class="layoutArea">
<div class="column">
(1) f(x) =

</div>
<div class="column">
􏰐19(4 − x2) − 1 ≤ x ≤ 2 0 otherwise

1

</div>
</div>
<div class="layoutArea">
<div class="column">
Perform the following tasks:

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="4">
<li>Write a function f that takes as input a vector x and returns a vector of f(x) values. Plot the function between −3 and 3. Make sure your plot is labeled appropriately.</li>
<li>Determine the maximum of f(x) and find an envelope function e(x) by using a uniform density for g(x). Write a function e which takes as input a vector x and returns a vector of e(x) values.</li>
<li>Using the Accept-Reject Algorithm, write a program that simulates 10,000 draws from the probability density function f(x) from Equation 1. Store your draws in the vector f.draws.</li>
<li>Plot a histogram of your simulated data with the density function f overlaid in the graph. Label your plot appropriately.</li>
</ol>
Problem 3: Reject-Accept Method Continued

</div>
</div>
<div class="layoutArea">
<div class="column">
Consider the standard normal distribution X with probability density function 1 􏰀12􏰁

</div>
</div>
<div class="layoutArea">
<div class="column">
f(x)=√2πexp −2x , −∞&lt;x&lt;∞.

In this exercise, we will write a function named normal.sim that simulates a standard

</div>
</div>
<div class="layoutArea">
<div class="column">
normal random variable using the Accept-Reject Algorithm. Perform the following tasks:

<ol start="8">
<li>Write a function f that takes as input a vector x and returns a vector of f(x) values. Plot the function between −5 and 5. Make sure your plot is labeled appropriately.</li>
<li>Let the known density g be the Cauchy density defined by pdf</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
g(x) = 1 1 π(1+x2)

</div>
<div class="column">
, −∞ &lt; x &lt; ∞.

</div>
</div>
<div class="layoutArea">
<div class="column">
Write a function e that takes as input a vector x and constant alpha (0 &lt; α &lt; 1) and returns a vector of e(x) values. The envelope function should be defined as e(x) = g(x)/α.

<ol start="10">
<li>Determine a “good” value of α. To show your solution, plot both f(x) and e(x) on the interval [−10, 10].</li>
<li>Write a function named normal.sim that simulates n standard normal random vari- ables using the Accept-Reject Algorithm. The function should also use the Inverse- Transformation from Part 1. Test your function using n=10 draws.</li>
<li>Using your function normal.sim, simulate 10,000 random draws from a standard normal distribution. Store the 10,000 draws in the vector normal.draws. Construct
2
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
a histogram of the simulated standard normal random variable with f(x) overlaid on the graph. Note: when plotting the density curve over the histogram, include the argument prob = T.

Part 3: Simulation with Built-in R Functions Consider the following “random walk” procedure:

• Startwithx=5

• Draw a random number r uniformly between −2 and 1. • Replace x with x+r

• Stopifx≤0

• Else repeat

Perform the following tasks:

<ol start="13">
<li>Write a while() loop to implement this procedure. Importantly, save all the positive values of x that were visited in this procedure in a vector called x.vals, and display its entries.</li>
<li>Produce a plot of the random walk values x.vals from above versus the iteration number. Make sure the plot has an appropriately labeled x-axis and and y-axis. Also use type=”o” so that we can see both points and lines.</li>
<li>Write a function random.walk() to perform the random walk procedure that you implemented in question (9). Its inputs should be: x.start, a numeric value at which we will start the random walk, which takes a default value of 5; and plot.walk, a boolean value, indicating whether or not we want to produce a plot of the random walk values x.vals versus the iteration number as a side effect, which takes a default value of TRUE. The output of your function should be a list with elements: x.vals, a vector of the random walk values as computed above; and num.steps, the number of steps taken by the random walk before terminating. Run your function twice with the default inputs, and then twice times with x.start equal to 10 and plot.walk = FALSE.</li>
<li>We’d like to answer the following question using simulation: if we start our random walk process, as defined above, at x = 5, what is the expected number of iterations we need until it terminates? To estimate the solution produce 10,000 such random walks and calculate the average number of iterations in the 10, 000 random walks you produce. You’ll want to turn the plot off here.
3
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
17. Modify your function random.walk() defined previously so that it takes an additional argument seed: this is an integer that should be used to set the seed of the ran- dom number generator, before the random walk begins, with set.seed(). But, if seed is NULL, the default, then no seed should be set. Run your modified function random.walk() function twice with the default inputs, then run it twice with the input seed equal to (say) 33 and plot.walk = FALSE.

Part 4: Monte Carlo Integration

The goal of this exercise is to estimate the mathematical constant π using Monte Carlo

Integration. Consider the function

􏰐√1 − x2 0 ≤ x ≤ 1

0 otherwise

</div>
</div>
<div class="layoutArea">
<div class="column">
(2) g(x) =

</div>
</div>
<div class="layoutArea">
<div class="column">
The above function traces out a quartile circle over the interval [0, 1]. Perform the following tasks:

18. Run the following code:

<pre>     g &lt;- function(x) {
       return(sqrt(1-x^2))
</pre>
<pre>     }
     plot(seq(0,1,.01),g(seq(0,1,.01)),type="l",col="purple")
</pre>
The above code should produce the plot of a quarter circle.

<ol start="19">
<li>Identify the true area under the curve g(x) by using simple geometric formulas.</li>
<li>Using Monte Carlo Integration, approximate the mathematical constant π within a 1/1000 of the true value. When performing this simulation, make sure to choose a probability density function that has support over the unit interval, i.e. uniform(0,1) or beta(α,β).</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
