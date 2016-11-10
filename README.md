# self-organizing-predictions

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
