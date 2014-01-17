An interview with Rob J. Hyndman
--------------------------------

*[Rob J. Hyndman](http://robjhyndman.com/) is Professor of Statistics at 
[Monash University](http://www.monash.edu/), Australia and Editor-in-Chief of the
International Journal of Forecasting. He is also the author of several widely
used R packages such as `forecast` and `hts` on time series forecasts.*

**Earo**: Your bachelor degree is a science honours degree. So why did you choose
Statistics as your major and what did statistics interest you most at that moment?

**Rob**: When I first did my science degree, I wasn't thinking of statistics and
I was planning to do pure maths. Majoring in any mathematical discipline at 
Melbourne University requires freshmen to do Statistics, Mathematics and 
Computer science. So I ended up doing Statistics since I had to. But I find it
interesting, because I love the idea that I can solve practical problems using
mathematical tools. 

My first statistical job in the first-year summer vacation was debugging 
code for the  [Statistical Consulting Centre](http://www.scc.ms.unimelb.edu.au/) 
at Melbourne University. I found bugs after a while but I knew they had to write
a report for a client. Then I kept trying to see the client and told him what I
found and where the problems were. He was really busy and said to me "Come back
tomorrow." After two days, I found myself silly, because I knew how to write a
report for a client and I even knew how to say since it's based on what I'd done.
I wrote the report and left it on his desk. Later, he called to me "I
think we should employ you full-time.". By the end of that summer, I decided to major
in Statistics. Also I spoke at a conference when I was a second-year student, because
the client wanted me to talk about one of the jobs that I've done at the consulting
group, which was quite crazy experience. I was pretty involved in the consulting
work there and I did enjoy it. That's why I became a Statistician.

**Earo**: Since you've been an academic for more than two decades, has the current
structure of Statistics remained the same as that of those years when you were
an undergraduate?

**Rob**: That's pretty similar. Maybe it should change more. (*But how?*) They
need more computing putting into the statistics training, I think. We'll change,
but university is really slow. On the other hand, the course part is always updated
with new materials in any good university. The stuff that I was taught is a little
bit different from what would be now, because new things are being put to the 
course based on new techniques.

**Earo**: You've mentioned we have to accept more computing training due to
the big data era. So how do you define the big data and how do you think the
relationship between data science and statistics?

**Rob**: I grab the definition from someone else. If the problems take longer
to compute than to set up the model mathematically. That's probably the data
problem. The hard work of most statistical analysis is to define the model
rather than to do the computation, since the computer is quick. But if there's the
other way around, it's definitely a large dataset. The other definition of 
the big data is the data cannot fit into the memory. How does data science 
relate to statistics? I think statistics is a subset of data science. Data 
science is a bigger topic including data management and data storage etc.; 
whereas statistics is mostly about the randomisation of the dataset and how 
to analyse it and how to report. But the actual management of large datasets
is the whole area of data science. Most people think that data science is a sexy
word of statistics. But I tend to think a bit more than that.

**Earo**: Because of the feature of data science, there are so many computer
scientists getting involved in field of data science. What advantages does a Statistician
have over a Computer Scientist?

**Rob**: The big advantage is understanding the stochastic modelling. Most computer
science people don't have any real training or they don't know some concepts like
uncertainty and how you form a decision based on the data when there's lots of 
noise in the data. What they really want Statisticians to do is to extract information 
out of noisy data. That's really a big advantage there. Typically, Data Scientists 
often don't produce the prediction interval and just produce the point forecasts. 
But there's uncertainty around it and you can quantify if you have stochastic 
components into the process. That's the whole way of thinking, which has been in 
Statistics for more than a hundred years. Many Computer Scientists getting into 
data science don't know the way of thinking. On the other hand, they are good at 
other aspects, such as algorithm design and efficient computation. I think Computer 
Scientists and Statisticians can work very well together. Because they bring slightly 
different perspectives to a problem. 

**Earo**: The `forecast` package has been one of the most widely used ones at R
CRAN. So can you please talk about the reason why you developed `forecast` package?

**Rob**: The first reason is I had some sets of functions that I used for consulting. 
I thought it's neat to have those in a package and a lot of people don't have access 
to good tools or they don't know how to find good tools. I figured that I could make my
forecast functions available for other people. So that would be useful. The other 
reason was I developed a lot of new methodologies in forecasting. I want people
to use it and the only way that people are going to use it is to give them a software. 
30 years ago, you wrote a paper on new methodology and if someone was interested, 
they had to code themselves. You didn't code it out. But that changed. If you are 
serious to produce new methodology, you have to provide. 

**Earo**: You not only develop R packages that are available on the web, you are
also a blogger and an active member at [Cross Validated](http://stats.stackexchange.com/) . 
Now you are a co-founder of [OTexts](https://www.otexts.org/) that offers online 
and open-access textbooks. From my point of view, you're quite involved in the 
online statistical community. What's your motivation to contribute your hard work 
and time for free?

**Rob**: I figure I get paid by the university and essentially by Australia government
to develop new ideas of statistics. It makes sense for me to give that to the community. 
I can't see the point in locking it up in journals. If you want to make a difference, 
you have to make it available. It's just a much better way of doing statistical 
research in the open and encouraging open conversation. I think the discipline 
will advance faster and the information will be more widely available. My salary 
is paid and I don't have to think about making money out of the work I really do. 
I don't really understand why some academics will not do it openly even they've 
already got the salary. It's different that you are working in a private industry 
and try to live through your research; but I don't have to do that. 

Why do I blog? Because I want to influence the way people think and I figure 
writing things down on a blog that actually helps do that. I blog because I
find myself answer the same questions from my undergraduates and sometimes from
other people a lot by email. It's just silly doing the same thing and I just stick 
it to the website and people can read there. But if I see repeated questions, 
I'll write a post. At least, it will help somebody to save these questions. I 
also partly blog, because it's a good advertisement for my own research and I 
want my research to be used. If I write a blog post saying you might have some 
problems like multiple seasonality in forecasting and you could use my method 
implemented in my `forecast` package. Nobody will read the forecast academic 
literatures if they are working in business, but they might do a web search and 
find an example on my website and use it. And then my work gets used more and
it's a good thing. I don't want to write a paper that gets published but never
gets used. So there are a couple of reasons why I do the blogging. 

Cross validated, originally was because again I got lots of questions and I thought 
I can directly go to the site that questions could be answered. That would be really 
useful. I was also aware that there are a lot of people doing statistics but they 
don't have enough training to know what they're doing. At least, they can get support 
from some community. That would be good. I was also aware of the [stackoverflow](http://stackoverflow.com/) community
for programmers where you can ask programming questions and get amazingly good answers
in really fast time. I use it occasionally for myself when I have questions usually
about R but sometimes about regular expressions that I try to do but am not sure
how to do. So I thought it's really cool if there's a statistical version of this
site. When I talked to the stackoverflow company about the idea, they immediately 
said yes and I became the first administrator of that site, and managed to get 
things working well for six months. I'm still on it but I'm no longer an administrator.
So that's motivation for that. 

The textbook is different. It really goes a long way. I wrote a textbook on 
forecasting in 1998. That was the biggest selling forecasting textbook in the world. 
They sold it at about 140 dollars. My contract said I should get 5%, but I actually 
got less. They had no cost apart from printing and marketing. They did a lousy 
job in marketing. I would go to a forecasting conference and they wouldn't know 
this book. So I wasn't really happy. And then the book became out-of-date. I 
think I need another edition but I don't want to do another edition with Wiley. 
However my contract said they had rights for the next edition and I wasn't allowed 
to write a competitive book. After negotiating a few times, they eventually agreed 
to release my from that contract. I was thinking that the reason I write a book 
is not to make money; the real reason that I write a book is because I want to 
influence the way people think and my view of forecasting hopefully influences 
other people to do forecasting. I think I've got some good ideas that would help. 
You really want to do it, because you want to change the world; not because you 
want to make money. It appears that  most students don't want to spend that money on
textbook since it's only used for one semester. Either they've got a second-hand 
copy, which was out-of-date; or they just look at the web to try to find some 
other resource instead of using a book. There's no good-quality textbook on the 
web, which is usually incorrect or incomplete. So what I want to do is just write 
an online book. I don't care about making the money and everyone will have access 
to it. I wouldn't have to worry about whether people can afford it. Then I write 
an online book and it quickly became very wildly used. I started to put chapters 
up early and there are several traffics on it. This really works. People like 
the online things as long as it's good quality by reputable people and then it 
should be better than a print book. I set up a platform and see we can encourage 
academics to write books on it. We do have some plans to make money as well. But
we haven't yet started monetizing it. The books will always be free and it's
a philosophy of it.

**Earo**: You are a statistical consultant in public or private sectors. How does
the consulting work relate to your research and teaching?

**Rob**: Research and consulting are quite closely related and they feed up
to each other. A company will come to me with a problem that they can't solve.
If the problem has its own solution, I generally won't do it. Because I'm not 
interested in doing routine's consulting work with official solution that exists. 
But if it sounds hard and there's no obvious way to do it using existing methods 
and I'll usually take that on, because it's an interesting problem. What I'm 
always thinking is whether there's a way I can come up with a solution to make it 
publishable. This is why I take those hard ones and I'm looking for publishable 
solutions. The ideal consulting job will lead to papers. Even it isn't directly to 
papers but it helps me to stay aware of what are the real problems in business 
and in industry and that guides what research problems that I take on. Just give 
you an example, years ago, a company had thousands of different products and they 
wanted to forecast grouped time series by retail or by stock. I helped them to 
solve the problem but all the time I'm thinking there's going be a theoretical 
problem here that's how to forecast hierarchical time series in an efficient way.
So eventually after ten years I saw the first of this, I wrote my first paper on 
hierarchical time series modeling. I find that I'm using the consulting problems 
to motivate what I might do research on. There's quite movement in the direction 
from consulting problems to my research. I guess there's the other way as well. 
A company will come along and say they've got this problem and I maybe have done 
some research on it. I can see how to apply my research and I might take it on 
to make sure the research actually works well in practice or I want to see where 
it doesn't work, because nothing works perfectly. That might guide me to other 
research problems. I don't really see my consulting is separate from my research, 
because I try to take on consulting problems that are research-like. 

Occasionally, I'll do consulting work that is good for the country. For twenty years, 
I've done all the scaling of year 12 marks in Victoria. The algorithm takes
students' marks and scales them in a way that enables them to be comparable across some
subjects. They use these rescaled scores as university entrances. I'm the main
person that has done that work for last twenty years. Every student's scores gets 
scaled by my algorithm and so they can get into university. I do that, because I 
think it's important. I didn't invent the algorithm but I did lots of modifications
on it. The research has already been published by someone else but I do it because 
I don't want students' marks getting stuff wrong. I'm also an advisor of Australia
Bureau of Statistics. I advise them on methodology they should analyse for the government. 

My consulting is useful in teaching, because it gives me stories and students usually like to
hear about things I've done. That's sort of things working together.

![rob](https://dl.dropboxusercontent.com/u/7131169/earo.me/rob.JPG)
