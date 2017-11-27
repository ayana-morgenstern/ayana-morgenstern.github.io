## Reading: *How Not To Read A Million Books*

About what not to read. 

About casting a wider net, using text-mining to:
 1. identify word boundaries, sentence boundaries, standard spellings, parts of speech and lemmata.
 2. find patterns in a single work, in a subset of the MONK collection, or across everything we have.
 ... Example:
 1. With Gertrude Stein's novel it:  applied “a frequent pattern analysis algorithm” that looked at every sequence of 
 three words in the book, and any patterns across those trigrams, but “executing the algorithm on 
 *Making* generated thousands of patterns since each slight variation in a repetition generated a new pattern."
 2. Appearance of the devil: we can see WHEN figures appear in texts and what these patterns mean.
 
### Best Practices when Data Mining:
1. Make assumptions explicit
2. Use multiple representations and methodologies
3. Report all trials (including failures)
4. Make data available and methods reproducible
5. Engage in peer review of methodology

### General Thoughts:
- About what is absent. How texts differ from each other as much as how they are similar. 
- Skepticism: Specifically, they point out that there are some key practices and assumptions in data-mining and machine 
learning that literary users of these tools may not fully appreciate or understand, and that without an understanding 
of fundamental principles, it is easy to misinterpret or overstate the significance of statistical results:
The temptation in applying machine learning methods to humanities data is to interpret a computed result as some 
form of proof or determinate answer. In this case, the validity of the evidence lies inherent in the technology. This can 
be problematic when the methods are treated as a black box, a critic ex machina.
- Have to be careful about manipulating data: can use it to prove different things. 

## Reading: *Text Analysis, Data Mining and Visualizations* 

Going against the idea that digital applications/tools take the "human" out of literary study.

The Digital Literary Studies: 
text analysis, visualization, and data mining represent paradigmatic shifts in the work of the humanities that force scholars to reflect on the relation between information and new media and technology and that require them
“to investigate underlying database, data-flow, cross-platform data architecture”.

About using data mining/visualization to defamiliarize texts!

Differences between close and distant readings. *About using both*
* Observations about the data-mining process made by collaborators also support the supposition that it is the combination of data mining and visualization (distant reading) with the ability to read and contextualize one’s results (close reading) that generated many of the most productive studies and that is needed to address the remaining gaps and difficulties. 

### Four approaches to studying literature:
1. As rhetoric or practical criticism: “the examination of diction and syntax, rhythm and repetition, and the various figures of speech”.
2. As philosophy or the “potential expression of truth and knowledge”.
3. As art or a unique aesthetic construct—a form of discourse inherently other, of which the objective is the “pleasure of representation” and the “pleasure of recognition,” or the pleasure “of taking in impersonations, fictions, and language creations of others and recognizing their justice”.
4. As “cultural production”—“for its political role, its exposure of the state of a given society”.

Having a "wide" reading gives greater pleasure and greater ability to make connections between texts. 
Also about silences!
Using tools to facilitate differential reading practices can facilitate self-reflective or self-conscious critical practices by helping us interpret the patterns we see in texts and in how others have read texts.

### 3 Steps for Data Mining
1. determine decision criteria for classification. The decision criteria could include features of the text to be analyzed such as n-grams (n number of characters or words of text), parts of speech, or phonetic sounds and certain behaviors or relations such as words or phrases that are repeated or words or phrases that are collocated (found in proximity to one another). 
2.use the data-mining algorithm to analyze and map the behavior of or patterns created by the decision criteria in a subset of the document collection or corpora. 
3. use the data-mining algorithm to apply that mapping to new documents to find similar patterns or behaviors.

Close reading and distant reading in data-mining projects are facilitated most by “technologies of collaboration”.

Must be aware of research bias: but everything humans do is naturally biased so I don't see the big fuss with this. 

## Reading: *Using Metadata to find Paul Revere*:

Using data to find people belonging to terrorist groups. 

*Key way of following data*: 
Instead of seeing how (and which) people are linked by their shared membership in organizations, we see which organizations are linked through the people that belong to them both. People are linked through the groups they belong to. Groups are linked through the people they share. This is the “duality of persons and groups” in the title of Mr Breiger’s article.

Different ways of calculating "centrality":
“If I have to get from person a to person z, how likely is it that the quickest way is through person x?” 

From a table of membership in different groups we have gotten a picture of a kind of social network between individuals, a sense of the degree of connection between organizations, and some strong hints of who the key players are in this world. And all this—all of it!—from the merest sliver of metadata about a single modality of relationship between people. 

### General Thoughts:

Data can be dangerous: we make assumptions, can be lead down the wrong paths, and yet can also find out an incredible amount concerning *relationships* between parcels of data/people. 

Data can be useful to visualize connections between groups/people and on various scales. 

## Reading: *How To Make a Racist AI without really trying* :

About plotting out negative and positive words. Adding neutral category too for nuance --> 
* *however*: So I tried a version of this notebook where I put in 800 examples of neutral words, and put a strong weight on predicting words to be neutral. But the end results were not much different from what you're about to see.

Sentiment requires context!

Some people expect that fighting algorithmic racism is going to come with some sort of trade-off. There's no trade-off here. You can have data that's better and less racist. You can have data that's better because it's less racist. There was never anything "accurate" about the overt racism that word2vec and GloVe learned.

You could abandon the idea of inferring sentiment for words, and only count the sentiment of words that appear exactly in the list. This is perhaps the most common form of sentiment analysis -- the kind that includes no machine learning at all. Its results will be no more biased than whoever made the list. But the lack of machine learning means that this approach has low recall, and the only way to adapt it to your data set is to edit the list manually.
As a hybrid approach, you could produce a large number of inferred sentiments for words, and have a human annotator patiently look through them, making a list of exceptions whose sentiment should be set to 0. The downside of this is that it's extra work; the upside is that you take the time to actually see what your data is doing. And that's something that I think should happen more often in machine learning anyway.

### General Thoughts:
- Data/code can be changed/there is always room for improvement. 
*Example*:
There are many things we could have done better:
1. Weight words by their inverse frequency, so that words like "the" and "I" don't cause big changes in sentiment
2. Adjust the averaging so that short sentences don't end up with the most extreme sentiment values
3. Take phrases into account
4. Use a more robust word-segmentation algorithm that isn't confused by apostrophes
5. Account for negations such as "not happy"

*But all of those would require extra code and wouldn't fundamentally change the results we're about to see.*  

- I am troubled by how difficult it seems to me to see patterns/interpret the data. How do you sort through all these numbers to figure out what is significant?
- Also, I love the idea of hybrid approaches to research/data analysis. 

## Reading: *What Is Text Analysis, Really?*:

View of what literature is and how it should be analyzed does not mesh with the actual practices of contemporary literary critics. 
Technology moving past print concordances. Time and speed!
- Can use text analysis to not just look at patterns quickly, but look at patterns *around* words, search for complex words, phrases, compare vocabulary between characters, visualize texts, and so on and so forth. 

