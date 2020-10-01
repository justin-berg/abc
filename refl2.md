## Reflection 2

Predicting Protein Folding With AI

Many of the most promising advancements in recent medicine have come from our manipulation of the so-called “central dogma of molecular biology”: Genetic information is stored in DNA, RNA is made based on DNA, and proteins are made based on RNA. Each of our proteins is made of a string of amino acids decided by our DNA sequence, and the way they react with one another determines how the protein folds into a 3D structure. For instance, pharmaceutical companies often develop drugs which have just the right shape and chemistry to block a malfunctioning protein from causing harm to our cells. Recent developments in gene editing and genome sequencing, with the help of data science, also let us alter the proteins that are made in cells. 

Now, one of the biggest challenges in biomedicine is predicting exactly how proteins will fold based on their amino-acid sequences. This ability might allow us to design proteins to serve any cellular function imaginable; as long as we know what sequence leads to a certain structure, we can use genetic engineering to create it. Deep learning and AI are helping us get there - they’re especially good at guessing a protein’s 3D shape in situations where the folding of similar proteins is already known and can serve as “training data.” AI is faster and less expensive than more traditional lab techniques, and researchers at Google are leading the effort. They placed first in 2018’s “CASP” competition to predict protein structures using computer programs.

Their “AlphaFold” algorithm, like many others, uses a neural network and considerable training data. It compares a protein’s sequence with similar, known proteins to see which amino acids tend to be near each other, then predicts the distances and angles between certain amino acids in the protein, even though they might not be physically possible. Then, it uses a second step that creates a random folding arrangement which is possible. Finally, it uses an optimization algorithm to modify that arrangement in small steps until it’s as close as possible to the first prediction. 

Thanks to data science methods, efforts to predict protein folding may allow us to finally treat or cure illnesses that could never be addressed in other ways. The possibilities extend beyond medicine as well - for example, we’ve started engineering plastic-eating bacteria to combat pollution. 

***
<br />
<br />


<div align="center">Works Cited

<br />
<br />

“AlphaFold: Using AI for Scientific Discovery.” Deepmind, Google, 15 Jan. 2020, deepmind.com/blog/article/AlphaFold-Using-AI-for-scientific-discovery.
Halton, Mary. “Recycling Hope for Plastic-Hungry Enzyme.” BBC News, BBC, 16 Apr. 2018, www.bbc.com/news/science-environment-43783631.
Hutson, Matthew. “AI Protein-Folding Algorithms Solve Structures Faster than Ever.” Nature News, Nature Publishing Group, 22 July 2019, www.nature.com/articles/d41586-019-01357-6. 
