# Applying Neutral Theory to the Gut: How Do Inflammatory Bowel Diseases and Broccoli Bioactives Affect Gut Microbial Ecology?
Project by Lola Holcomb

## What was your question?

For this project I attempted to use Sloan's neutral theory as a lens to study large 16S bacterial datasets in attempt to better understand how broccoli, as a dietary intervention for IBD, affects gut microbial ecology. Some questions I wanted (and want) to answer are: how do IBDs and dietary treatments for them affect gut microbial ecology? Do gut microbes adhere to neutral theory under these two conditions?

## How did you try to approach it?

I used several R packages to analyze alpha diversity and beta diversity of the samples within our large datasets. Then, I performed litarture searches and github searches to try and piece together a script that would let me use functions to test my dataset's adherence to the neutral model. I haven't yet accomplished this second part.

## What did you find? OR, what obstacles did you encounter?

A key finding from the beta diversity bacterial community analyses performed in this study is that gut microbiota seem to stabilize in early life. I found that bacterial richness and diversity was greater in the 4-week-old trial 1 mice than in the 7-week-old trial 2 mice. Also, microbiota stabilization is associated with reduction of interindividual variation (beta-diversity) in bacterial communities (Derrien et al.  2019). The principal coordinates analyses performed in my study reflect such a trend, in that the older trial 2 mice exhibit a lesser degree of Jaccard dissimilarity across experimental groups compared to their trial 1 counterparts.

Regarding our the diet variable, I found that that controls had greater prevalence and abundance of the inflammatory/harmful bacteria, such as Helicobacter.  Mice fed the broccoli diet showed increased bacterial species richness in the gut, lesser prevalences and abundances of pro-inflammatory microbes, and greater prevalences and abundances of anti-inflammatory microbes. Taken together, we can theorize that a broccoli diet may promote a rich and diverse gut microbiome, while potentially protecting against inflammation-causing bacteria

Unfortunately, though, I was unable to accomplish my goal of figuring out whether mice with IBD with or without a broccoli diet adhere to Sloan's neutral model.  The codes I found in my literature and github searches were lasted updated in 2015, and now, in 2022, basically all of the them are out of date and unusable. So, I've been working on drafting a new code from pieces I found in literature and online, but I need more time to get it to work.

## What do you think are the next steps?

It is my hope that with a little more time, patience, reading, and learning, that I'll eventually be able to write a script that allows me (and hopefully others in the future) to run 16S microbial datasets through various functions that will determine the degree of community adherence to neutral theory. I'd also like to generate figures that show adherence (or lack thereof) to the model.

## What would be your words of wisdom to someone trying to continue this work?

Be patient. Take the time to understand what the the packages you're using do, and what parameters are needed in your call lines. Try to thoroughly understand the functions you're working with, too -- it'll make it easier to figure out why they might fail to work. Remember, you're doing cool stuff with this line of research. You're thinking about things and asking questions that may not have been asked before.

## Some sources I used to start drafting my script:
- https://github.com/Russel88/MicEco/#neutralfit
- https://www.nature.com/articles/ismej2015142#MOESM51
- https://www.rdocumentation.org/packages/stats4/versions/3.6.2/topics/mle
- https://www.rdocumentation.org/packages/stats/versions/3.6.2/topics/optim
- https://stackoverflow.com/questions/64477268/mle-function-error-in-optimstart-f-method-method-hessian-true-n

