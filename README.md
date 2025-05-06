# cs170-homework-10-solved
**TO GET THIS SOLUTION VISIT:** [CS170 Homework 10 Solved](https://www.ankitcodinghub.com/product/cs170-homework-10-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96706&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS170 Homework 10 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
2 Max Flow, Min Cut, and Duality

In this exercise, we will demonstrate that LP duality can be used to show the max-flow min-cut theorem.

Consider this instance of max flow:

A 7A4

ST S547T

B B

Let f1 be the flow pushed on the path {S,A,T}, f2 be the flow pushed on the path

</div>
</div>
<div class="layoutArea">
<div class="column">
{S,A,B,T}, and f3 be the flow pushed on max flow in terms of the variables f1, f2, f3:

max f1+f2+f3 f1 + f2≤7 f3≤5 f1≤4 f2≤4 f2 + f3≤7 f1,f2,f3 ≥0

The objective is to maximize the flow being

we can’t push more flow through that edge than its capacity allows.

</div>
</div>
<div class="layoutArea">
<div class="column">
the path {S,B,T}. The following is an LP for

</div>
</div>
<div class="layoutArea">
<div class="column">
pushed, with the constraint that for every edge, (a) Find the dual of this linear program, where the variables in the dual are xe for every

</div>
</div>
<div class="layoutArea">
<div class="column">
edge e in the graph.

(b) Consider any cut in the graph. Show that setting xe = 1 for every edge crossing this cut and xe = 0 for every edge not crossing this cut gives a feasible solution to the dual program.

(c) Based on your answer to the previous part, what problem is being modelled by the dual program? By LP duality, what can you argue about this problem and the max flow problem?

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
<div class="layoutArea">
<div class="column">
(Constraint for (S, A)) (Constraint for (S, B)) (Constraint for (A, T )) (Constraint for (A, B)) (Constraint for (B, T ))

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
3 How to Gamble With Little Regret

Suppose that you are gambling at a casino. Every day you play at a slot machine, and your goal is to minimize your losses. We model this as the experts problem. Every day you must take the advice of one of n experts (i.e. a slot machine). At the end of each day t, if you take advice from expert i, the advice costs you some cti in [0, 1]. You want to minimize the regret R, defined as:

</div>
</div>
<div class="layoutArea">
<div class="column">
1􏰊T T􏰋 R = 􏰀 cti(t) − min 􏰀 cti

</div>
</div>
<div class="layoutArea">
<div class="column">
T t=1 1≤i≤n t=1

</div>
</div>
<div class="layoutArea">
<div class="column">
where i(t) is the expert you choose on day t. Your strategy will be probabilities where pti denotes the probability with which you choose expert i on day t. Assume an all powerful adversary (i.e. the casino) can look at your strategy ahead of time and decide the costs associated with each expert on each day. Let C denote the set of costs for all experts and all days. Compute maxC(E[R]), or the maximum possible (expected) regret that the adversary can guarantee, for each of the following strategies.

(a) Choose expert 1 at every step, i.e. pt1 = 1 for all t.

(b) Any deterministic strategy, i.e. for each t, there exists some i such that pti = 1.

(c) Always choose an expert according to some fixed probability distribution at every time step. That is, fix some p1,…,pn, and for all t, set pti = pi.

What distribution minimizes the regret of this strategy? In other words, what is argminp1,…,pn maxC(E[R])?

This analysis should conclude that a good strategy for the problem must necessarily be randomized and adaptive.

4 Global Mincut to Min s-t Cut

In class, we showed how to use maximum s-t flow to solve the minimum s-t cut. Now we ask you to consider the global mincut problem. Given a weighted, undirected graph G, the problem asks you to find a minimum weight set of edges whose removal disconnects the graph. (Note that there is no notion of s and t).

Show how to use maxflow or min s-t cut algorithms to solve this problem efficiently. Prove that your reduction would lead to the optimal solution. How many times do you need to invoke the maxflow or min s-t cut subroutine?

5 Dijsktra’s Sort

Show how to use Dijsktra’s algorithm to sort n real numbers (not necessarily non-negative or integral) in ascending order in O(n log n) time. You may use the intermediate outputs of Dijsktra’s to do the sorting (as opposed to using it as a blackbox).

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Argue that this means that improving upon the O(m + n log n) run-time of Dijsktra’s algorithm (with Fibonacci heap) would lead to a faster sorting algorithm than merge and quick sort.

Hint: Given the numbers, construct a graph such that the order of vertices being extracted from priority queue by Dijsktra’s algorithm corresponds to the right sorting order.

</div>
</div>
</div>
