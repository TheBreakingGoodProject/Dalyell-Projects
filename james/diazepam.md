# MEDICINE 1: DIAZEPAM (updated 02/04/21)

## Introduction Survey

“Where do you live? (country)”: Would it be more convenient to replace the text input with a dropdown menu? This would allow less room for error.

“Have your studies and/or career involved health, medicine, chemistry or pharmaceutical topics?”: Replace text input with [yes]  [no] buttons? Simply because boolean data would be much easier to interpret.


## Challenge 1: News Flash

Challenge context was confusing as it implied to me that it was asking about news articles that I’ve spontaneously seen. But obviously, it had to be a news articles that I had to actively search and reach out to see.

Confusing as to whether or not I answer survey questions from memory or reference the source material directly? As I would’ve imagined that an interesting part of the survey to explore would be seeing what information is actually retained from news articles by users, and what is forgotten.

I chose the side effects option, but in the process of searching, I wasn’t familiar with the difference between adverse effect and side effect. Of course this is pretty minor, but something I wanted to be sure about; side effects are generally expected (well observed and studied, thus well known at the time of administration) and can be good/bad. Adverse effects are unexpected and come as an unpleasant surprise, being noxious in nature. [^1]  [^2]

Diazepam has an extensive list of side effects [^3]  [^4]. It is labeled as having a black box warning which “is the most serious warning from the [FDA]...” [^4] Although I felt that this was misleading as the warning is for combining diazepam with opioid medications or other sedating medications. [^5] Since this warning popped up at the top of the page with no context and seemed more like a general warning, one has to question why they would place that there.

### Side Effects

- drowsiness
- tiredness or fatigue
- muscle weakness
- headache
- tremor
- dizziness
- dry mouth or excessive saliva
- nausea
- constipation
- confusion
- difficulty urinating
- frequent urination
- changes in sex drive or ability
- loss of control of bodily movements
- uncontrollable shaking of a part of the body
- slowed or slurred speech
- slowed breathing and heartbeat
- worsening of seizures frequency or severity
- depression
- feelings of the room spinning (vertigo)
- double or blurred vision
- thoughts of suicide
- memory loss
- extreme excitement
- anxiety
- hallucinations
- increased muscle spasms
- trouble sleeping
- agitation
- yellowing of your skin or whites of your eyes (jaundice)
- abdominal or muscle cramps
- convulsions

[^1]:  https://www.pharmacytimes.com/view/adverse-event-not-the-same-as-side-effect

[^2]: https://www.youtube.com/watch?v=lfDOseggwVA

[^3]: https://www.ncbi.nlm.nih.gov/books/NBK537022/

[^4]: https://www.medicalnewstoday.com/articles/diazepam-oral-tablet

[^5]: https://www.nami.org/About-Mental-Illness/Treatments/Mental-Health-Medications/Types-of-Medication/Diazepam-(Valium)


## Challenge 2 Price Hike

I found it confusing when asked to use a search engine in a website and document what I had found. What is the purpose of asking to look up a specific website and input search results? Is this to see how well we are at looking up a website or is this to check the actual information? If it is the former, displaying the instructions step by step defeats the purpose of seeing if the user is able to see the information. Instead, you would give the survey participant a general goal, which they would need to figure out naturally to reach. If it’s the latter (simply gathering the data), why not use a web scraper?


## Challenge 3 Circle Of Life

Spelling error in description: “Excellent! You chose diazepam. Now that you have chosen an essential medicine, it is time to look it up on our public database. We will use this databaes to find out which company currently owns the rights to diazepam, what its trade name is and when it was first approved. You can find this information in the following link.”

Confusion about given database as when I had a look, my chosen medicine (diazepam) was not found in database.

*UPDATE: medicine was found. Perhaps the database wasn’t updated when I originally checked.*

The database was quite overwhelming, especially with the duplicate medicines with variating information. Maybe a direct instruction to simply pick at random? And if random isn’t the ideal choice, then what is the ideal choice?

It is claimed that .gov .edu and .org websites are signs of a trustworthy site. I understand the reasoning behind .edu and .gov (as only educational or government can create them), however, .org websites can be registered by anyone.

This challenge required me to filter through a lot, as information on original owners is pretty niche; most websites covering usage information instead of historical origins.


### First site: https://www.ncbi.nlm.nih.gov/books/NBK423855/

- .gov site
- Author of article is the International agency for research on cancer WHO, website provided

A method for preparing diazepam was first reported in 1961. The first commercial production of diazepam was first reported in 1963


### Second site: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3990949/

- .gov
- Include author, contact details and author credentials

Diazepam was originally manufactured by Hoffman-La Roche, first synthesised in 1959, then patented and entered the market in 1963 (corroborating with site 1). The patent then expired in 1985, such that over 500 different brands of diazepam in various forms were now sold (what happens when a patent expires?)

After the patent expires, anyone may make, use, offer for sale, sell or import the invention without permission of the patent owner [^6]


### Third site: https://www.ncbi.nlm.nih.gov/books/NBK537022/

- .gov
- Author information and affiliations, but no contact details

First patented in 1963


### Fourth site: https://en.wikipedia.org/wiki/Diazepam

- .org (one example where .org doesn’t necessarily mean anything)

Citations provided for diazepam being patented in 1959 by Hoffman-La Roche [^7]

[^6]: https://corporate.findlaw.com/intellectual-property/u-s-patent-overview.html
[^7]: https://worldwide.espacenet.com/patent/search/family/027585147/publication/US3371085A?q=pn%3DUS3371085A
