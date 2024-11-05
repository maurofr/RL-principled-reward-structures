# Enhancing Rocket League AI Performance Using Proximal Policy Optimization with Principled Reward Structures

## Abstract
_AI systems have consistently surpassed human performance in various games, marking significant milestones in artificial intelligence development. From IBM’s Deep Blue defeating chess grandmaster Garry Kasparov to Google’s AlphaGo mastering the ancient game of Go, these achievements highlight AI’s tactical prowess. Today, state-of-theart AI systems outperform these benchmarks, exceeding human prowess in both board and video games._

_Rocket League, a popular multiplayer sports video game blending soccer with vehicular action, has emerged as a dominant force in esports since its 2015 debut. Its dynamic gameplay, which emphasizes teamwork and mechanical skill, presents a unique challenge. In this study, we demonstrate how a reinforcement learning algorithm, initialized from scratch, rapidly surpasses players with extensive gameplay experience. Furthermore, by crafting a concise set of shaping rewards based on the game’s core principles, we illustrate how the AI can autonomously acquire advanced game mechanics through self-play._

_By leveraging these techniques, our research sheds light on the adaptive and learning capabilities of AI systems in mastering complex real-time environments like Rocket League._

## Full paper

To read the full paper, follow [this link](<Enhancing Rocket League AI Performance Using Proximal Policy Optimization with Principled Reward Structures.pdf>).

## Agent performance
### Early mechanics

We found that between 1-2 billion steps the bot already was experimenting with half flips and predicts. Look at this nice goal!

![Half flip into predict goal](https://github.com/maurofr/RL-principled-reward-structures/blob/main/Clips/hf_pred.gif)

In this clip the bot's car is a Fennec, even though an Octane was used through the entire training. 

### Outplay

In this clip, the bot outplays himself in self-play with a nice corner play and leveraging ball height. 

![Outplay](https://github.com/maurofr/RL-principled-reward-structures/blob/main/Clips/opp_outplay.gif)

### Wall shots

We can also see the consistency of the bot from the wall, scoring these two impressive goals in the same game due to the opponent not being fast enough.

![Wall Goal 1](https://github.com/maurofr/RL-principled-reward-structures/blob/main/Clips/wg1.gif)
![Wall Goal 2](https://github.com/maurofr/RL-principled-reward-structures/blob/main/Clips/wg2.gif)

### Aerial touch

The bot is also learning to fly and hit consistent aerial touches. 

![Aerial touch](https://github.com/maurofr/RL-principled-reward-structures/blob/main/Clips/aerial_touch.gif)

He still has room to improve, as the shot could have been a field-to-field goal!

### Leveraging momentum

Finally we show this play where the bot gets the 100 boost and uses it to gain momentum, reach supersonic speed and use that to out-speed the opponent and clearly win a fifty for a goal.

![Momentum play](https://github.com/maurofr/RL-principled-reward-structures/blob/main/Clips/momentum_long_shot.gif)
