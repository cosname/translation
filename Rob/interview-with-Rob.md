An interview with Rob J. Hyndman
--------------------------------

*[Rob J. Hyndman](http://robjhyndman.com/) is Professor of Statistics at 
[Monash University](http://www.monash.edu/), Australia and Editor-in-Chief of the
International Journal of Forecasting. He is also the author of several widely
used R packages such as `forecast` and `hts` on time series forecasts.*

**Earo**: Your bachelor degree is a science honours degree. So why did you choose
Statistics as your major and what did statistics interest you most at that moment?

**Rob**: When I first did my science degree, I wasn't thinking of statistics and
I was planning to do mathematics. At that time, majoring in any mathematical discipline at 
Melbourne University required first year students to do Statistics, Mathematics and 
Computer Science. So I ended up doing Statistics since I had to. But I found it
interesting, because I love the idea that I can solve practical problems using
mathematical tools. 

At the end of my first-year, I got a summer vacation debugging 
code for the  [Statistical Consulting Centre](http://www.scc.ms.unimelb.edu.au/) 
at Melbourne University. After I had found the bugs, I tried to get a time to talk
to my boss about what I had done, but he was always busy. I knew he had to write a report
for the client, so I eventually just wrote the report myself and left in on my boss's desk.
Later he called to me to say "I think we should employ you permanently". By the end of that 
summer, I decided to major in Statistics. The following year, when I was a second-year student,
I spoke at an academic conference on one of my consulting projects, because the client wanted me 
to talk about one of the jobs that I had done. I was pretty involved in the consulting
work there and I did enjoy it. That's why I became a Statistician.

**Earo**: Since you've been an academic for more than two decades, has the current
structure of Statistics remained the same as that of those years when you were
an undergraduate?

**Rob**: The undergraduate courses are quite similar. Maybe it should change more. (*But how?*) 
For a start, I think more computing should be put into statistics training, especially
with data sets becoming much larger and more complicated. It will change, of course,
but universities are very slow to update at the undergraduate level, especially the first
couple of years. On the other hand, higher level courses are updated all the time in any good university. 

**Earo**: You've mentioned we have to accept more computing training due to
the big data era. So how do you define the big data and how do you think the
relationship between data science and statistics?

**Rob**: I'll grab the definition from someone else: If the problems take longer
to compute than to set up the model mathematically, then it is a big data
problem. The hard work of most statistical analysis is to define the model
rather than to do the computation, since the computer is quick. But if it is the
other way around, it's definitely a large dataset. The other definition of 
the big data is when the data cannot fit into the memory of your computer. How does data science 
relate to statistics? I think statistics is a subset of data science. Data 
science is a bigger topic including data management and data storage etc.; 
whereas statistics is mostly about the randomisation of the dataset and how 
to analyse it and how to report. But the actual management of large datasets
is an important area of data science, but is often ignored in statistics. 
Many people think that data science is a sexy word for statistics. But I tend 
to think it is a bit more than that.

**Earo**: Because of the feature of data science, there are so many computer
scientists getting involved in field of data science. What advantages does a Statistician
have over a Computer Scientist?

**Rob**: The big advantage is understanding stochastic modelling. Most computer
scientists don't have any real training in stochastic models, and they often 
don't understand some concepts like uncertainty and how you handle noisy data.
In data science problems, a common task is to extract information 
out of noisy data, and statisticians have a big advantage there. Another issue
is quantifying uncertainty. Typically, in prediction problems, Data Scientists 
don't produce prediction intervals and just produce the point forecasts. 
But there's uncertainty associated with the forecasts, and you can quantify if you have stochastic 
components in the process. That's a whole way of thinking which has been in 
Statistics for more than a hundred years. Many Computer Scientists getting into 
data science don't know that way of thinking about uncertainty. On the other hand, they are good at 
other aspects, such as algorithm design and efficient computation. I think Computer 
Scientists and Statisticians can work very well together because they bring slightly 
different perspectives to a problem. Ultimately, I expect the distinction between 
data scientist and statistician will disappear, but that's a few years away.

**Earo**: The `forecast` package has been one of the most widely used ones at R
CRAN. So can you please talk about the reason why you developed `forecast` package?

**Rob**: The first reason is I had some sets of functions that I used for consulting. 
I thought it's neat to have those in a package and a lot of people don't have access 
to good tools or they don't know how to find good tools. I figured that I could make my
forecast functions available for other people and that would be useful. The other 
reason was that I have developed a lot of new forecasting methods. I want people
to use them, and the only way that people are going to use them is to give them software. 
Thirty years ago, if you wrote a paper on a new method or model and someone was interested in applying it, 
they had to code it up themselves. There was no culture of sharing code. But that changed. If you are 
serious about developing new statistical models or methods, then you have to provide R packages to make
it easy for other people to implement your ideas.

**Earo**: You not only develop R packages that are available on the web, you are
also a blogger and an active member at [Cross Validated](http://stats.stackexchange.com/) . 
Now you are a co-founder of [OTexts](https://www.otexts.org/) that offers online 
and open-access textbooks. From my point of view, you're quite involved in the 
online statistical community. What's your motivation to contribute your hard work 
and time for free?

**Rob**: I figure I get paid by the university (and indirectly by the Australian government)
to develop new ideas in statistics. It makes sense for me to give my work back to the community. 
I can't see the point in locking it up in journals. If you want to make a difference, 
you have to make it available. It's much better way to do statistical 
research in the open and encourage open conversation. I think the discipline 
will advance faster and the information will be more widely available that way. 
My salary is paid so I don't have to think about making money out of the work I do. 
I don't really understand why some academics will not work openly.
It's different if you are working in private industry and having to make
a living through your research; but I don't have to do that. 

Why do I blog? Because I want to influence the way people think and I figure 
writing things down on a blog actually helps do that. I also blog because I
find myself answering the same questions from my students and others. I hate
doing the same thing over again, so I just stick my answers on my website
and people can read them there. If I see repeated questions, I'll write a post. 
At least, it helps me answer questions more efficiently. I 
also blog because it's a good advertisement for my own research and I 
want my research to be used. For example, I might write a blog post discussing 
the problem of multiple seasonality in forecasting, and explaining that the problem
is handled by a method implemented in my `forecast` package. Nobody in business 
will read the academic paper where I develop the theory, but they might do a 
web search and find an example on my website and use it. And then my work gets used more and
that's a good thing. I don't want to write a paper that gets published but never
gets used. So there are a few reasons why I do the blogging. 

Cross validated als began because I receive lots of questions about statistics generally
and I thought that it would be nice if there was a website where such questions
could be answered. A lot of people are doing statistics with insufficient training
to really understand what they're doing. If they could get some support from an
online community that would be good. I was also aware of the [stackoverflow](http://stackoverflow.com/) community
for programmers where you can ask programming questions and get amazingly good answers
really fast. I use it occasionally myself when I have programming questions, usually
about R but sometimes about regular expressions that I am trying to use. 
So I thought it would be really cool if there was a statistical version of this
site. I proposed the idea to the stackoverflow company, and I became the first administrator 
of that site, and managed to get things working well for six months. 
I'm still on it but I'm no longer an administrator.

The textbook is different. It really goes back a long way. I wrote a textbook on 
forecasting in 1998 and it became the biggest selling textbook on statistical forecasting in the world. 
My contract said I should get 5% of sales, but I actually got much less. Wiley (the publisher)
had no costs apart from printing and marketing, and they did a lousy 
job in marketing.  So I really wasn't happy. And then the book became out-of-date. I 
thought I needed to do another edition but I didn't want to do another edition with Wiley. 
However my contract said they had the rights for the next edition and I wasn't allowed 
to write a competitive book. After negotiating backwards and forwards a few times, they eventually agreed 
to release my from that contract. 

I was thinking that the reason I write a book 
is not to make money; the real reason that I write a book is because I want to 
influence the way people think and my view of forecasting hopefully influences 
other people to do forecasting well. You write a textbook because you want to change the world; not because you 
want to make money. It appears that most students don't want to spend money on
textbooks since they are often only used for one semester. Either the students get hold of a second-hand 
copy, which is often out-of-date, or they just look on the web to try to find some 
other resource instead of using a book. There are few good-quality textbooks on the 
web, and what is there is often incorrect or incomplete. So I thought I would write
an online book. I didn't care about making money, everyone would have access 
to it, and I wouldn't have to worry about whether people could afford it. So I wrote
an online book and it quickly became very widly used. As I put chapters online, they 
started receiving a lot of traffic. People like online things as long as they are 
good quality by reputable people. So then I set up the OTexts platform to see if we can encourage 
other academics to write online books. We do have some plans to make money as well. But
we haven't yet started monetizing it. The books will always be free as that is an important
underlying philosophy of OTexts.

**Earo**: You are a statistical consultant in public or private sectors. How does
the consulting work relate to your research and teaching?

**Rob**: My research and consulting are quite closely related and they feed on
each other. A company will come to me with a problem that they can't solve.
If the problem has an existing solution, I generally won't do it. I'm not 
interested in doing routine consulting work applying existing solutions. 
But if it sounds hard and there's no obvious way to do it using existing methods, 
I'll usually take it on, because it's an interesting problem and it might
lead to publishable research. The ideal consulting job will lead to papers. 
Even it isn't directly to 
papers, consulting helps me to stay aware of what are the real problems in business 
and in industry and that guides what research problems I take on. 

To give you an example, years ago a company asked me to help solve a forecasting
problem that involved the monthly sales of thousands of different products. They wanted to forecast 
the individual sales of each product, as well as the grouped sales by retail outlet or by product type.
I helped them to 
solve the problem but all the time I was thinking there's is a theoretical 
problem here about how to forecast hierarchical time series in an efficient way.
About ten years after I first encountered this problem in consulting, I wrote my first paper on 
hierarchical time series modeling. And I am still working on hierarchical forecasting issues and methods.
I find that I'm using the consulting problems to motivate what I might do research on. 

It also works the other way as well. A company will come along with a problem that
I have already done some research on. Then I might take on the project so I can
see how well my research works in practice. In particular, I want to know where 
my methods do not work, because nothing works perfectly. That might guide me to other 
research problems. I don't really see my consulting as separate from my research, 
because I try to take on consulting problems that are research-like. 

Occasionally, I'll do free consulting work that is good for the country but with no real
research component. For twenty years, I've been involved with the scaling of all year 12 
marks in Victoria. The algorithm takes students' marks and scales them in a way that 
enables them to be comparable across all subjects. These rescaled scores are then used for 
selecting students to go on to university. I do this work unpaid because I think it's important. 
I'm also an advisor to the Australian Bureau of Statistics. I advise them on methodology 
they should in collecting and analysing data for the government.

My consulting is also useful in teaching, because it gives me stories to tell and students usually like to
hear about things I've done. It's nice when everything works together -- research, consulting and teaching.

![rob](https://dl.dropboxusercontent.com/u/7131169/earo.me/rob.JPG)
