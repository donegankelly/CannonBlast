# Cannon Blast - An explosive new smartphone approach to measuring model-based planning

Cannon Blast is a gamified version of the two-step reinforcement learning task developed by Daw an colleagues (Daw et al., 2011) which subtly measures model-based planning within a diamond-shooting game. 

The goal of Cannon Blast is to hit as many diamonds as possible using a finite source of balls (100 shoots per block). To do so, you must aim the central cannon and then choose to load a ball from one of two containers that flank the cannon. The balls dynamically bounce around in the containers and reflect the probability of a specific-coloured ball being loaded. For example, the left container contains 8 purple balls and 2 pink balls and so, by choosing the left you have an 80% chance of loading a purple ball ("common") and 20% chance of loading a pink ball ("rare"). The coloured balls each have independent reward values that drift throughout the game. This value is defined as the probability of being rewarded with a "good" ball to shoot with. Alternatively, you might be unrewarded with a "dud" ball that explodes upon firing and thus forbids from shooting the diamond. The probability of being rewarded drifts independently over the course of the task. Check out ‘Cannon Blast Trials’ file to see how we gamified the traditional transition and reward features of a trial into a diamond-shooting game (!)

We can then use this to calculate the probability of repeating your choice (‘stay’ behaviour) based on if the trial previous was a common/rare transition or if it was rewarding or not. Check out ‘Cannon Blast Graph’ video to see how a players stay probability changed over the course of the game.


Latest findings using this task are available to read as a pre-print now at: https://psyarxiv.com/hpm4s 
