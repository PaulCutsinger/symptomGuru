# symptomGuru
example Alexa skill showing synonyms, dialog management, and ER_SUCCESS_NO_MATCH

In the interaction, notice a few turns that work, then, in the last turn, the person uses the word "tummy" which is not in the model. So, the developer gets an ER_SUCCESS_NO_MATCH and can log the value "tummy" to add as a synonym of abdominal.
![alt text](https://github.com/PaulCutsinger/symptomGuru/blob/master/pics/CP_tummy_sim.PNG "example interaction")

To do this, here are the utterances and slots
![alt text](https://github.com/PaulCutsinger/symptomGuru/blob/master/pics/CP_symptom_utterances.PNG "utterances and slots")

matched up with example utterances
![alt text](https://github.com/PaulCutsinger/symptomGuru/blob/master/pics/CP_utterances_to_sample_phrases.PNG "example utterances ")

and some of the slot values.
![alt text](https://github.com/PaulCutsinger/symptomGuru/blob/master/pics/CP_symptom_slot_values.PNG "slot values")



Here are a few related resources:
- a tutorial for building your own skill that requests multiple slots: https://alexa.design/dialogtask1
- a sample that calls an api https://github.com/alexa/skill-sample-nodejs-petmatch
- a sample that without an api call https://github.com/alexa/skill-sample-nodejs-decision-tree

