# Project - Event Counter

### Assignment: 
Please write a small library which helps to track the number of events that happened 
during a specified window of time. As an example, it might be used to track 
how often a particular webpage is served. 

The library should support two operations:
 - Client should be able to signal that a single event happened (e.g. a page was served)
 - Client should be able to request the number of events that happened over a user-specified amount of time until current time. You may limit the supported timespan to a reasonable upper bound, like 5 minutes. 

Please only track counts, you do not have to track any data payload associated with an event. 

Since the main use for a component like this is presenting diagnostic information on demand, it doesn’t have to persist data. Additionally, please do not spend time writing an example application that integrates the library, because we will not base our assessment on it. 

We encourage you to reach out with any questions you have on the requirements and expectations.

### Assessment: 
We will assess your work on the following dimensions:

You asked the right kinds of questions either during the kick-off call or via email afterwards
The submission meets the technical requirements ("it works")
It doesn’t introduce negative side-effects like memory leaks under continued use
The code in the submission is clean, readable, and well-structured
The submission demonstrates clearly communicated reasoning

### Submittal: 
You can submit your result in whatever format you prefer. If you wish to submit via Github, please make it a publicly accessible repo. 

## Testing and Documentation
Some candidates may prefer to use this assignment to cover all of the technical aspects that we're looking to measure at their own pace. Other candidates may have time constraints preventing them from doing so. To accommodate, we present two options for this assignment: Production-Quality vs Abbreviated. If you choose the Abbreviated version, we will cover topics like testing and documentation during on-site modules. Please explicitly state your choice when submitting.

### Option A: Production-Quality
We expect the code to be at the bar that you consider "production quality." In addition to the above assessment criteria, that means the library should be in a state in which you would be happy to receive it if you were to become its new maintainer in terms of:
 - Code cleanliness
 - Robust and meaningful test coverage
 - Documentation

### Option B: Abbreviated
With this option, in deference to your time, we ask that you not spend your time on these kinds of things, as they will not be used to assess your work:

 - Do not bother writing module-level or function-level documentation -- we will cover technical documentation during the onsite.
 - Do not write exhaustive unit tests unless doing so is part of your preferred development flow -- we will cover testing during the onsite.

Also in the interest of your time, please come prepared with any and all questions around clarifying the scope of the project prior to the kick-off call. While we’re excited to help you produce the best possible solution, it will be up to you to make this time valuable with the questions you have. As extra motivation, the questions asked are a part of our evaluation criteria.
