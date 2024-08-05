# A quick note to the Test Readers.
Thanks so much for the opportunity to take this test.
I found it quite interesting as I have not had a chance to use Fastify before, 
though I have been using Fresh, React, Next and payload recently.

The system of cachedFetch as a hook is interesting and I went simple but tried to use some shared functions.

A have a similar effort in production already. In that case, my system 
features cachetimeouts and also allows a parser/processing function to be passed in 
via a configuration.  The cache stores the parsed/processed version of the data
of course.

In any event, this was fun and I hope to have a chance to discuss going forward.

Regards,
Robert LaMarca 
646 732 8315
robertlamarca@gmail.com

# To make this ready for production

## Auto Rebuild System (nice to have)
I had to triage this as my initial attempts did not quite do it. 
With a bit more time, I would have researched Fastify solutions for this 
or else worked to get the solution in synch from the esbuild configurations.

I have done this with simple esbuild solutions before, but had issues chaining them in the time alloted


## Replace the mockServiceWorker
Since, you know, it says to not use it in production.
Turns out just shutting this off works fine.
This will make me a bit crazy later and I will look into a more complete solution if there is one.

## Others

### Setup Unit Tests

### Setup CI/CD pipeline

### Setup Team review and PR protocol

### Setup Error Tracking

### Logging

### Data Sanitation

