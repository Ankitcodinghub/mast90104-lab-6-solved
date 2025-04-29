# mast90104-lab-6-solved
**TO GET THIS SOLUTION VISIT:** [MAST90104 Lab 6 Solved](https://www.ankitcodinghub.com/product/mast90104-a-first-course-in-statistical-learning-solved-5/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;112915&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MAST90104 Lab 6 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1 Practical questions

(a) What are the species of the three tallest trees? Of the five fattest trees? (Use the order command.)

(b) What are the mean diameters by species?

(c) What are the two species that have the largest third quartile diameters?

(d) What is the identity of the tallest tree of the species that was the fattest on average?

2. The following questions use the ‘sleep’ dataset, which you can download from the course website. This dataset contains (among other things) data on the body weight (kg) and brain weight (g) of 62 mammals. Use the following commands to read the data (make sure the data file is in your working directory, or change to the correct path):

mammals &lt;- read.csv(“sleep.csv”)

This creates a data frame, mammals, with components (among others) named BodyWt and BrainWtWe are interested in predicting brain weight from body weight.

(a) Plot the data. Fit the model of brain weight vs. body weight using the lm function. Plot the diagnostics plots and comment on the plots. Is the model appropriate ?

(b) Apply a logarithmic transformation to both BodyWt and BrainWt.

mammals$BodyWt &lt;- log(mammals$BodyWt) mammals$BrainWt &lt;- log(mammals$BrainWt)

Fit a linear model explaining (transformed) brain weight from body weight, using the lm command.

Display the summary of the fitted model, and then create a scatter plot of the data and superimpose the fitted regression line on it. Does it look like a reasonable fit?

Use diagnostic plots to assess if the model assumptions are satisfied.

(c) Find a 95% confidence interval for a mammal weighing 50 kg.

(d) Find a 95% prediction interval for a mammal weighing 50 kg.

(e) Test the following hypotheses, using the anova function.

i. H0 : β = 0

ii. H0 : β1 = 0 iii. H0 : β0 = 0 iv. H0 : β = (2,1)

(f) Write down the final model for the untransformed data.

1

2 Workshop questions

1. Suppose X is n × p of full rank and C is r × p,r ≤ p also of full rank.

(a) Show that XTX is positive definite (hint: use the definition).

(b) Show that C(XTX)−1CT is positive definite (hint: why does (XTX)−1 have a matrix square root?).

(c) Show that C(XTX)−1CT is invertible.

(d) Show that [C(XTX)−1CT]−1 is positive definite.

2. In this question we consider the hypothesis H0 : β = β∗. The test statistic for this hypothesis is

.

(a) Show that

(b−β∗)TXTX(b−β∗) = (y− Xβ∗)T(y− Xβ∗) − (y− Xb)T(y− Xb).

That is, it is the SSRes for the null model minus the SSRes for the full model. Also show that, in general,

(b−β∗)TXTX(b−β∗) 6= yTX(XTX)−1XTy−β∗TXTXβ∗.

That is, in this case we can not write it as the SSReg for the full model minus the SSReg for the model under H0.

(b) Show directly that (b−β∗)TXTX(b−β∗) and SSRes are independent, that is without using our existing results that b and SSRes are independent.

Hint: set q = y− Xβ∗ then

i. Show that (b−β∗)TXTX(b−β∗) = qTX(XTX)−1XTq.

ii. Show that SSRes = qT[I − X(XTX)−1XT]q and hence that these two quadratic forms are independent.

3. Recall the joint confidence region for the parameters of a full rank linear model:

(b−β)TXTX(b−β) ≤ ps2fα.

Use this to derive a test for the hypothesis H0 : β = β∗. Show that this test is equivalent to the test for H0 : β = β∗ obtained using the general linear hypothesis.

2
