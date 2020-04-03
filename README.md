# nlpelief
Belief system revelation via nlp 

## Task 1 : Key-Query-Val Approach
(Key, [Query1, Query2]) -> Val
where Key is preposition to weigh, such as "Is Trump good?" and (Query1, Query2) is (Yes, No) or (Good, Bad) for the key (How's Trump?) 

## Task 2 : 

For given Key, predict which queries are available.
e.g. for (Key: "China", ?), the avialble querie tuple are (Friend, Enemy), (Ally, Enemy) etc.

## Task 3 (Most generalized/Simplified version):

For given any sequence of words, predict 0 or 1 where 0 is subjective-false 1 is subjective-true, subjective true/false is defined as belief.

"Trump is Good" -> 0: No, he's evil 1: Yes, I believe him
