<h1>Week 1: Defining Data Science and What Data Scientists Do</h1>


<h2>Defining Data Science</h2>

<h3>What is Data Science?</h3>

__Different Data Science definitions:__

- Data Science is a process, not an event. It is the process of using data to understand different things, to understand the world.

- Data science is when you have a model or hypothesis of a problem, and you try to validate that hypothesis or model with your data.

- Data science is the art of uncovering the insights and trends that are hiding behind data. It's when you translate data into a story and you use storytelling to generate insight. And with these insights, you can make strategic choices for a company or an institution.

- Data science is a field about processes and systems to extract data from various forms of whether it is unstructured or structured form.

- Data science is the study of data. Like biological sciences is a study of biology, physical sciences is the study of physical reactions.

<h3>The Many Paths to Data Science</h3>

Data science didn't really exist 10 to 20 years back. It's not something that we ever woke up and said, I want to be a data scientist when I grow up. If you talk to enough data scientists you will see that they come from all kinds of fields, I have a degree in Electrical Engineering in Physics, I have taught students with backgrounds from Business to Arts and they all dabble into data science at one point or the other. It can be when you are trying to solve some problem, looking into data science to apply in your field or looking to completely change your field, it doesn't matter what your background is, all you need is passion for continuous learning of new tools and patience to clean and analyze data.

<h3>Advice for New Data Scientists</h3>

My advice to an aspiring data scientist is to be __curious__, __extremely argumentative__ and __judgmental__.

_Curiosity_ is absolute must. If you're not curious, you would not know what to do with the data. _Judgmental_ because if you do not have preconceived notions about things you wouldn't know where to begin with. _Argumentative_ because if you can argue and if you can plead a case, at least you can start somewhere and then you learn from data and then you modify your assumptions and hypotheses and your data would help you learn. You might start at the wrong point, you may say that I believed this, but now with data I know this. So, this is a learning process.

The other thing that the data scientist would need is some comfort and flexibility with analytics platforms: some software, some computing platform, but that's secondary. The most important thing is curiosity and the ability to take positions. Once you have done that, once you've analyzed, then you've got some answers. And that's the last thing that a data scientist need, and that is the ability to tell a story. Once you have your analytics, once you have your tabulations, now you should be able to tell a great story from it. Because if you don't tell a great story from it, your findings will remain hidden, nobody would know. But your rise to prominence is pretty much relying on your ability to tell great stories. A starting point would be to see what is your competitive advantage. Do you want to be a data scientist in any field or a specific field? Because, let's say you want to be a data scientist and work for an IT firm, the set of skills you need will be different from someone who wants to work in the health industry. So figure out first what you're interested, and what is your competitive advantage. Your competitive advantage is not necessarily going to be your analytical skills. Your competitive advantage is your understanding of some aspect of life where you exceed beyond others in understanding that. Maybe it's film, maybe it's retail, maybe it's health, maybe it's computers. Once you've figured out where your expertise lies, then you start acquiring analytical skills. What platforms to learn and those platforms, those tools would be specific to the industry that you're interested in. And then once you have got some proficiency in the tools, the next thing would be to apply your skills to real problems, and then tell the rest of the world what you can do with it.


<h2>What Do Data Scientists Do?</h2>

<h3>Data Science Topics and Algorithms</h3>

I really enjoy regression I'd say regression was maybe one of the first concepts that I that really helped me understand data so I enjoy a regression. Let me explain regression in the simplest possible terms. If you have ever taken a cab ride you understand regression. Here's how it works. The moment you sit in a cab ride you see that there's a fixed amount you need to pay, let's say it's 2.50 if you chose to ride or get off, that is a fixed amount that you owe to the driver, so let's say you chose to ride. Then as the cab starts moving for every meter or hundred meters the fare increases by certain amount so there's a fraction there. A relationship between distance and the amount you would pay above and beyond that constant. And if you're not moving and you're stuck in traffic then every additional minute you have to pay more so as the minutes increase your fare increases as the distance increases your fare increases and while all this is happening you've already paid a base fare which is the constant. This is what regression is, regression tells you what the base fare is and what is the relationship between time and the fare you have paid and the distance you have traveled and the fare you've paid because in the absence of knowing those relationships and just knowing how much people traveled for and how much they paid, regression allows you to compute that constant that you didn't know it was 2.50 and it would compute the relationship between the fare and and the distance and the fare and the time.

<h3>What is the cloud?</h3>

Cloud is a godsend for data scientists primarily because you take your data and put it in the Cloud, put it in the central storage system. It allows you to bypass the physical limitations of the computers and the systems you're using, and it allows you to deploy the analytics and storage capacities of advanced machines that do not necessarily have to be your machine or your company's machine. Cloud allows you not just to store large amounts of data on servers somewhere in California or in Nevada, but it also allows you to deploy very advanced computing algorithms and the ability to do high performance computing using machines that are not yours. So, think of it as you have some information, you can't store it, so you send it to storage space, let's call it Cloud. And the algorithms that you need to use, you don't have them with you. But then, on the Cloud, you have those algorithms available. So, what you do is you deploy those algorithms on very large data sets and you're able to do it even though your own systems, your own machines, your own computing environment would not allow you to do so. The other thing Cloud is beautiful for is that it allows multiple entities to work with same data at the same time. So, you can be working with the same data that your colleagues in, say, Germany, and another team in India, and another team in Ghana, they are collectively working and they're able to do so because the information, and the algorithms, and the tools, and the answers, and the results, whatever they needed is available at a central place which we call Cloud.



<h1>Week 2: Data Science Topics</h1>



<h2>Big Data and Data Mining</h2>

<h3>Data Science Skills & Big Data</h3>

A definition of big data is data that is large enough and has enough volume and velocity that you cannot handle it with traditional database systems. Some statisticians think big data is something you can't fit on a thumb drive. Big data was started by Google when Google tried to figure out how to solve their page rank algorithm, there was nothing out there to store all of the web pages in the world, and there was no technology, there was no way to do this, and so they developed a new approach, which later became Hadoop.

<h3>What is Hadoop?</h3>

Traditionally in computation and processing data we would bring the data to the computer. In a big data cluster what Larry Page and Sergey Brin came up with is very simple, they took the data and they sliced it into pieces and they distributed each and they replicated each piece or triplicated each piece and they would send the pieces of these files to thousands of computers. First it was hundreds, then it was thousands and now it's tens of thousands. Then they would send the same program to all these computers in the cluster. And each computer would run the program on its little piece of the file and send the results back. The results would then be sorted and those results would then be redistributed back to another process. The first process is called a __Map__ or a mapper process and the second one was called a __Reduce__ process. Fairly simple concepts but turned out that you could do lots and lots of different kinds of computations and handle lots and lots of different kinds of problems and very, very, very large data sets.

One thing that's nice about these big data clusters is they scale linearly. You had twice as many servers and you get twice the performance and you can handle twice the amount of data. So this broke the bottleneck for all the major social media companies. Yahoo then got on board. Yahoo hired Doug Cutting who had been working on a clone or a copy of the Google big data architecture and now that's called __Hadoop__. And if you google Hadoop you'll see that it's a very popular term and there are hundreds of thousands of companies out there that have some kind of footprint in the big data world.


<h2>Deep Learning and Machine Learning</h2>

<h3>Neural Networks and Deep Learning</h3>

A neural network is trying to use a computer program that will mimic how neurons, how our brains use neurons to process things, brains to synapse, neurons to synapses and building these complex networks that can be trained. So a neural network starts out with some inputs and some outputs and you keep feeding these inputs in to try to see what kinds of transformations will get to these outputs, and you keep doing this over and over and over again in a way that this network should converge so that the transformations will eventually get these outputs. The problem with neural networks was that even though the theory was there and they did work on small problems like recognizing handwritten digits and things like that, they were computationally very intensive, and so they went out of favor.

Deep Learning is neural networks on steroids. What they did was they just had more multiple layers of neural networks and they use lots and lots of computing power to solve them.



<h1>Week 3: Data Science in Business</h1>



<h2>Applications of Data Science and Recruiting Data Scientists</h2>

<h3>How Should Companies Get Started in Data Science?</h3>

At the end of the day, for businesses, they know one thing, that if they are unable to measure something, they are unable to improve it. And if they are unable to measure their costs, they are unable to reduce them. If they're unable to measure their profits, they are unable to increase them. So the first thing a company has to do is to start recording information, start capturing data, data about costs and then differentiate it by labor costs, material cost and the total cost. And then you look at the revenue, where's your revenue coming from? Is 80% of your revenue coming from 20% of your customers? Or is it the other way around? So first thing first, start capturing data. Once you have data, then you can apply algorithms and analytics to it. If you're not capturing data, start capturing it. If you're capturing it, archive it. Do not overwrite on your old data thinking you don't need it anymore. Data never gets old. Data is always relevant, even if it's 100 years old, 200 years old. It is relevant to you and and your firm and your success. So keep data, capture it, archive it, make sure nothing goes to waste. Make sure there's a consistency. So someone 20 years later trying to understand that data should be able to do so, so have proper documentation. Do it now. Put the best practices for data archiving in place the moment you start a business. And if you're already in business and you haven't done it, do it now.

Start measuring things. Too many companies haven't measured things properly for a decade and then they decide they want data science. Data science inside a company is only going to be as valuable as the data collected. Garbage in, garbage out is a rule in any sort of analysis. If something is not measured, it's very difficult to improve it or to change it. So the very first step is measurement. If companies have existing data, then they should start looking at it and clearing it.

Then look for a team who love to work as data scientists. The first stop is to have employees who are interested in data science, because if you don't have interest in your company, you will not have engagement. Companies should remember that it's key to have a team. So it's not one data scientist, but a team of them, that each of them have strengths in different areas of data science.

<h3>Recruiting for Data Science</h3>

When companies are hiring people for a data science team, maybe a data scientist or an analyst, or a chief data scientist. The tendency would be to find the person who has all the skills, that they know the domain-specific knowledge. They're excellent in analyzing structured and unstructured data. And they're great at presenting and they've got great storytelling skills. So if you put all this together, you will realize you're looking for a unicorn. And your odds of finding a unicorn are pretty rare. I think what you need to do to is to see, given the pool of applicants you have, who has the most resonance with your firm's DNA. Because you can teach analytics skills, anyone can learn analytics skills if they dedicate time and effort to it. But what really matters is who's passionate about the kind of business that you do. Someone could be a great data scientist in the retail environment, but they may not be that excited about working in IT related firms or working with gigabytes of weblogs. But if someone is excited about those weblogs, if someone is excited about health-related data then they would be able to contribute to your productivity much more so.

If I'm looking for someone, if I have to put together a data science team, I would first look for curiosity. Is that person curious about things not just for data science but anything like, are they curious about why this room is painted a certain way, why do the bookshelves have books, and what kinds of books? They have to have a certain degree of curiosity about everything that is in their vision, that they look at. The second thing is do they have a sense of humor because, you see, you have to have a lighthearted about it. If someone is too serious about it, they probably would take it too seriously, and would not be able to look at the lighter elements. The third thing I think, and I think the last thing that I would look for are technical skills. I would go through the social skills, curiosity and sense of humor. The ability to tell a story, the ability to know that there is a story there. And then once all is there then I would say, well, can you do the technical side of it? And if there is some hope or some sign of some technical skills, I would take them because I can train them in whatever skills they need. But I cannot teach curiosity. I cannot teach storytelling. I cannot certainly, instill sense of humor in anyone.

From a skills point of view, let's focus on the technical skills and in that case, first thing would be what kind of a technical platform would you like to adopt? Let's say you want to work in a structured data environment and let's say you want to work in market research. Then the type of skills you need are slightly different than someone who would like to work in big data environments. If you want to work in the traditional market research data, structured data environment, your skills should be some statistical knowledge and some knowledge of basic statistical algorithms, maybe some machine learning algorithms. And these are the tools that you would like to develop. If you want to work in big data, then there's the other aspect of it and that is to be able to store data. So you start with the expertise in storing large amounts of data. And then you look into platforms that allow you to do that. The next step would be to be able to manipulate large amounts of data, and the final step would be to apply algorithms to those large sets of data. So it's a three-step process. But most likely it starts with where you would like to be, in what field, in what domain. In terms of platforms, let's you want to be in the traditional predictive analytics environment, and you're not working with big data, then R or Stata, or Python would be your tools. If you're working mostly with unstructured data, then Python is most suitable than R. If you're working with big data, then Hadoop and Spark are the environments that you will be working with. So it all depends upon where you would like to be and what kind of work excites you and then you pick your tools.
