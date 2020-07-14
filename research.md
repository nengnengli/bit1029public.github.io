---
title: Research
layout: page
collectionpage: pages

---

<style type="text/css">
.fig {
  display: block;
  margin-left: 20px;
  float: right;
}
</style>

<!---
Read about our current projects on
[Inverse Reinforcement Learning](#Inverse Reinforcement Learning),
,

and ....
--->


---

##### **DRL agent in Rabbids: 100% win rate against human-players**
_Key people: Li Zhang_

<p style="text-align:justify;">In the cooperation of our lab and <a href="https://www.ubisoft.com">Ubisoft</a>, we designed a novel DRL framework and applied it to train agents in Rabbids: Journey To The West, a party game of <a href="https://en.wikipedia.org/wiki/Raving_Rabbids">Rabbids series</a>, which is a famous title presented by Ubisoft.</p>

<div style="float:left;border:solid 1px 000;margin:20px;"><img src="/images/co.png" height="100"></div>
<div style="float:left;border:solid 1px 000;margin:20px;"><img src="/images/rabbids.gif" height="100"></div>
<div style="float:none;clear:both;"></div>

<p style="text-align:justify;">To test our agents, we organized some competitions, in which three human-players formed a team and collaborated to compete with a single agent trained by our method. This event attract many people to join, but no team beat our agent, yielding a 100% win rate of our agent.</p>

##### **UVIN: An Universal DRL Method to Combine Planning and Learning**
_Key people: Li Zhang_

<p style="text-align:justify;">Most existing DRL approaches focus on leveraging the deep neural network structure to approximate the value function via a trial-and-error learning process, but insufficiently address explicit planning computation as in the conventional model-based approaches. We proposed Universal Value Iteration Networks (UVIN) to combine model-free learning and model-based planning in common RL setting to improve long-term reasoning and inference.</p>

<div style="float:left;border:solid 1px 000;margin:20px;"><img src="/images/minecraft.gif" height="100"></div>
<div style="float:left;border:solid 1px 000;margin:20px;"><img src="/images/maze.png" height="100"></div>
<div style="float:none;clear:both;"></div>

<p style="text-align:justify;"><a href="https://www.minecraft.net">Minecraft</a> is a popular sandbox video game that allows players to explore, gather, and craft in a 3D world. To collect the desired items in the inventory, players need to plan whether to search for or synthesize a new item, and how. Thus, Minecraft is a typical problem requiring long-term reasoning. UVIN significantly outperforms other state-of-the-art approaches (<a href="https://arxiv.org/abs/1806.06408">GPPN</a>, <a href="https://arxiv.org/abs/1706.02416">GVIN</a>, <a href="https://arxiv.org/abs/1602.02867">VIN</a>, <a href="https://arxiv.org/abs/1710.02298">Rainbow</a>) in Minecraft and some variants of maze navigation we introduced. UVIN has been accepted as a conference <a href="https://aaai.org/Papers/AAAI/2020GB/AAAI-ZhangL.10191.pdf">paper</a> by AAAI-2020.</p>

##### **ADRQN: On Improving Deep Reinforcement Learning for POMDPs**
_Key people: Pengfei Zhu_

<p style="text-align:justify;">Most of Deep Reinforcement Learning (DRL) methods focus on Markov Decision Process (MDP). Partially Observable Markov Decision Process (POMDP) is an extension of MDP, it can naturally model planning tasks with uncertain action effects and partial state observability, but finding an optimal policy is notoriously difficult. Inspired by belief state update based on Bayes’ theorem, we proposed Action-specific Deep Recurrent Q-Network (ADRQN) to improve DRL in POMDP. </p>

<div style="float:left;border:solid 1px 000;margin:20px;"><img src="/images/atari.gif" height="100"></div>
<div style="float:left;border:solid 1px 000;margin:20px;"><img src="/images/doom.gif" height="100"></div>
<div style="float:none;clear:both;"></div>

<p style="text-align:justify;"><a href="https://en.wikipedia.org/wiki/Atari_2600">Atari 2600</a> is a classical video game set and is used as benchmark tasks in many DRL research. We evaluated ADRQN in a flickering version of Atari, which obscuring the entire screen with a certain probability at each time step. Further more, a 3D video game <a href="https://en.wikipedia.org/wiki/Doom_(1993_video_game)">Doom</a> is also used to evaluate our model. ADRQN achieves better performance than baseline methods (<a href="https://web.stanford.edu/class/psych209/Readings/MnihEtAlHassibis15NatureControlDeepRL.pdf">DQN</a>, <a href="https://arxiv.org/abs/1507.06527">DRQN</a>, <a href="https://arxiv.org/abs/1602.02672">DDRQN</a>) in flickering Atari and Doom. The citations of <a href="https://arxiv.org/pdf/1704.07978.pdf">ADRQN paper</a> are up to 30 now.</p>

##### **Inverse Reinforcement Learning**

_Key people: Jie Huang_

<p style="text-align:justify;">Inverse Reinforcement Learning is mainly for complex tasks where the reward function is difficult to formulate. We hope that this method can find an efficient and reliable reward function. We assume that when an expert completes a task, his decision is often optimal or close to optimal. When the cumulative reward function expectations of all policies are not greater than the cumulative return expectations of expert policies, the corresponding reward function is the reward function learned according to the expert demonstrations. </p>

<p style="text-align:justify;">In general, the inverse reinforcement learning is to learn the reward function from the expert demonstrations, which can be understood as explaining the expert policy with the reward function we learned.When learning policies based on optimal sequence samples is needed, we can combine reverse reinforcement learning and deep learning to improve the accuracy of the reward function and the effect of the policy. </p>

<p style="text-align:justify;">Our work is to use the imitation learning algorithm or inverse reinforcement learning algorithm to solve related complex tasks, and apply it to the robot (Figure 1 below) and its simulation environment (Figure 2 below), so that it can be learned using the training set demonstrated by the experts and get the Same effect as expert. </p>

<div style="float:left;border:solid 1px 000;margin:20px;"><img src="/images/projects/dogbot.jpg" height="100"/></div>

<div style="float:left;border:solid 1px 000;margin:20px;"><img src="/images/projects/dogbot2.jpg" height="100"/></div>



