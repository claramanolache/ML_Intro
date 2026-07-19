I was curious about how self-driving cars and advanced driver-assistance systems address explainability. In an autonomous vehicle, this could mean determining what objects the vehicle detected, how it interpreted the road, why it selected a particular route, or why it failed to brake before a collision. Because mistakes made by driving systems can injure or kill people, explainability is not merely a technical preference. It is important for accident investigations, safety testing, public trust, and legal accountability. For this question, I looked into two main cars, Waymo—which is fully self-driving—and Tesla—which classifies itself as an advanced driver-assistant. While Tesla is technically only a driver-assistance, it’s advertised as a fully self-driving car and is used by many in such a way. 


Unfortunately, there have recently been a lot of Tesla Crashes when using their autonomous mode. On June 23, 2026, for example, a Tesla Model 3 crashed into a house in Katy, Texas, killing a woman inside. The family of the woman sued Tesla, but they were able to prove it was not their fault by checking the driver logs. Here, they found that the driver actually accelerated the car. However, many similar lawsuits have occurred throughout Tesla companies history. While Tesla has won some of these lawsuits by claiming to be a type two autonomous vehicle (that requires human supervision), many cases ended in settlement and one lawsuit cost the company $200 million in damages. To win such cases or to ease public concern, explaining and fixing exactly where the model errored is important. For this, Tesla needs to ensure their code has explainability. 


I found that tesla uses a singular end-to-end neural network that learns the complete driving task. This is definitely not the most explainable approach. When comparing Tesla to Waymo, I was initially surprised by how similar the models were. While Waymo initially tried to hand-engineer different rules, they found that this approach was too complicated and in a way “overfit” to the city. So, the company went with a neural network approach, like Tesla. However, it separates as Waymo uses a hybrid approach, with modular neural-network systems and several large components trained together. It also uses a Gemini-based vision-language model when the car is in unusual situations, like for instance when receiving police instructions. Even though Waymo abandoned the more human approach, it still has more explainability then the Tesla because the engineers know what each individual component does. For example, if a Waymo hits a pedestrian, they can individually test whether the sensor-fusion encoder detected every pedestrian. 


The difference shouldn’t be very surprising. Waymo is the first fully automated commercial vehicle, so it had to do a lot of work to prove to the public that it is safe. Meanwhile, Tesla wants their car to be fully automated but legally can’t say that cause they know its not safe. Once, Elon said "Even if you save 90% of the lives, the 10% that you don't save are going to sue you." This value has been restated many times throughout Elon's career, and he said that wouldn’t disable the autodriver feature but it was mere years away from being perfect. So, explainability wouldn’t be a concern for someone who doesn’t much value the safety of the testing data. 


Ultimately, the comparison between Waymo and Tesla demonstrates a central conflict in modern artificial intelligence. Companies must balance robustness and explainability (as Waymo initially did in favor of robustness) as well as speed and simplicity (which Tesla favored over explainability). These choices often reflect the values of the companies producing the models. 


### Sources:

[Tesla's Recent Crash](https://www.nbcnews.com/news/us-news/fatal-texas-tesla-automated-driving-assistance-crash-lawsuit-rcna351485)

 
[Tesla Settlement](https://www.statesman.com/business/article/tesla-fatal-crash-lawsuit-fsd-probe-nhtsa-22324167.php)


[Waymo vs Tesla System](https://www.understandingai.org/p/waymo-and-teslas-self-driving-systems)
