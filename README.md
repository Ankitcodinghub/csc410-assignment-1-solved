# csc410-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CSC410 Assignment 1 Solved](https://www.ankitcodinghub.com/product/csc410-solved-10/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120372&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC410 Assignment 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Assignment 1

Assignment Format and Guidelines on Submission

This assignment is worth 12% of the total course mark. Submit on Markus and follow these rules:

• Each group should submit six files named gcd.dfy, search.dfy, rabbit.dfy, stackinga.dfy, stackingb.dfy, and bubble.dfy. Note that Markus has been setup to accept exactly those files. All the required lemmas, helper functions, etc, should be included in the one file for each problem.

• Make sure your final submitted proofs pass through the compile (and not just VSCode) for either Dafny 2 or Dafny 3. VSCode can sometimes be buggy in declaring things verified. You are encouraged, but not required, to work with Dafny 2 as it seems like a more stable version for beginners.

Note that your assignment will be automatically graded. Your function will be called from another function. If you mess with the signature, the call will fail and the autograder will give you a 0 mark.

Word of Advice

Before you sit behind a Dafny terminal, make sure you have a detailed proof worked out on paper. If you do not have such a (detailed) complete proof, you cannot hack your way through a Dafny proof. You have already seen in class that even when we think our proofs are complete, some intermediate steps (deemed trivial by us) require some more work in Dafny. If you have a complete proof, and are certain about its correctness, but cannot get it through to Dafny, then it most likely means that you are making a leap in reasoning somewhere that seems trivial to you, but not to the prover. We can assure you that this has nothing to do with a feature or a command that you do not know and have to dig up from a manual/tutorial. Everything you need to know to solve these has already been covered in class and Dafny tutorials.

Problem 0 (25 points)

(Warm up!) Consider the predicate divides as defined below:

predicate divides(a: nat, b:nat) requires a &gt; 0

{

exists k: nat :: b == k * a

}

It formalizes the standard mathematical concept of a|b. Encode the following property of gcd in Dafny and prove it:

∀k,a,b ∈ N : k|a ∧ k|b =⇒ k|(a,b)

Note that we want to prove that Euclid’s GCD algorithm satisfies the above (and not the mathematical definition of (a,b) (the greatest common divisor of a and b).

Problem 1 (30 points)

An implementation of a special case of a search routine with the precondition and postcondition encoded is given in the file search.dfy accompanying this assignment. Give a proof of correctness in Dafny for this search routine. Do not change the preconditions or postconditions. Only add annotations to the body of the method.

Problem 2 (40 points)

Problem 3 (40 points)

Consider the following game single player game. Initially, you are given a single stack of n boxes. In each turn of the game, you must perform exactly one of two moves:

1. Pick a stack of a+b boxes and split it into two non-empty stacks of a and b boxes (i.e. a,b &gt; 0). This move scores a × b points.

2. Pick a stack containing only one box and remove it. This actions scores no points.

The game is finished when no more moves are possible. No matter what moves you make, you will eventually run out of turns, and somewhat surprisingly, you will always finish the game scoring exactly points. Try out a few runs of the game for some specific games to observe this.

Your task is to prove this outcome for the game. A Dafny encoding of the game is given in the accompanying file stacking.dfy. The program is simulating the game. Add the annotations necessary to prove to Dafny that the program (hence the game) terminates and that the postcondition holds. For grading purposes, we divide this assignment into the following two tasks:

(a) (20 points) Prove that the postcondition as specified in stacking.dfy and outlined above holds.

Note: Dafny currently complains about line 14 of the code. This is intentional. You need to add a loop invariant that makes this complaint go away, and then be on your way about proving the problem correct.

Problem 4 (30 points)

A rabbit is located somewhere on a one-dimensional line, and it moves. It starts at location a. Every second, he moves b units to the right. Therefore, the location of the rabbit at time t is given by the expression a + t ∗ b. But, the catch is that a,b ∈ N are constants that are unknown to us. We can only know check if the rabbit is at a particular location by querying that location, and we can only query one location at every second.

We can catch the rabbit as follows. The set N×N of pairs of natural numbers is countable . Therefore, there exists a function unpair : N → N × N that covers all pairs of natural numbers.

Our strategy is to check the location x + t × y at time t, where (x,y) = unpair(t). There exists some t0 such that (a,b) = unpair(t0). This means that at time t0 we will check the location a + t0 ∗ b, where the rabbit shall be at time t0 as well! Therefore, we are guaranteed to catch the rabbit.

Now, you take the high level argument above and the sketch of an implementation that is given to you in file rabbit.dfy and turn it into a complete formal argument in Dafny. Complete the implementation of method unpair according to our strategy above, and prove that the while loop terminates (i.e. that we eventually catch the rabbit).

Hint: It is much easier to define unpair recursively, instead of defining it as a closed form function. It is also easier to formally reason about such definition in Dafny compared to the closed form.
