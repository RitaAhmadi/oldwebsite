
---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: profile.jpeg
  image_circular: false
  image_width: 200px
  more_info: fatimah dot rita dot ahmadi at gmail dot com

featured:
  enabled: true
  heading: "Featured"
  items:
    - title: "Your featured item title"
      description: "A short description of this item."
      link: "#"       # URL or file path, e.g. /assets/pdf/paper.pdf
    - title: "Another featured item"
      description: "Another short description."
      link: "#"

announcements:
  enabled: true
---

I am a stipendiary lecturer at Mansfield College...
Next steps
1. What items do you want in the Featured section? For example: papers, talks, uploaded PDFs, links to media coverage, awards? You mentioned wanting to add files — go ahead and upload them here and I'll give you the exact file paths and link values to use.

2. Does the al-folio layout support featured natively? The standard al-folio theme doesn't have a built-in featured section, so we'll also need to add a small snippet to the _layouts/about.liquid (or .html) file to render it. Want me to check that file too? Share the link:

https://github.com/RitaAhmadi/ritaahmadi.github.io/blob/main/_layouts/about.liquid

You said: three things
three things 

an article featured here
a bbc featured about an event
11:35 AM
Claude responded: Please share the details for both!
Please share the details for both! For each one, it would help to know:

The article — title, authors, link or PDF to upload?
The BBC feature — is this the one already in your news section ("What is the weirdest thing in the universe?")? If so, just confirm and I'll use that link. Or do you have a different one?
And you said "three things" — what's the third? 😊

You said: and an interview
and an interview

11:35 AM
Claude responded: Got it!
Got it! So the three featured items will be:

📄 An article — please share the title, authors, and link/PDF
📺 BBC feature — is it this one: What is the weirdest thing in the universe??
🎙️ An interview — please share the title and link (or upload the file)
Share the details for each and I'll prepare all the changes needed!

You said: google.
google.com/search?q=rita+ahmadi&rlz=1C5OZZY_enGB1187GB1187&oq=rita+ahmadi+&gs_lcrp=EgZjaHJvbWUyCggAEEUYFhgeGDkyBwgBEAAYgAQyCAgCEAAYFhgeMggIAxAAGBYYHjIICAQQABgWGB4yBggFEEUYPDIGCAYQRRg8MgYIBxBFGDzSAQgyMDY3ajBqN6gCALACAA&sourceid=chrome&ie=UTF-8

11:35 AM
Claude responded: I found some great content!

Searched the web
Searched the web
I found some great content! I can see:

📄 Article: "The 2-Category of Topological Quantum Computation" on arXiv 
arXiv
🎙️ Interview: Research Insights with Dr Rita Ahmadi on the Imperial College QuEST blog 
Imperial
📺 BBC feature: Already in your news ("What is the weirdest thing in the universe?")
Are these the three you had in mind? Just confirm and I'll prepare the exact code for your _pages/about.md with all three featured items ready to go!

You said: https://www.
https://www.bbc.com/news/articles/c8xg7r4qqz4o

11:35 AM
Claude responded: No worries, I can't access BBC directly but I already have enough from your news section.

Failed to fetch: https://www.bbc.com/news/articles/c8xg7r4qqz4o
Failed to fetch: https://www.bbc.com/news/articles/c8xg7r4qqz4o
No worries, I can't access BBC directly but I already have enough from your news section. Here's what I'll use for the three featured items:

📄 Article — "The 2-Category of Topological Quantum Computation" → https://arxiv.org/abs/2505.22171
📺 BBC Feature — "What is the weirdest thing in the universe?" → https://www.bbc.co.uk/news/articles/c8xg7r4qqz4o
🎙️ Interview — "Research Insights with Dr Rita Ahmadi" (Imperial College QuEST blog) → https://blogs.imperial.ac.uk/imperialquest/2024/10/30/research-insights-with-dr-rita-ahmadi/
Here is the updated _pages/about.md with the Featured section added before the news/announcements:

markdown
---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: profile.jpeg
  image_circular: false
  image_width: 200px
  more_info: fatimah dot rita dot ahmadi at gmail dot com

featured:
  enabled: true
  items:
    - title: "The 2-Category of Topological Quantum Computation"
      type: article
      description: "New preprint on arXiv — proposes a braided fusion 2-category as a unified formalism for anyonic theories and topological quantum computing."
      link: "https://arxiv.org/abs/2505.22171"

    - title: "BBC: What is the weirdest thing in the universe?"
      type: press
      description: "Our debate was featured on BBC News."
      link: "https://www.bbc.co.uk/news/articles/c8xg7r4qqz4o"

    - title: "Interview: Research Insights with Dr Rita Ahmadi"
      type: interview
      description: "Imperial College QuEST blog — discussing quantum algorithms, category theory, and curiosity-driven research."
      link: "https://blogs.imperial.ac.uk/imperialquest/2024/10/30/research-insights-with-dr-rita-ahmadi/"

announcements:
  enabled: true
---

I am a stipendiary lecturer at Mansfield College, University of Oxford...
Now, since al-folio doesn't render featured out of the box, we also need to add a small block to _layouts/about.liquid to display it. Could you share that file?

https://github.com/RitaAhmadi/ritaahmadi.github.io/blob/main/_layouts/about.liquid

You said: https://quantumzeitgeist.
https://quantumzeitgeist.com/anyons-and-topological-quantum-computation-unified-by-category-theory/

11:37 AM
Claude responded: Got it — so the article is this Quantum Zeitgeist piece covering your paper.

Fetched: Anyons And Topological Quantum Computation Unified
Fetched: Anyons And Topological Quantum Computation Unified
Got it — so the article is this Quantum Zeitgeist piece covering your paper. Here's the final list of three featured items:

📄 Article — "Anyons & Topological Quantum Computation: Unified Theory" on Quantum Zeitgeist → https://quantumzeitgeist.com/anyons-and-topological-quantum-computation-unified-by-category-theory/
📺 BBC Feature — "What is the weirdest thing in the universe?" → https://www.bbc.co.uk/news/articles/c8xg7r4qqz4o
🎙️ Interview — "Research Insights with Dr Rita Ahmadi" on Imperial QuEST blog → https://blogs.imperial.ac.uk/imperialquest/2024/10/30/research-insights-with-dr-rita-ahmadi/
Now here are the exact files to edit. You'll need to make two changes:

1. Update _pages/about.md
Replace your entire front matter with this:

markdown
---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: profile.jpeg
  image_circular: false
  image_width: 200px
  more_info: fatimah dot rita dot ahmadi at gmail dot com

featured:
  enabled: true
  items:
    - title: "Anyons & Topological Quantum Computation: Unified Theory"
      type: article
      description: "Quantum Zeitgeist covers the new paper proposing a braided fusion 2-category as a unified formalism for anyonic theories and topological quantum computing."
      link: "https://quantumzeitgeist.com/anyons-and-topological-quantum-computation-unified-by-category-theory/"

    - title: "BBC: What is the weirdest thing in the universe?"
      type: press
      description: "Our debate was featured on BBC News."
      link: "https://www.bbc.co.uk/news/articles/c8xg7r4qqz4o"

    - title: "Interview: Research Insights with Dr Rita Ahmadi"
      type: interview
      description: "Imperial College QuEST blog — discussing quantum algorithms, category theory, and curiosity-driven research."
      link: "https://blogs.imperial.ac.uk/imperialquest/2024/10/30/research-insights-with-dr-rita-ahmadi/"

announcements:
  enabled: true
---

I am a stipendiary lecturer at Mansfield College, University of Oxford. Before that, I was a postdoctoral researcher at the Department of Mathematics, Imperial College London. I did my DPhil at Quantum Group based at the Department of Computer Science, University of Oxford. During my PhD, I worked on topological quantum computation and category theory. In my thesis, I studied and proposed bicategorical structures for topological quantum computation.
2. Add rendering code to _layouts/about.liquid
We need to add HTML to actually display the featured section. Please share this file:

https://github.com/RitaAhmadi/ritaahmadi.github.io/blob/main/_layouts/about.liquid

Once I can see it, I'll give you the exact snippet to insert and exactly where to place it.





Claude is AI and can make mistakes. Please double-check responses.
