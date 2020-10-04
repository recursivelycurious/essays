[Index](https://recursivelycurious.github.io/essays/index.html) ~~ [About](https://recursivelycurious.github.io/essays/about.html)


# The Importance of Revisions

These are strange times. Confusing. Overwhelming. It can be difficult to make sense of it all. I have a lot of questions, and I expect I am not the only one.

I work as a technologist. The kinds of systems that make it possible for you to read these words right now are what my colleagues and I produce. This type of work has paid the bills for almost a decade now and has become a career. Rather a surprise to the version of myself that attended university. Cogent with hindsight perhaps, but we must live life forwards.

Early in my career I worked in "tech support". I have access to the engineers. I might even have access to the code. You have access to neither. You are trying to make our technology do something that the web page claims - to your understanding - that it is capable of doing. Somewhere, something is wrong. There is a bug. It might be in our code. It might be in our documentation. It might be in our marketing. It might simply be a gap in your understanding. My job - then and with layers of abstraction since - is to find that bug... and squash it.

In those days a common ticket type I worked on was a customer trying to use our API. As I explained it then...

> ... when you come to our web page, you are using our Graphical User Interface (GUI); a bunch of pictures and icons interlinking parts of our application in a way that makes it easy for you, a human with a browser, to work with. Similarly we provide an Application Programing Interface (API) that is designed for machines rather than humans...

Is this wrong? A more _complete_ or _accurate_ definition certainly can be provided, but would it have helped most of the folks opening tickets?

At the same time, I also distinctly recall dispensing the following "knowledge" about our REST API:

> ... A `GET` request can't alter the state of the server...

Which, _for the system in question at the time_ was completely inaccurate. 

I'd done a bit of googling, but too little experimenting, and since technology I was supporting was a "RESTful" API, the Sherlock in me deduced that our GET method would not modify server state.

And I was wrong. 

What might we learn from such errors?

One of the themes of these essays - and an architectural principle around which the content will be built - is that systematically documenting our provisional understanding (even if we believe it to be something _more_ than provisional) and then _revising it in the face of new evidence_ is epistemically important.

"Well, duh!" I hear you say, "That is just science." Right. _Just science_. Yet another conception worth checking into source and revising as needed.

Shall we begin?

- RC Grey

[Index](https://recursivelycurious.github.io/essays/index.html) ~~ [About](https://recursivelycurious.github.io/essays/about.html)
