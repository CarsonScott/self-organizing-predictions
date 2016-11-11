# Self Organizing Predictions

## Prediction Agents
&nbsp;&nbsp;&nbsp;&nbsp; How can we possibly know anything about the future if it hasn’t happened yet? That’s easy: by looking at the past. When we experience a novel event or feeling, especially those with emotional connotations, we are driven to reproduce it. We ask ourselves, what was the cause? 

&nbsp;&nbsp;&nbsp;&nbsp; Causal relationships occur in one direction: forward. Cause-and-effect is a temporal-based process in which current events lead to future events. When we experience unknown or unexpected stimuli, we react with surprise. This jolt of internal stimulation is due to our natural aversion toward things that don’t fit our understanding of the world. We compensate by either internalizing new information to revise our knowledge, or by keeping ourselves from believing what is true.

&nbsp;&nbsp;&nbsp;&nbsp; In any case, we are driven to maximize expected results. The most effective way of doing so is by learning from our mistakes. When faced with a surprising event, we quickly process the moments leading up to it. Assuming that current events cause future events, and thus that past events caused current events, we can infer that the sequence of recent events are somehow related to what is currently happening. So how do we represent this association?

&nbsp;&nbsp;&nbsp;&nbsp; When the input set is activated, a signal is sent to the output that decreases the thresholds, which the leads information to activate in response to a lower amount of stimuli that they did before. This causes anticipation when a prediction is made, leading to greater attention applied to the result and thus more accurate corrections to the agent when it gets things wrong.

&nbsp;&nbsp;&nbsp;&nbsp; When we are surprised by an event, a sequence agent forms input connections from recent events and output connections to current events. This means that next time we experience events similar to what has recently occurred, the surprising event will be expected. Fool me once.

![Agents](https://github.com/CarsonScott/self-organizing-predictions/blob/master/Prediction%20Agents.jpg "Prediction Agent")

***

## Bad Predictions
&nbsp;&nbsp;&nbsp;&nbsp; A prediction agent forms connections with neurons that collectively represent a moment in time. This pattern is believed to cause the output pattern representing another moment in time. The agent receives input signals from active neurons, which are multiplied by a weight and summed to find the total activation. This is compared to a threshold which determines whether the prediction should be made. 

![Structure](https://github.com/CarsonScott/self-organizing-predictions/blob/master/Agent%20Structure.jpg "Agent Structure")

&nbsp;&nbsp;&nbsp;&nbsp; If the agent makes a prediction, feedback provides measured information that is compared to the predicted results. Success is measured by the percentage of overlap, and error is measured by the differences. This guides changes to certain weights in order maximize successful predictions.

&nbsp;&nbsp;&nbsp;&nbsp; Agents form when a set of information invokes surprise. That is to say that the expected events and possible alternatives had failed to consider the information to be an option, thus there were details of recent events that were not taken into account, may have led to the information being fully expected.

&nbsp;&nbsp;&nbsp;&nbsp; An agent must choose which information it connects to. There’s a possibility that the chosen set will contain irrelevant pieces of information. This is solved by learning how the inputs correlate to successful/unsuccessful predictions. Unsuccessful connections are eventually dropped, leaving the successful set of inputs to predict a pattern.

&nbsp;&nbsp;&nbsp;&nbsp; This enables the system to refine patterns by exploiting the fact that irrelevant neurons tend to be inactive when the important neurons are active. The important neurons will naturally invoke a correct solution, and therefore increase their own weights while decreasing the inactive weights. Once the weights reach zero, the connection disappears. A fully correlated input pattern is indicated when connections stop being removed from the prediction agent.

***

## Competing Theories
&nbsp;&nbsp;&nbsp;&nbsp; Prediction agents with a shared input pattern have to compete against each other for the ability to respond when the pattern is active. The dominant theory is chosen based on the average success rates of each agent, as well as the current magnitude of activation. The chosen agent suppresses the activation of its opponents. This decreases the inferior agents’ weights for all active connections that are shared with the dominant agent.

![Competing](https://github.com/CarsonScott/self-organizing-predictions/blob/master/Competing%20Agents.jpg "Competing Agents")

&nbsp;&nbsp;&nbsp;&nbsp; Over time, the dominant agent suppresses the opponents to take away their connections that overlap with the pattern. Eventually, the competing agents share no connections with the superior agent. The dominant prediction is the only remaining response, and its connections to the neurons are strong. This means that any competition arising in the future will be pushed out quickly. At the very least, any competition will have to spend an extensive amount of time and energy to defeat the superior agent because the accumulated strength of its connections makes it very difficult to lose any neurons.

&nbsp;&nbsp;&nbsp;&nbsp; The competing agents, now scattered, represent smaller patterns that don’t overlap with the superior agent, or they have lost all of their connections and reside in stock where they are used to learn new patterns. In this way the prediction agents in the system have self-organizing properties. The best agents force others to find new patterns to predict. Agents are on a constant journey to “find their purpose”. If they never achieve this, death and reincarnation occur and they try again with a new pattern.

***

## Agents and Neurons
&nbsp;&nbsp;&nbsp;&nbsp; When we make predictions, our representations describe the future in various time scales. If someone is taking a walk to a store, they're constantly predicting the placement of their feet, the street views around corners, how long it will take to reach the destination, what activities will take place once they arrive, etc., all at the same time.  But the various domains in which we make predictions are not constrained to current experiences. We also consider events that took place throughout the day, social interactions we engaged in, improvements we’d made in our work, and so on. These reflective trains of thought deal with a larger time scale than the thoughts we have when taking walk.

&nbsp;&nbsp;&nbsp;&nbsp; We may ask, what determines the time scale of ideas and expectations? The answer lies in how memories are stored in the brain. Networks of neurons are structured into discrete levels, where each level receives input from the level beneath it. This is why we can think about concepts that consist of combinations of other concepts without any piece of information disrupting another. Neurons at one level form connections to multiple neurons at a lower level, thus representing them as a single entity. An emergent property of this is pattern recognition, where the features of a pattern send activations to the next level in which a single neuron is activated that represents that pattern as a whole, given that enough of its features are present. Time scale of predictions relates to agents as complexity of patterns relates to neurons. 

&nbsp;&nbsp;&nbsp;&nbsp; If neural networks develop this kind of emergent behavior, then what's the point of prediction agents? Let's go back to the walk. If I located and removed all the agents in your head, what would you walk be like? You'd still recognize houses, streets, and signs, but they wouldn't do you any good. The usefulness of patterns does not reside in the pattern itself, but what we can infer from their presence.  If you decide to cross the street with your nose in your phone, and the distant hum of an engine is heard, you may think "that is the sound of a car". However, you'd fail to pick up on the implications of the car, your location, and Newton's three laws.

&nbsp;&nbsp;&nbsp;&nbsp; This is where prediction agents become a necessity. They allow processing that the fill in the blanks of hidden information, either because it can't be observed directly or because it hasn't occurred yet. Incorporating a temporal dimension compliments the spatial dimension of neural networks. Prediction agents help us learn from our mistakes and improve ourselves, which is beneficial across all domains.
