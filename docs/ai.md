# AI

## Approaches

- Behaviourtree
- Neural Network
- Automat
- **Utility system**

### Reducing predictability

Rather than changing into set stages at certain arguments there could be a weighted picker instead. So instead of always chosing one state and being determined there is a certain chance to do one thing - but it can also do something else. As an example the agent might want to flee, but instead of fleeing 100% of the time the evaluation results in a 80% chance to flee. So 20% of the time the agent actually fights more aggressive, or even more than just two results.

## Utility AI

Every input gets mapped via function to a certain score. The potential actions then evaluate relevant parameters into their own score. The highest scoring action will prevail and executed.

- Simple to design
- Easily extendable
- Better quality

Implementing the reduced predictability is also easily possible. Instead of choosing the highest scoring action one might add a weighted picker based on the score. E.g. with a score of 0.9 an action has a 90% weight. Each following action can be added in the remaining 10% and evaluated. There might be some math necessary and the action evaluating itself needs to be a little more precise.

**Input Parameter**

- Proximity to Player
- Knows of Player
- ...