# HackerRank

## Compare the Triplets

Alice and Bob each created one problem for HackerRank. A reviewer rates the two challenges, awarding points on a scale from 1 to 100 for three categories: problem clarity, originality, and difficulty.

We define the rating for Alice's challenge to be the triplet A=(a[0],a[1],a[2]), and the rating for Bob's challenge to be the triplet B=(b[0],b[1],b[2]).

If a[i] > b[i] , then Alice is awarded 1 point.

If a[i] < b[i], then Bob is awarded 1 point.

If a[i] = b[i], then neither person receives a point.

Comparison points is the total points a person earned.

Given A and B, can you compare the two challenges and print their respective comparison points?

Input Format

The first line contains 3 space-separated integers, a[0], a[1], and a[2], describing the respective values in triplet . 

The second line contains 3 space-separated integers, b[0], b[1], and b[2], describing the respective values in triplet .

Constraints

1 < a[i] < 100

1< b[i] < 100
Output Format

Print two space-separated integers denoting the respective comparison points earned by Alice and Bob.
