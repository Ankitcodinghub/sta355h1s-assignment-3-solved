# sta355h1s-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [STA355H1S Assignment #3 Solved](https://www.ankitcodinghub.com/product/assignment-3-sta355h1s-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117142&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STA355H1S  Assignment #3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Problems to hand in:

1. Suppose that X1,···,Xn are independent Gamma random variables with pdf

for x &gt; 0

where λ &gt; 0 and α &gt; 0 are unknown parameters. Given X1 = x1,···,Xn = xn, the likelihood function is

(a) Assume the following prior distribution for (λ,α):

100) for λ,α &gt; 0

Given X1 = x1,···,Xn = xn, show that the posterior density of α is

(b) Data on intervals (in hours) between failures of air conditioning units on ten Boeingaircraft are given (and analyzed) in Example T of Cox &amp; Snell (1981). These data (199 observations) are provided in a file on Quercus. Using the prior for (λ,α) in part (a), compute the posterior distribution for α.

Note: To compute the posterior density, you will need to compute the normalizing constant – on Quercus, I will give some suggestions on how to do this. A simple estimate of α is αb = ¯x2/s2 where ¯x and s2 are the sample mean and variance, respectively. We would expect the posterior to be concentrated around this estimate.

(which is a hyperparameter) at α = 1 so that

100) for λ &gt; 0

and

100) otherwise

(This type of prior is an example of a “spike-and-slab” prior used in Bayesian model selection.) We then have

.

For θ = 0.1,0.2,0.3,···,0.9, evaluate P(α = 1|x1,···,xn). (This is easier than it looks as much of the work has been done in part (b).)

2. Suppose that F is a continuous distribution with density f. The mode of the distribution here is defined to be the global maximizer of the density function. (In other applications, it is useful to think of modes as local maxima of the density function.)

In some applications (for example, when the data are “contaminated” with outliers), the centre of the distribution is better described by the mode than by the mean or median; however, unlike the mean and median, the mode turns out to be a difficult parameter to estimate. There is a document on Quercus that discusses a few of the various methods for estimating the mode.

The τ-shorth is the shortest interval that contains at least a fraction τ of the observations X1,···,Xn; it will have the form [X(a),X(b)] where b − a + 1 ≥ τn. A number of mode

estimators are based on the observations lying in [X(a),X(b)]; for example, we can the sample mean of these observation or the sample median. (Note that taking the sample mean of the observations in [X(a),X(b)] is like a trimmed mean although the trimming here is typically asymmetrical.) In this problem, we will consider estimating the mode using the midpoint of the interval, that is, µb = (X(a) + X(b))/2. This estimator is called a Venter estimator. An R function to compute this estimator for a given value of τ is available on Quercus in a file venter.txt.

(a) For the Hidalgo stamp thickness data considered in Assignment #2, compute Venterestimates for various values of τ. How small does τ need to be in order that the estimate “makes sense”? (Recall from Assignment #2 that the density seemed to have a number of local maxima but one clear global maximum.)

(b) Suppose that the underlying density f is asymmetric and unimodal. The choice of τ for the Venter estimator involves a bias-variance tradeoff: If τ is small then we should expect the estimator to have a small bias but larger variance with the bias increasing and the variance decreasing as τ increases.

Suppose that X1,···,Xn are independent Gamma random variables with density

where we will assume that α &gt; 1; in this case, the mode is α − 1.

Using Monte Carlo simulation, estimate the MSE of the Venter estimator for τ = 0.5 and τ = 0.1, sample sizes n = 100 and n = 1000, and shape parameters α = 2 and α = 10. (8 simulations in total.) For α = 2 and α = 10, which Venter estimator seems to be better (on the basis of MSE)?

We can exploit this independence as follows: Define T = X1 + ··· + Xn; T has a Gamma distribution with shape parameter n. Then

Thus given ( ), we can estimate

by

!

and so we can estimate P(µb ≤ x) by

and differentiating, we obtain the density estimate

Using the simulation data in part (b) for n = 100, α = 2 and τ = 0.5, compute

Supplemental problems (not to hand in):

3. Suppose that X1,···,Xn are independent random variables with density or mass function f(x;θ) and suppose that we estimate θ using the maximum likelihood estimator θb; we estimate its standard error using the observed Fisher information estimator

where `0(x;θ),`00(x;θ) are the first two partial derivatives of lnf(x;θ) with respect to θ. Alternatively, we could use the jackknife to estimate the standard error of θb; if our model is correct then we would expect (hope) that the two estimates are similar. In order to investigate this, we need to be able to get a good approximation to the “leave-one-out” estimators .

(a) Show that θ−i satisfies the equation

n

`0(Xi;θb−i) = X`0(Xj;θb−i).

j=1

(b) Expand the right hand side in (a), in a Taylor series around θb to show that

and so

(You should try to think about the magnitude of the approximation error but a rigorous proof is not required.)

(c) Use the results of part (b) to derive an approximation for the jackknife estimator of thestandard error. Comment on the differences between the two estimators – in particular, why is there a difference? (Hint: What type of model – parametric or non-parametric – are we assuming for the two standard error estimators?)

(d) For the air conditioning data considered in Assignment #1, compute the two standarderror estimates for the parameter λ in the Exponential model (f(x;λ) = λexp(−λx) for x ≥ 0). Do these two estimates tell you anything about how well the Exponential model fits the data?

4. Suppose that X1,···,Xn are independent continuous random variables with density f(x;θ) where θ is real-valued. We are often not able to observe the Xi’s exactly rather only if they belong to some region Bk (k = 1,···,m); an example of this is interval censoring in survival analysis where we are unable to observe an exact failure time but know that the failure occurs in some finite time interval. Intuitively, we should be able to estimate θ more efficiently with the actual values of {Xi}; in this problem, we will show that this is true (at least) for MLEs.

Assume that B1,···,Bm are disjoint sets such that ) = 1. Define independent discrete random variables Y1,···,Yn where Yi = k if Xi ∈ Bk; the probability mass function of Yi is for k = 1,···,m.

Also define

Under the standard MLE regularly conditions, the MLE of θ based on X1,···,Xn will have variance approximately 1/{nIX(θ)} while the MLE based on Y1,···,Yn will have variance approximately 1/{nIY (θ)}.

(a) Assume the usual regularity conditions for f(x;θ), in particular, that f(x;θ) can be differentiated with respect to θ inside integral signs with impunity! Show that IX(θ) ≥ IY (θ) and indicate under what conditions there will be strict inequality.

Hints: (i) f(x;θ)/p(k;θ) is a density function on Bk.

(ii) For any function g,

(iii) For any random variable U, E(U2) ≥ [E(U)]2 with strict inequality unless U is constant.

(b) Under what conditions on B1,···,Bm will IX(θ) ≈ IY (θ)?

5. In seismology, the Gutenberg-Richter law states that, in a given region, the number of earthquakes N greater than a certain magnitude m satisfies the relationship

log10(N) = a − b × m

for some constants a and b; the parameter b is called the b-value and characterizes the seismic activity in a region. The Gutenberg-Richter law can be used to predict the probability of large earthquakes although this is a very crude instrument. On Quercus, there is a file containing earthquakes magnitudes for 433 earthquakes in California of magnitude (rounded to the nearest tenth) of 5.0 and greater from 1932–1992.

(a) If we have earthquakes of (exact) magnitudes M1,···,Mn greater than some known m0, the Gutenberg-Richter law suggests that M1,···,Mn can be modeled as independent random variables with a shifted Exponential density

f(x;β) = β exp(−β(x − m0)) for x ≥ m0.

where β = b × ln(10) and m0 is assumed known. However, if the magnitudes are rounded to the nearest δ then they are effectively discrete random variables taking values xk = m0 + δ/2 + kδ for k = 0,1,2,··· with probability mass function

p(xk;β) = P(m0 + kδ ≤ M &lt; m0 + (k + 1)δ)

= exp(−βkδ) − exp(−β(k + 1)δ)

= exp(−β(xk − m0 − δ/2)){1 − exp(−βδ)} for k = 0,1,2,···.

If X1,···,Xn are the rounded magnitudes, find the MLE of β. (There is a closed-form expression for the MLE in terms of the sample mean of X1,···,Xn.)

(b) Compute the MLE of β for the earthquake data (using m0 = 4.95 and δ = 0.1) as well as estimates of its standard error using (i) the Fisher information and (ii) the jackknife. Use these to construct approximate 95% confidence intervals for β. How similar are the intervals?

6. In genetics, the Hardy-Weinberg equilibrium model characterizes the distributions of genotype frequencies in populations that are not evolving and is a fundamental model of population genetics. In particular, for a genetic locus with two alleles A and a, the frequencies of the genotypes AA, Aa, and aa are

Pθ(genotype = AA) = θ2, Pθ(genotype = Aa) = 2θ(1−θ), and Pθ(genotype = aa) = (1−θ)2 where θ, the frequency of the allele A in the population, is unknown.

In a sample of n individuals, suppose we observe XAA = x1, XAa = x2, and Xaa = x3 individuals with genotypes AA, Aa, and aa, respectively. Then the likelihood function is

L(θ) = {θ2}x1{2θ(1 − θ)}x2{(1 − θ)2}x3.

(The likelihood function follows from the fact that we can write

Pθ(genotype = g) = {θ2}I(g=AA){2θ(1 − θ)}I(g=Aa){(1 − θ)2}I(g=aa);

multiplying these together over the n individuals in the sample gives the likelihood function.) (a) Find the MLE of θ and give an estimator of its standard error using the observed Fisher information.

(b) A useful family of prior distributions for θ is the Beta family:

for 0 ≤ θ ≤ 1

where α &gt; 0 and β &gt; 0 are hyperparameters. What is the posterior distribution of θ given XAA = x1, XAa = x2, and Xaa = x3?
