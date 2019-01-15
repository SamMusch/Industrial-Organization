
# Game Theory
**3.1 Describing a game** <br>
**3.2 Static + complete** <br>
**3.3 Dynamic + complete + perfect info** <br>
**3.4 Repeated games** <br>
**3.5 Bargaining + fair allocations** <br>
**3.6 Games with incomplete + assymetric + imperfect info** <br>

**Nash Equilibrium** <br>
No advantage in switching for either side

**Introductory game theory =** <br>
study of rational behavior <br>
in strategic settings <br>
where players make flawless calculations <br>
in determining the actions <br>
that best serve their interests


**General Information** <br>
Strategic game = game where the actions of one player influences the actions of the other player (Not pure skill or pure luck) <br>
Noncooperative game theory = contracts / cooperation among competitors is not allowed (eg US business environment)

**Rules of game theory** <br>
(1) Never play a dominated strategy <br>
(2) If you have a dominant strategy, play it <br>
(3) Eliminate strategies until all dominated are eliminated <br>
(4) If dominant & iterated dominant don't exist, look for mutual best replies
(5) In dynamic games: look forward, reason backwards

---

# 3.1 Describing a Game

### Underlying assumption - Players are rational <br>
(1) You are aware of your preferences & constraints <br>
(2) You act consistently given your preferences & constraints & behavior of others



### Game theory characteristics <br>
(1) Strategy = players contingency plan or decision rule (optimal action in every possible scenario) <br>

(2) Timing of play <br>
$\quad$ (a) Static game = each player moves without knowing their opponents move <br>
$\quad$ (b) Dynamic game = order of play is sequential <br>

(3) Informtion Set = info each player has at each stage of the game <br>
$\quad$ (a) Complete information = each player knows the payoff / objective of every other player <br>
$\quad$ (b) Perfect information (dynamic games only) = each player knows the history of the other players in the game <br>
$\quad$ (c) Common knowledge = Information known by everyone in the game, everyone knows everyone else knows <br>
$\quad$ (d) Symmetric information = each player has the same set of information <br>


**Rules of the game** <br>
(1) Players <br>
(2) Actions <br> 
(3) Timing of play <br> 
(4) Payoff function of each player <br>
(5) Information available

---

# 3.2 Static Games + Complete Information

Everyone moves without knowing the others player's moves, but everyone knows the other players objectives.

---

## (1) Coordination games 
Players benefit from cooperating, Communication before playing the game helps with the final outcome<br>

**Example 1: Driving on one side of the road**
It doesn't matter whether people choose left or right as long as they make the same choice.

**Example 2: Pareto Coordination Game**
There is one outcome that would be best for everyone, but another where they will benefit more than the rest of the options.
Both choosing the one correct box $\:$$\:$  >$\:$ $\:$  both choosing a different box $\:$ $\:$  > $\:$ $\:$ choosing different boxes <br>

**Example 3: Dating game** <br>
Guy likes meat + red wine<br>
Girl likes fish + white win<br>
**Good:** Meat + red OR fish + white <br>
**Bad:** Meat + white OR fish + red<br>

Guy brings fish to make girl happy<br>
Girl brings red wine to make guy happy<br>
Dinner = ruined<br>

---

![coordinate.png](attachment:coordinate.png)

---

## (2) competitive games 

**Example 1: Zero sum games (Matching pennies)** <br>

**Example 2: Not zero sum (War - each side wants the other to be peaceful.)** <br>
From the perspective of A: <br>
Best result = They are peaceful, we attack (+3) <br>
2nd best result = We are both peaceful (+2) <br>
3rd best result = They attack, we are peaceful but limited damage (+1) <br>
4th best result = We both attack, full war (-1)

**Example 3: Prisoners Dilemma** <br>
Similar to war from above, but now the "3rd best" option from above is going to be the worst for us. Not confessing is a bigger risk.

---

![compete.png](attachment:compete.png)

---

## (3) Static games 3 types of equilibrium

**1st - Dominant Strategy Equilibrium** <br>
Strictly dominant strategy = choice that earns higher payoff than any other strategy <br>
If both players have a strictly dominant strategy, the result will be a **dominant strategy equilibrium** <br>
Example: Negative political ads


**2nd - Iterated-Dominant Strategy Equilibrium** <br>
Example: Pig Push vs Not
Players will elimate dominated strategies until they find a solution

**3rd - Nash Equilibrium** <br>
The equilibrium where neither player would be better off making a change <br>
Pure strategy (predictable) = decision rule that does not involve randomizing <br>
Mixed strategy (unpredictable) = sometimes choose one, sometimes choose the other <br>

$\quad$ **Finding a mixed strategy Nash equilibrium to a game like matching pennies** <br>
$\quad$ (1) Define possible mixed strategies <br>
$\quad$ (2) Identify each players best reply function (the best response to each possible move by the opponent) <br>
$\quad$ (3) Mixed stratgy nash equilibrium = where the best replies of each player equal one another


-----

# 3.3 Dynamic Games + Perfect Information


**Nodes** <br>
(1) Decision node = any point where a player is making a decision <br>
(2) Initial node = Very first decision <br>
(3) Terminal node = very bottom of the lowest branches <br>

**Threats** <br>
(1) False belief = you think the other player will do something if you don't give in, but they actually won't <br>
(2) Credible threat = they actually will go through with what they're saying

![syria1.png](attachment:syria1.png)

---

![syria2.png](attachment:syria2.png)

---

![syria3.png](attachment:syria3.png)

---

# 3.4 Repeated games


**Finite repeated games** <br>
Tit for tat = we cooperate with our competitor because it helps us out in the end <br>

**Infinite repeated games (super games)** <br>
Trigger strategy = they cooperated with us last time, we will this time, they will next time, etc <br>
To solve, we have to decide whether the PV of all future returns from cooperating is greater than competing <br>




$\pi \quad$ = **5mil** (payoff from cooperating each period) <br>
$PV \: \:$ = **10mil** (payoff for competing in first period, 0 afterwards) <br>
$\beta \quad$ = Discount factor (.9 would be someone who cares about the future a alot)

$ Value(\pi,\infty) = \frac{\pi}{1-\beta} = PV $ <br>

$ Value(\pi,\infty) = \frac{5}{1-\beta} \geq 10 $ <br>
So in this example, we should only cooperate if our discount value is $\geq$ than .5


