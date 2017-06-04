Gouty McGoutface: Smiling at the face of excess uric acid production
====================================================================

# Introduction & Background
I've recently been diagnosed with [gout](https://en.wikipedia.org/wiki/Gout), at the tender age (at time of writing) of ~35. Following inspiration from [this post](https://github.com/arielf/weight-loss) regarding the use of [Vowpal wabbit](https://github.com/JohnLangford/vowpal_wabbit/wiki) to, in essence, use regression to understand the impact of diet and lifestyle on weight loss, I plan to adapt it to understand the impact of diet and lifestyle choices on my uric acid levels, the seemingly determinant factor in suffering from gout. 

## Caveats & nota bene

Chances are, if you're reading this, I've asked you to, coz you are well smart, innit, and I value your thoughts and input on the situation, bosh. As such, please:
* bring your A-game
* do **not** pull any punches: great feedback is clear, not mean. Feel free to tear apart as required from an academic critique perspective
* ... and no, I couldn't find the spellcheck

## Initialisation -- About me & this project
### Me
* White male, born early 1980's
* History of gout on the paternal side

### Disease history
At time of writing, I've experienced three acute gout attacks:

1. 2012: Following running. 
2. 2106: Following _barefoot_ running. (There was an issue getting the Vibrams onto my right foot, where I bent the right "ring" toe underneath the foot, effectively trapping it in the shoe, and then having to stand on it. Following walking on this foot awkwardly over the following days, this seemed to induce an acute gout response)
3. 2017: Eating three meals consisting of seafood in succession:
    * Sushi, and two glasses of red wine -- note that I was mostly teetotal for ~6weeks prior to this point
    * Crayfish salad
    * Haddock

### Diagnosis & pharmacotherapy

* From seeing a consultant rheumatologist in May-2017, he diagnosed gout.
* He prescribed [allopurinol](https://en.wikipedia.org/wiki/Allopurinol), a xanthine oxidase inhibitor -- so, to my lay eyes, preventing purines from being fully metabolised to uric acid, hence preventing/reducing [hyperuricemia](https://en.wikipedia.org/wiki/Hyperuricemia). 

# Protocol

The plan, in short, is to (a) go get data, and (b) work out what impacts my personal uric acid reading. 

## Equipment & pre-requisites

* From this [2014 poster](https://www.smithbiomed.com/wp-content/uploads/2015/09/Uric-acid-meters-poster.pdf) it appears that not all uric acid monitors for use at home are born identical.... The Benecheck Plus system appears to be available in the UK -- see here [http://www.millermedicalsupplies.com/diagnostics/cholesterol-meters-strips/benecheck-meters-strips/benecheck-plus-multi-monitoring-system-with-carry-case-lancing-pen-and-lancets](http://www.millermedicalsupplies.com/diagnostics/cholesterol-meters-strips/benecheck-meters-strips/benecheck-plus-multi-monitoring-system-with-carry-case-lancing-pen-and-lancets). 
* Electronic scale. 

## Method & Approach

### Gather baseline data

* Gather 30 days' worth of readings: Take daily uric acid readings at 9.30am local time. Main point here is to understand any potential variability in readings. 
* Maintain diet of items considered to be *safe* -- i.e. avoid bloody crayfish...
* Data to track: 
    * Liquid consumed, type and amount
    * Food consumed -- use the scales to track precise amounts of food consumed

### Start playing with things :sunglasses:

* Vary intake as per folklore, random ideas... What happens when I have a pint of beer? (Potential thought: if beer is that bad for uric acid, maybe try a pint and watch for the uric acid spike?) 

### Other data points to collect (potentially)

* Sleep: Use a FitBit to track amount of time asleep. 
* Environmental info -- temperature and humidity: (Remain unconvinced this is necessary) Find a website to show average daily temperature and humidity, and track
* Activity -- maybe?
* Thought -- the error term could be particularly interesting... How much uric acid change is due to factors not measured?

## Analysis

TBC -- I imagine regression analysis of some description. 

# Open loops
* How will regression deal with potential time delay of change in uric acid levels? E.g. imagine that one beer is drunk on day 1, but the resulting change in uric acid occurs on day 4. (Ask RowChief about this)
* What's the timeline for metabolising purines to uric acid?
* Is there any value in being genetically screened for the particular mutation? (If you had this though, what would you do with the knowledge?) 
* Probability of your rheumatologist having kittens when he finds out you've blatantly ignored his advice = high. Is what's being proposed here sufficient for him to write up as a letter to a journal? (probably not sufficient for a paper with a single subject...) Can I find out somehow if he is active in research?

# Coda -- philosophy behind this approach

So, obvious question here: Am I merely delaying the inevitable here, in that at some point -- probably soon -- I will simply have to start taking the prescribed medication, yes?

More than likely, yes. 

However, the ultimate issue in events like this is the lack of agency over one's predicament: The analogy that springs to mind is that of the athlete who retires on the treatment table due to injury, as opposed to taking their leave from the field of play of their own volition. 

At least by undertaking the above, as hare-brained as it might appear, is that at least it *feels* like I am doing to something to control the outcome, and not simply being done unto, and that hopefully I can manifest change. Further, as everyone's gout appears to be different, I will develop a better understanding of how mine operates. 

***

# References
* The main weight loss article using Vowpal Wabbit: [https://github.com/arielf/weight-loss](https://github.com/arielf/weight-loss)
* The article reviewing uric acid monitors: [https://www.smithbiomed.com/wp-content/uploads/2015/09/Uric-acid-meters-poster.pdf](https://www.smithbiomed.com/wp-content/uploads/2015/09/Uric-acid-meters-poster.pdf)
