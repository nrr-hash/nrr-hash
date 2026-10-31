Nathaniel. 
Content strategist and editor. B2B, B2C, B2G and technical content, as well as the tools that check it.
I write and edit for private and public sector clients across the UK, German and Maltese markets, under the Human in the Loop positioning. The work is editorial quality assurance, fact-checking and brand voice systems, with English language training for German executives (specialist construction sector) and their teams.
How the work is checked: 
A house style is only worth having if it can be enforced after the fact. Mine is, by a versioned style pack and a set of Python tools that audit a draft against it: proscribed vocabulary and constructions, sentence-length distribution, and a comparison of successive drafts that reports what changed, including figures introduced and qualifications lost.
Each check emits JSON. The exit code is not the result; the JSON is.

Some of that measurement work is public: [search-benchmarks](https://github.com/nrr-hash/search-benchmarks) holds two reproducible rigs, a job-ad audit and a sitemap/feed availability benchmark.
Two design decisions worth stating: 
The ban list runs after drafting, never during. Instructing a writer, human or otherwise, to avoid a list of words distorts the draft around the list. So the draft is made by thought and ear, and the scanners run on what comes out. A scanner hit is a prompt to look at a sentence, not an instruction to change it. A lower hit count is not better writing.
Veracity outranks style. Every substantive factual claim is listed with its intended evidence before drafting, traced to source after drafting, and reread adversarially after every material edit for numbers, dates, units, names and attribution. Anything unverifiable is cut or flagged. Gaps are never smoothed over.
Checks performed by a model are model research. Only a named person who has read the source can mark a claim verified.
Based in Gozo, Malta.
