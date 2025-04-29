# ai-3000-cs-5500-reinforcement-learning-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [AI 3000 / CS 5500 : Reinforcement Learning Assignment № 3 Solved](https://www.ankitcodinghub.com/product/ai-3000-cs-5500-reinforcement-learning-assignment-%e2%84%96-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110721&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;AI 3000 \/ CS 5500 : Reinforcement Learning Assignment № 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Problem 1 : Importance Sampling

Consider a single state MDP with finite action space, such that |A| = K. Assume the discount factor of the MDP γ and the horizon length to be 1. For taking an action a ∈ A, let Ra(r) denote the unknown distribution of reward r, bounded in the range [0,1]. Suppose we have collected a dataset consisting of action-reward pairs {(a,r)} by sampling a ∼ πb, where πb is a stochastic behaviour policy and r ∼ Ra. Using this dateset, we now wish to estimate V π = Eπ[r|a ∼ π] for some target policy π. We assume that π is fully supported on πb.

(a) Suppose the dataset consists of a single sample (a,r). Estimate V π using importance sampling (IS). Is the obtained IS estimate of V π is unbiased ? Explain. (2 Points) (b) Compute

(1 Point)

(c) For the case that πb is a uniformly random policy (all K actions are equiprobable) and π a deterministic policy, provide an expression for importance sampling ratio. (1 Point)

(d) For this sub-question, consider the special case when the reward r for choosing any action is identical, given by a deterministic constant r [i.e., r = R(a), ∀a ∈ A]. For a uniform behaviour policy πb and a deterministic target policy π, calculate the variance of V π estimated using importance sampling (IS) method. (5 Points)

[Note : Variance needs to be estimated under measure πb]

(e) Derive an upper bound for the variance of the IS estimate of V π for the general case when the reward distribution is bounded in the range [0,1]. (3 Points)

(f) We now consider the case of multi-state (i.e |S| &gt; 1), multi-step MDP. We futher assume that µ(s0) to be the initial start state distribution (i.e. s0 ∼ µ(s0)) where s0 is the start state of the MDP. Let τ denote a trajectory (state-action sequence) given by, (s0,a0,s1,a1,··· ,st,at,···) with actions a0:∞ ∼ πb. Let Q and P be joint distributions, over the entire trajectory τ induced by the behaviour policy πb and a target policy π, respectively. Provide a compact expression for the importance sampling weight . (3 Points)

Problem 2 : Game of Tic-Tac-Toe

Consider a 3×3 Tic-Tac-Toe game. The aim of this problem is to implement a Tic-Tac-Toe agent using Q-learning. This is a two player game in which the opponent is part of the environment.

(a) Develop a Tic-Tac-Toe environment with the following methods. (5 Points)

(2) An act method that takes as input a move suggested by the agent. This method should check if the move is valid and place the ’X’ in the appropriate board position.

(3) A print method that prints the current board position

(4) You are free add other methods inside the environment as you deem fit.

(b) Develop two opponents for the Q-learning agent to train against, namely, a random agent and safe agent (5 Points)

(1) A random agent picks a square among all available empty squares in a (uniform) random fashion

(2) A safe agent uses the following heuristic to choose a square. If there is a winning move for the safe agent, then the corresponding square is picked. Else, if there is a blocking move, the corresponding square is chosen. A blocking move obstructs an opponent from winning in his very next chance. If there are no winning or blocking moves, the safe agent behaves like the random agent.

(c) The Q-learning agent now has the task to learn to play Tic-Tac-Toe by playing several games against safe and random opponents. The training will be done using tabular Q-learning by playing 10,000 games. In each of these 10,000 games, a fair coin toss determines who makes the first move. After every 200 games, assess the efficacy of the learning by playing 100 games with the opponent using the full greedy policy with respect to the current Q-table. Record the number of wins in those 100 games. This way, one can study the progress of the training as a function of training epochs. Plot the training progress graph as suggested. In addition, after the training is completed (that is after 10,000 games of training is done), the trained agent’s performance is ascertained by playing 1000 games with opponents and recording the total number of wins, draws and losses in those 1000 games. The training and testing process is described below. (15 Points)

(1) Training is done only against the random player. But the learnt Q-table is tested against both random and safe player.

(2) Training is done only against the safe player. But the learnt Q-table is tested against both random and safe player.

(3) In every game of training, we randomly select our opponent. The learnt Q-table is tested against both random and safe player.

(4) Among the three agents developed, which agent is best ? Why ?

(5) Is the Q-learning agent developed unbeatable against any possible opponent ? If not, suggest ways to improve the training process.

ALLTHEBEST
