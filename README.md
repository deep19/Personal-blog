# What is the true utility of a memory system like Anki for conceptual understanding

Memory systems like flashcards can be used not just for memorizing facts and study aspects of  subjects like a new language or medicine or chemistry where you need to remember a lot of facts, but deeper conceptual ideas as well. An example of this process: [https://cognitivemedium.com/srs-mathematics](https://cognitivemedium.com/srs-mathematics)

There are 3 major aspects here:
1. Long term retention
2. Forcing you to form good questions which helps build a deeper relationship with the subject (one of the reasons why sharing decks or using someone else's deck is not useful)
3. Internalised understanding leads to flow state which is not possible if you have to disrupt yourself to look for the information in an external system

Long term retention also gives you the additional drive that helps foster motivation which is an important element in learning. If I know I won't remember much of the subject as it's not something I use day-to-day, I'm less likely to have the drive to start it. Having the confidence that it'll be retained in long term memory can be crucial. 
Systems like Anki have a small detail which make them much more efficient than traditional flashcards -- they use a schedule based on how difficult or easy is it for you to remember the fact or idea. This itself causes an efficiency of the system reducing life long retention time of a fact or idea from 2 hours per card to 6-7 minutes per card. If an idea seems important enough to spend 10 mins cumulative of your life, you can out it into Anki.

Condensing knowledge into bite sized blocks can help develop a new outlook towards the subject. Having multiple pieces of the whole retained in memory can help you see the combined picture in important ways much more conducive to learning than conventional reading. The atomic knowledge blocks can be combined in unexpected ways again fostering deeper understanding. This is the core of the process and has a high learning curve.
To quote Nielsen:
>*Anki skills concretely instantiate your theory of how you understand; developing those skills will help you understand better

Internalized understanding enables speed in associative thought, an ability to rapidly try out many combinations of ideas, and to intuit patterns, in ways not possible if you need to keep laboriously looking up information. 
Basically memory can really help you to be in flow state while pursuing your creative task at hand. The task can be cooking, music, programming -- anything. By memory I mean internalised understanding of the elements of your task. For cooking, it'd be an internalised understanding of the recipe and the ingredients used. For programming, it can be the library API that's being used intensively in your project. For music, it can be the scale of your musical piece. Again, it's not just about memorising these elements but having a deeper understanding of it which is retained in the long term memory. That's one of the arguments of the utility of such memory systems even when this information can be put in some notebook and retrieved easily --  it'll disrupt the flow state. Having an internalised understanding of these elements will help you achieve and maintain the flow state.


# Michael Nielsen - Augmenting long term memory

 Reference: [https://augmentingcognition.com/ltm.html](https://augmentingcognition.com/ltm.html)

## Using Anki to thoroughly read a research paper in an unfamiliar field

>*What made Anki finally “take” for me, turning it into a habit, was a project I took on as a joke. I'd been frustrated for years at never really learning the Unix command line. I'd only ever learned the most basic commands. Learning the command line is a superpower for people who program, so it seemed highly desirable to know well. So, for fun, I wondered if it might be possible to use Anki to essentially completely memorize a (short) book about the Unix command line.*

Use a personal project to learn a new tool. Don't start working on the tool unless you have a project you're really interested in where the tool would be helpful

>*It's tempting instead to use Anki to stockpile knowledge against some future day, to think “Oh, I should learn about the geography of Africa, or learn about World War II, or […]”. These are goals which, for me, are intellectually appealing, but which I'm not emotionally invested in. I've tried this a bunch of times. It tends to generate cold and lifeless Anki questions, questions which I find hard to connect to upon later review, and where it's difficult to really, deeply internalize the answers. The problem is somehow in that initial idea I “should” learn about these things: intellectually, it seems like a good idea, but I've little emotional commitment.*

The project should have an *emotional* value for you and not just intellectual value where you feel you "should" be doing it

## Using Anki to do shallow reads of papers

>*Really good resources are worth investing time in. But most papers don't fit this pattern, and you quickly saturate. If you feel you could easily find something more rewarding to read, switch over. It's worth deliberately practicing such switches, to avoid building a counter-productive habit of completionism in your reading. It's nearly always possible to read deeper into a paper, but that doesn't mean you can't easily be getting more value elsewhere. It's a failure mode to spend too long reading unimportant papers.*

Important to make sure you're cultivating the taste as to what's really important 


>*As mentioned above, I'm usually doing such reading as part of the background research for some project. I will find a new article (or set of articles), and typically spend a few minutes assessing it. Does the article seem likely to contain substantial insight or provocation relevant to my project – new questions, new ideas, new methods, new results? If so, I'll have a read.
> 
> This doesn't mean reading every word in the paper. Rather, I'll add to Anki questions about the core claims, core questions, and core ideas of the paper. It's particularly helpful to extract Anki questions from the abstract, introduction, conclusion, figures, and figure captions. Typically I will extract anywhere from 5 to 20 Anki questions from the paper. It's usually a bad idea to extract fewer than 5 questions – doing so tends to leave the paper as a kind of isolated orphan in my memory. Later I find it difficult to feel much connection to those questions. Put another way: if a paper is so uninteresting that it's not possible to add 5 good questions about it, it's usually better to add no questions at all.

Just go through abstract, conclusions, some basic figures and try to extract a dozen or so questions in anki -- perhaps this approach can be used in not just research papers but articles as well? Like this article? Experiment!

## Syntopic reading using Anki

>*In fact, to really grok an unfamiliar field, you need to engage deeply with key papers – papers like the AlphaGo paper. What you get from deep engagement with important papers is more significant than any single fact or technique: you get a sense for what a powerful result in the field looks like*

**Syntopic reading** - To read up broadly about an entirely new field
Engage in most important key papers to get an idea of the field -- quality over quantity here
You get a sense of how the important techniques in the field are applied to an important problem
You see the important questions, the current limitations

>*Such things aren't captured individually by any single Anki question. But they begin to be captured collectively by the questions one asks when engaged deeply enough with key papers

Important point -- for broader things, you might need to have a more holistic view of the questions and see how the combination paints the broader picture -- does it mean I need to order my cards in a certain way? Do I need hierarchy?

>*Without a lot of drive, it was extremely difficult to make a lot of material in a new field stick. Anki does much to solve that problem. In a sense, it's an emotional prosthetic, actually helping create the drive I need to achieve understanding.*

Important ways in which seemingly simple tool can help is create that drive -- adding that additional little motivation required for the little push -- [[Wozniak - Formula for healthy self discipline]]

## More patterns of Anki use

>***Make most Anki questions and answers as atomic as possible:** That is, both the question and answer express just one idea. As an example, when I was learning the Unix command line, I entered the question: “How to create a soft link from `linkname` to `filename`?” The answer was: “`ln -s filename linkname`”. Unfortunately, I routinely got this question wrong.
> 
> The solution was to refactor the question by breaking it into two pieces. One piece was: “What's the basic command and option to create a Unix soft link?” Answer: “`ln -s …`”. And the second piece was: “When creating a Unix soft link, in what order do `linkname` and `filename` go?” Answer: “`filename linkname`”.

An example to see how to make things atomic. Another thing to note is the feedback mechanism used here. Pay attention to answers that you get wrong and delve deep into that and see what improvement can be made in those cases


>*Note that this doesn't mean you shouldn't also retain some version of the original question. I still want to know how to create a soft link in Unix, and so it's worth keeping the original question in Anki. But it becomes an integrative question, part of a hierarchy of questions building up from simple atomic facts to more complex ideas*

Explore what an "integrative" question is. And how to build hierarchies in anki?

>*But one real benefit is that later I often find those atomic ideas can be put together in ways I didn't initially anticipate. And that's well worth the trouble*

One more point in answering [[What is the true utility of a memory system like Anki for conceptual understanding]]

>*My questions about AlphaGo began with simple questions such as “How large is a Go board?”, and ended with high-level conceptual questions about the design of the AlphaGo systems – on subjects such as how AlphaGo avoided over-generalizing from training data, the limitations of convolutional neural networks, and so on.*

Examples of questions used for a deeper subject matter.

>*Part of developing Anki as a virtuoso skill is cultivating the ability to use it for types of understanding beyond basic facts. Indeed, many of the observations I've made (and will make, below) about how to use Anki are really about what it means to understand something. Break things up into atomic facts. Build rich hierarchies of interconnections and integrative questions. Don't put in orphan questions. Patterns for how to engage with reading material. Patterns (and anti-patterns) for question types. Patterns for the kinds of things you'd like to memorize. Anki skills concretely instantiate your theory of how you understand; developing those skills will help you understand better. It's too strong to say that to be a virtuoso Anki user is to be a virtuoso in understanding. But there's some truth to it.

What does it mean to understand something for you? -- experiment with anki and see!
"instantiates your theory of how you understand things"


>***Use one big deck:** Anki allows you to organize cards into decks and subdecks. Some people use this to create a complicated organizational structure. I used to do this, but I've gradually** It's gradual because questions sometimes need to be rewritten due to the changed context. For instance, both my Emacs and Unix command line decks had very similar questions, along the lines of: “How to delete a word?” Those questions need to be rewritten, e.g. as: “In Emacs, how to delete a word?” (This, by the way, may seem a strange question for a long-time Emacs user such as myself. In fact, I've used Anki to help me change the way I delete words in Emacs, which is why I have an Anki question on the subject. I have made many improvements to my Emacs workflow this way.) merged my decks and subdecks into one big deck. The world isn't divided up into neatly separated components, and I believe it's good to collide very different types of questions. One moment Anki is asking me a question about the temperature chicken should be cooked to. The next: a question about the JavaScript API. Is this mixing doing me any real good? I'm not sure. I have not, as yet, found any reason to use JavaScript to control the cooking of a chicken. But I don't think this mixing does any harm, and hope it is creatively stimulating, and helps me apply my knowledge in unusual contexts.

Similar to how zettelkasten recommends no structure to synthesised notes. Connections can come from anywhere. categorization is artificial. Knowledge doesn't have defined boundaries
But need to take into account context now with each question -- a tradeoff

>*I call these _orphan questions_, because they're not closely related to anything else in my memory. It's not bad to have a few orphan questions in Anki – it can be difficult to know what will turn out to be of only passing interest, and what will grow into a substantial interest, connected to my other interests. But if a substantial minority of your questions are orphans, that's a sign you should concentrate more on Ankifying questions related to your main creative projects, and cut down on Ankifying tangential material

Orphan questions can become boring with time -- you'd want to avoid having too. many of such questions -- how do you even say that these are not related to anything else? Once say you have 1000s of cards? Do you maintain any related links in anki?

>*For instance, it's possible to try to remember as an isolated fact that 1962 was the year the first telecommunications satellite, Telstar, was put into orbit. But a better way of remembering it is to relate that fact to others. Relatively prosaically, you might observe that Telstar was launched just 5 years after the first Soviet satellite, Sputnik. It didn't take long to put space to use for telecommunications. Less prosaically – a richer elaboration – I personally find it fascinating that Telstar was put into orbit the year _before_ the introduction of ASCII, arguably the first modern digital standard for communicating text. Humanity had a telecommunications satellite before we had a digital standard for communicating text! Finding that kind of connection is an example of an elaborative encoding.

Example of how to make simple facts more fascinating -- discuss with yadav

>*The act of constructing an Anki card is itself nearly always a form of elaborative encoding. It forces you to think through alternate forms of the question, to consider the best possible answers, and so on. I believe this is true for even the most elementary cards. And it certainly becomes true if you construct more complex cards, cards relating the basic fact to be remembered to other ideas (like the Telstar-ASCII link), gradually building up a web of richly interrelated ideas

How do i form the interconnections in anki? Same question as asked some points above

>*there is great value in learning to “think in more memorable ways”

interesting quote


>*Why not use more of Anki's features? Part of the reason is that I get an enormous benefit from just the core features. Furthermore, learning to use this tiny set of features well has required a lot of work. A basketball and hoop are simple pieces of equipment, but you can spend a lifetime learning to use them well. Similarly, basic Anki practice can be developed enormously. And so I've concentrated on learning to use those basic features well.
> 
> I know many people who try Anki out, and then go down a rabbit hole learning as many features as possible so they can use it “efficiently”. Usually, they're chasing 1% improvements. Often, those people ultimately give up Anki as “too difficult”, which is often a synonym for “I got nervous I wasn't using it perfectly”. This is a pity. As discussed earlier, Anki offers something like a 20-fold improvement over (say) ordinary flashcards. And so they're giving up a 2,000% improvement because they were worried they were missing a few final 5%, 1% and (in many cases) 0.1% improvements. This kind of rabbit hole seems to be especially attractive to programmers.

Important to note for other tools in use as well. Like obsidian for eg. Been thinking about this tangent lately. Identify the really core things the tool can help you with. Do you even actually have any use for the tool? Don't jump on it because it seems 'cool'. Have a real purpose and that's when the tool will truly shine. Focus on mastering the fundamentals of the tool which get you the max benefit for your endeavour. Then see the gaps and incrementally fill them with time but those things can wait. Right now for obsidian I'm just noting down the gaps. Will see the solutions later on. Much more meaningful this way than exploring all the cool plugins and retrofitting the use for them. [[Don't retrofit stuff!]] 
It's okay to start with slight inefficiency and gradually improve on it (if there are major inefficiencies fix them upfront) 

>*to really internalize a process, it's not enough just to review Anki cards. You need to carry out the process, in context. And you need to solve real problems with it.

Read -> internalize (using anki or similar memory system) -> create/solve problems with the internalized knowledge. Don't forget the 3rd step

>*This trope that names don't matter was repeatedly drilled into me during my scientific training. When I began using Anki, at first I felt somewhat silly putting questions about names for things into the system. But now I do it enthusiastically, knowing that it's an early step along the way to understanding.

Names do matter. Helps sort of "tagging" it in the brain. Give it a "home" I guess? -- maybe more to be thought on this -- Related to how notation change can bring about a difference in understanding? De bruijn nottation, bilinear forms in halmos book also talks about slight change in notation making the idea really shine -- viewpoint does matter

>*I'm more haphazard about videos, events, and places. It'd be good to, say, systematically Ankify 3-5 questions after going on an outing or to a new restaurant, to help me remember the experience. I do this sometimes. But I haven't been that systematic.

Kind of a personal journal to remember stuff. About intense emotional experience. About any piece of music or art you like. A moment in the day that captured your attention. Would be good to "seal" it into the memory and ponder on it. Experiment!

>*I tend to Ankify in real time as I read papers and books. For seminars, conversations, and so on I prefer to immerse myself in the experience. Instead of getting out Anki, I will quickly make a mental (or paper) note of what I want to Ankify. I then enter it into Anki later. This requires some discipline; it's one reason I prefer to set a small quota, so that I merely have to enter a few questions later, rather than dozens.
> 
> One caution is with books: reading an entire book is a big commitment, and adding Anki questions regularly can slow you down a lot. It's worth keeping this in mind when deciding how much to Ankify. Sometimes a book is so dense with great material that it's worth taking the time to add lots of questions. But unmindfully Ankifying everything in sight is a bad habit, one I've occasionally fallen into.

Good idea to set limits on how much to ankify. You need to tread the balance between "immersing" in the experience vs trying to ankify. Sort of like watching a concert vs trying to take video or when witnessing something exceptional, trying to capture it rather than live it. Need to draw some boundaries there

>*fluid access to memory is at the foundation of so much creative thought.

>*In practice, I find myself instinctively and unsystematically doing some things as notes, others as Anki questions, and still other things as both. Overall, it works okay, but my sense is that it could be a lot better if I applied more systematic thought and experimentation. Part of the problem is that I don't have a very good system for note taking, period! If I worked more on that, I suspect the whole thing would get a lot better. Still, it works okay.

Something I've been thinking about as well. Experiment and see I guess!
