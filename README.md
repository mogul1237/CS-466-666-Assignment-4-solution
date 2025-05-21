# CS-466-666-Assignment-4-solution

Download Here: [CS 466/666 Assignment 4 solution](https://jarviscodinghub.com/assignment/cs-466-666-assignment-4-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. [14 marks] This question deals with an algorithm to find the second largest of n values.
In class we mentioned/proved that if we scan n values comparing each with the
maximum seen so far we expect the number of “new maxima” to be  1/i  ln n + ,
where =.577…
Take a random sample, R, of r of the values; r = n/lg n (or so).
By repeatedly pairing the elements that have “won” every comparison, find the
maximum of the sample (in r-1 comparisons). Initialize m1 as the sample maximum and
m2 as the element that was the maximum of half the sample but “lost” to the maximum
in the last comparison.
Scan through the remaining elements (i.e. those not in R), comparing each to m2 and if
it is larger than m2 compare it with m1. Update m1 to be the maximum seen so far and
m2 to be the second largest (perhaps excluding some of the values from the R).
When finished the scan, m1 is the maximum of the set; under some condition, you may
know m2 is the second largest value in the set. If you cannot guarantee m2 is the second
largest, find the maximum of m2 and the random sample elements that “lost” directly to
the original m1.
a. [2 marks] What is the maximum number of comparisons this method could use? (Off
by O(1) is OK, but no more. Briefly justify your claim.)
b. [4 marks] What condition, detectable in this algorithm, would guarantee that m2 is the
second largest after finishing the scan of all elements? What is the probability that this
condition will hold? (Briefly justify this claim)
c. [2 marks] If the condition above is not satisfied, how many more comparisons are
required?
d. [4 marks] What is the expected number of times m2 is replaced (i.e. the number of
times a second comparison is done) in scanning the n-n/lg n non sample elements?
(Give the expected number of times including the constant factor in the lead term, and
justify the claim)
e. [4 marks] Given the probability of the condition (of part b.) being satisfied and the
expected number of comparisons used in that case, and the probability of it not being
satisfied and the number of comparisons used in the latter case, what is the expected
number of comparisons used by the method. (Justify this claim.)
