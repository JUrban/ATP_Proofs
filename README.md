# Interesting ATP Proofs
 
### Lipschitzian is uniformly continuous: 
http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/ncfcont2.html#T25

E proof: http://grid01.ciirc.cvut.cz/~mptp/enigma_prf/t25_ncfcont2
261 axioms, 373 initial clauses, 1534 processed, 11.2 generated, 38s, 135 proof clause steps, 36/79 initial proof flas/clauses, lots of calculation

### Enigma learns to count: 
for r being real number st 0 <= r & r <= 2 * PI & sin r = 1 holds r = PI / 2

http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/sin_cos6.html#T28

E proof: http://grid01.ciirc.cvut.cz/~mptp/enigma_prf/t28_sin_cos6
2175 proc, 30.6k generated, 27s, 185 steps, 71 clauses and 63 flas, - lots of calculation

### Groups with sets: 
for a being Element of G for H being Subgroup of G holds ( a in H iff a * H = carr H )

http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/group_2.html#T113
E proof: http://grid01.ciirc.cvut.cz/~mptp/enigma_prf/t113_group_2
217 fof axioms, 298 initial clauses, 1214 nontriv given, 8523 nontriv gener, 109 proof clause steps, 28/44 initial proof flas/clauses

### Longer proof about programs and sequences with 59/663 used/initial axioms
/home/mptp/big1/bushy_np/en_gnn/convert-models/grid28_60/mzr02-premsel_enigma_01_2020_T10_loop01_epoch_66-query768-ctx1536-w0-coop/t64_compos_1
http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/compos_1.html#T64

```
% Generated clauses                    : 38354
% ...of the previous two non-trivial   : 36601
% Processed clauses                    : 5785
% ...remaining for further processing  : 3336
% Parsed axioms                        : 663
% Initial clauses in saturation        : 1212
% Proof object initial clauses used    : 78
% Proof object initial formulas used   : 59
% Proof object clause steps            : 158
```

### Topology
for T being non empty discrete TopSpace holds T is T_2

http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/yellow13.html#T4

(base) mptp@air-02:~/big1/bushy_np/en_gnn/convert-models/grid28_60/mzr02-premsel_enigma_01_2020_T10_loop01_epoch_66-query768-ctx1536-w0-coop$ less t4_yellow13  

```
% Parsed axioms                        : 194
% Initial clauses in saturation        : 279
% Proof object clause steps            : 103
% Proof object initial clauses used    : 36
% Proof object initial formulas used   : 23
% Processed clauses                    : 3866
% ...remaining for further processing  : 1758
% Generated clauses                    : 36890
% ...of the previous two non-trivial   : 32976
```

### Connectedness 

for GX being TopSpace holds
( ex x being Point of GX st
for y being Point of GX holds x,y are_joined iff for x, y being Point of GX holds x,y are_joined )

http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/connsp_1.html#T29

```
% Proof object clause steps            : 99
% Proof object initial clauses used    : 32
% Proof object initial formulas used   : 17
% Parsed axioms                        : 74
% Initial clauses in saturation        : 99
% Processed clauses                    : 1940
% ...remaining for further processing  : 1069
% Generated clauses                    : 28829
% ...of the previous two non-trivial   : 27799
```

### Topology - product of T_0 spaces is T_0
for M being non empty set
for J being non-Empty TopStruct-yielding ManySortedSet of M st ( for i being Element of M holds J . i is T_0 TopSpace ) holds
product J is T_0

http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/yellow14.html#T37

mptp@air-02:~/big1/bushy_np/en_gnn/convert-models/grid1500/l8-mzr02-premsel_enigma_01_2020_T10_loop01_epoch_51-query128-ctx1024-w0-coop$ 

```
% Proof object clause steps            : 98
% Proof object initial clauses used    : 44
% Proof object initial formulas used   : 23
% Parsed axioms                        : 188
% Initial clauses in saturation        : 319
% Processed clauses                    : 2185
% ...remaining for further processing  : 1408
% Generated clauses                    : 9227
% ...of the previous two non-trivial   : 7578
% User time                : 20.956 s
```

### Enigma can differentiate

http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/sin_cos9.html#T89

((ln * arctan) `| Z) . x = 1 / ((1 + (x ^2)) * (arctan . x)) ) )

http://grid01.ciirc.cvut.cz/~mptp/enigma_prf/t89_sin_cos9

```
% Proof object clause steps            : 143
% Proof object initial clauses used    : 62
% Proof object initial formulas used   : 45
% Parsed axioms                        : 643
% Initial clauses in saturation        : 834
% Processed clauses                    : 4037
% ...remaining for further processing  : 2341
% Generated clauses                    : 18764
% ...of the previous two non-trivial   : 16507
% User time                : 28.020 s
```


### Additivity of integral
http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/mesfunc5.html#T93

f is nonnegative & A c= B holds Integral (M,(f | A)) <= Integral (M,(f | B))

http://grid01.ciirc.cvut.cz/~mptp/enigma_prf/t93_mesfunc5

```
% Proof object clause steps            : 126
% Proof object initial clauses used    : 53
% Proof object initial formulas used   : 29
% Parsed axioms                        : 441
% Initial clauses in saturation        : 670
% Processed clauses                    : 3725
% ...remaining for further processing  : 2236
% Generated clauses                    : 14044
% ...of the previous two non-trivial   : 13075
```

(base) mptp@air-02:~/big1/bushy_np/en_gnn/convert-models/grid1500/l5-mzr02-premsel_enigma_01_2020_T10_loop01_epoch_4-query512-ctx768-w0-coop$ 


### Almost infinitude of primes:

Enigma can now (sort of) prove that primes are infinite: for l being Nat ex p being Prime st ( p is prime & p > l )

http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/newton.html#T72

The E proof is at http://grid01.ciirc.cvut.cz/~mptp/enigma_prf/t72_newton

Modulo the fact that we gave it 328 FOF axioms translated to 549 initial clauses, the proof stats seem easy:

```
% Proof object clause steps            : 83
% Proof object initial clauses used    : 42
% Proof object initial formulas used   : 38
% Parsed axioms                        : 328
% Initial clauses in saturation        : 549
% Processed clauses                    : 880
% ...remaining for further processing  : 734
% Generated clauses                    : 3135
% ...of the previous two non-trivial   : 2856
% User time                : 6.772 s
```

The only issue is that no prover could do it before and that I got the proof with only one parameterization of Enigma out of 800 :-). (l8-mzr02-premsel_enigma_01_2020_T10_loop01_epoch_67-query128-ctx768-w0-solo).

The fact that it generated only 2.8k clauses during 734 nontrivial given clause loops (with 549 initial clauses) is pretty amazing (and probably the reason why this succeeded). 



### Longish proof in INT_5
http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/int_5.html#T3

for fp being FinSequence of INT st len fp = 1 holds Poly-INT fp = INT --> (fp . 1)

(base) mptp@air-02:~/big1/bushy_np/en_gnn/convert-models/grid1500/l5-mzr02-premsel_enigma_01_2020_T10_loop01_epoch_45-query256-ctx1536-w0-coop$ less t3_int_5

```
% Proof object clause steps            : 153
% Proof object initial clauses used    : 76
% Proof object initial formulas used   : 59
% Parsed axioms                        : 404
% Initial clauses in saturation        : 656
% Processed clauses                    : 2547
% ...remaining for further processing  : 1849
% Generated clauses                    : 11674
% ...of the previous two non-trivial   : 10831
```

### Longish proof in ORDERS_1

for R being Relation for X being set st R partially_orders X holds R |_ 2 X is Order of X

http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/orders_1.html#T45

```
% Proof object clause steps            : 132
% Proof object initial clauses used    : 46
% Proof object initial formulas used   : 26
% Parsed axioms                        : 218
% Initial clauses in saturation        : 347
% Processed clauses                    : 3985
% ...remaining for further processing  : 1852
% Generated clauses                    : 30744
% ...of the previous two non-trivial   : 27676
% User time                : 22.204 s
```

### Cardinalities:
1 -tuples_on D,D are_equipotent & card (1 -tuples_on D) = card D 

http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/card_4.html#T8

http://grid01.ciirc.cvut.cz/~mptp/enigma_prf/t8_card_4

```
% Proof object clause steps            : 90
% Proof object initial clauses used    : 35
% Proof object initial formulas used   : 20
% Parsed axioms                        : 301
% Initial clauses in saturation        : 508
% Processed clauses                    : 1262
% ...remaining for further processing  : 932
% Generated clauses                    : 6827
% ...of the previous two non-trivial   : 6260
```

### Divergence of locally greater function

http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/limfunc2.html#T37

### Cardinalities
 X,[:X,{x}:] are_equipotent & card X = card [:X,{x}:] 

http://grid01.ciirc.cvut.cz/~mptp/7.13.01_4.181.1147/html/card_2.html#T6

