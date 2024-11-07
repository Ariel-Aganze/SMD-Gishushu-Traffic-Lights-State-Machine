# SMD-Gishushu-Traffic-Lights-State-Machine

The traffic light system operates with four distinct states: Red, Red + Yellow, Green, and Yellow. Initially, the traffic light is in the Red state for a specific duration, indicating that all traffic must stop. Following this, the traffic light moves to the Red + Yellow state, lasting for around 3 seconds, signaling caution for the upcoming change.

Next, the traffic light switches to the Green state, permitting traffic to proceed. After a certain duration in the Green state, the traffic light transitions to the Yellow state, lasting for another 3 seconds, indicating that the traffic should prepare to stop as the light will soon turn Red.

1. State: Red
   __________

Initial state
Transition: After staying in this state for a specific duration, it moves to the next state.

2. State: Red + Yellow
   ___________________

Transition: This state is a transition state from Red to Green, indicating caution for the upcoming change.
Duration: Approximately 3 seconds

3. State: Green
   ____________

Transition: After Red + Yellow state, it moves to this state, allowing traffic to proceed.
Transition: After staying in this state for a specific duration, it moves to the next state.

4. State: Yellow
   _____________

Transition: This state is a transition state from Green to Red, indicating that the traffic should prepare to stop.
Duration: Approximately 3 seconds
