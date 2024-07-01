# Enhancing Rocket League AI Performance Using Proximal Policy Optimization with Principled Reward Structures

This repository showcases the performance of an the AI agent trained in the paper _Enhancing Rocket League AI Performance Using Proximal Policy Optimization with Principled Reward Structures_.

### Early mechanics

We found that between 1-2 billion steps the bot already was experimenting with half flips and predicts. Look at this nice goal!

![Half flip into predict goal](https://github.com/maurofr/RL-principled-reward-structures/blob/main/Clips/hf_pred.gif)

In this clip the bot car is a Fennec, even though an Octane was used through the entire training. 

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

Finally we show this play where the bot gets the 100 boost and uses it to gain momentum, reach supersonic speed and score a goal due to having much more momentum than the opponent.

![Momentum play](https://github.com/maurofr/RL-principled-reward-structures/blob/main/Clips/momentum_long_shot.gif)