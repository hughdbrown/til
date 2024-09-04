* [Zero regrets: Firefox power user kept 7,500 tabs open for two years](https://www.techspot.com/news/102871-zero-regrets-firefox-power-user-kept-7500-tabs.html)
* [FastHTML web framework](https://www.fastht.ml/)
* [Dave Kiss on winning contests](https://davekiss.com/contests)
* [Dave Kiss on winning the WD-40 contest](https://davekiss.com/blog/how-i-won-2750-using-javascript-ai-and-a-can-of-wd-40)
* [ai_alchemy python library for getting structured data from LLM requests](https://pypi.org/project/ai-alchemy/)
* [Technical blog on LLMs, RAG, generative AI](https://www.lycee.ai/blog)
* [Build an audio AI assistant](https://www.lycee.ai/blog/audio-ai-assistant-openai)
* [Transcribe audio and video files with Python and Universal-1](https://www.assemblyai.com/blog/transcribe-audio-python-universal-1)
* [Extraordinary Videos powered by AI](https://autoeditor.video/)
* [Llama 3.1 Deep Dive: Beyond the Hype](https://ai.gopubby.com/llama-3-1-deep-dive-beyond-the-hype-68af405c4ec1)
* [Optimization story - quantum mechanics simulation speedup](https://tinkering.xyz/fmo-optimization-story/#problem-description)
* [Show HN: Ell – A command-line interface for LLMs written in Bash](https://news.ycombinator.com/item?id=41138085)
* [Back-dating Git commits based on file modification dates](https://til.simonwillison.net/git/backdate-git-commits)
* [Ask HN: How different is AWS/GCP/Azure in everyday work](https://news.ycombinator.com/item?id=41182565)
* [How to Build Anything Extremely Quickly](https://learnhowtolearn.org/how-to-build-extremely-quickly/)
* ["We ran out of columns" - The best, worst codebase](https://jimmyhmiller.github.io/ugliest-beautiful-codebase)
* [Ask HN: How to build site with payment, subscriptions, user login, registration](https://news.ycombinator.com/item?id=41182823)
* [Tracking supermarket prices with playwright](https://www.sakisv.net/2024/08/tracking-supermarket-prices-playwright/]
* [Playwright for python](https://playwright.dev/python/docs/intro)
* [23+ Best React Libraries & Plugins for Different Functionalities in 2024](https://dev.to/syakirurahman/23-best-react-libraries-plugins-for-production-grade-app-in-2024-5fjb)
* [What's New in React 19: A Deep Dive into the Latest Features](https://dev.to/vyan/whats-new-in-react-19-a-deep-dive-into-the-latest-features-3gp2)
* [9 Must-Try React UI Component Libraries for Stunning Web Apps in 2024](https://dev.to/vyan/9-must-try-react-ui-component-libraries-for-stunning-web-apps-in-2024-p7j)
* [FastHTML: Revolutionizing Web Development with Python](https://medium.com/@rajputgajanan50/fasthtml-revolutionizing-web-development-with-python-dd4b68f8b922)
* [Mastering Bollinger Bands: A Comprehensive Guide with Python and OpenBB](https://hub.tinztwins.de/mastering-bollinger-bands-a-comprehensive-guide-with-python-and-openbb)
* [LangChain for Finance](https://shop.tinztwins.de/l/langchain-for-finance)

* [Prime polynomial approximation](https://www.lycee.ai/blog/ai-prime-numbers-numpy)
Has a good piece of code for finding primes:
```python
def is_prime(n):
    """Function to check if a number is prime"""
    if n <= 1:
        return False
    if n <= 3:
        return True
    if n % 2 == 0 or n % 3 == 0:
        return False
    i = 5
    while i * i <= n:
        if n % i == 0 or n % (i + 2) == 0:
            return False
        i += 6
    return True
```

* Websites with for-profit video courses
1. [lycee.ai](https://www.lycee.ai/search)
2. [maven.com](https://maven.com/)
3. [Talk Python](https://training.talkpython.fm/)
4. [Accelerant (Rust bootcamp)](https://accelerant.dev/)
5. [Let's Get Rusty (Rust bootcamp)](https://portal.letsgetrusty.com/bootcamp/)
6. [Docker, Flask, Let's Encrypt](nickjanetakis.com)

* Maven courses
1. [AI Engineering Essentials](https://maven.com/snrism/aiessentials)
2. [Building LLM Applications](https://maven.com/boring-bot/ml-system-design)
3. [Systematically Improving RAG Applications](https://maven.com/applied-llms/rag-playbook)


* Favorite python libraries
1. pathlib
2. collections
3. itertools
4. dataclass
5. tomllib

* [Recursively split by character](https://python.langchain.com/v0.1/docs/modules/data_connection/document_transformers/recursive_text_splitter/)
* [Chunking: Let's Break It Down](https://www.datastax.com/blog/chunking-to-get-your-data-ai-ready)
* [Chunking strategies](https://docs.unstructured.io/api-reference/api-services/chunking)
* [MTEB: Massive Text Embedding Benchmark](https://huggingface.co/blog/mteb)
* [Deserialising binary data in Rust](https://dev.to/thiagomg/deserialising-binary-data-in-rust-2di4)
* [100 Days of Generative AI - Building Your First RAG Application Using Open-Source tools: Day 8](https://dev.to/lakhera2015/100-days-of-generative-ai-building-your-first-rag-application-using-open-source-tools-day-8-3kc6)
* [Rust + Lambda using CDK & Github Actions (Part 2)](https://dev.to/mblydenburgh/rust-lambda-using-cdk-github-actions-part-2-4cm2)
* [Rust + Lambda using CDK & Github Actions (Part 1)](https://dev.to/mblydenburgh/rust-lambda-using-cdk-github-actions-part-1-1bnk)
* [Rust #7: Command-Line interfaces](https://dev.to/cthutu/rust-7-command-line-interfaces-4084)
* [Top 10 React Performance Optimization Techniques](https://dev.to/dipakahirav/top-10-react-performance-optimization-techniques-ikp)
* [Arapahoe County online Digital Resources](https://www.hoopladigital.com/)
* [Vector search extension for sqlite](https://github.com/asg017/sqlite-vec/)
* [SQLite FTS5 Extension](https://www.sqlite.org/fts5.html)
* [Mara's Blog](https://blog.m-ou.se/)
* [Brooks Builds](https://www.youtube.com/@BrooksBuilds)
* [The Rust Corner Podcast](https://www.youtube.com/playlist?list=PLpmILDwWLo7tbogGhbPBVi8ktx99NU5v6)
* [Mojo vs. Rust](https://github.com/mikeleppane/mojo-rust-python-perf/blob/main/n_body_rust/src/lib.rs)
* [Data-Parallelism in Rust with the Rayon Crate](https://www.linkedin.com/pulse/data-parallelism-rust-rayoncrate-luis-soares-m-sc--csvsf/)
* [What does Rust´s From Trait teach us about elegant Code?](https://medium.com/@patrickkoss/what-does-rust-s-from-trait-teach-us-about-elegant-code-92b8eb36f98c)

* [Why Is dbt So Popular？dbt + RisingWave: The Ultimate Real-Time Data Warehouse Combination](https://towardsdev.com/why-dbt-is-so-popular-8f957c945106)
* [Meet Claude Dev — An Open-Source AI Programmer In VS Code](https://generativeai.pub/meet-claude-dev-an-open-source-autonomous-ai-programmer-in-vs-code-f457f9821b7b)

* Git stacking
1. [Git-spice - manage stacked Git branches](https://forum.devtalk.com/t/git-spice-manage-stacked-git-branches/163192)
2. [Working with stacked branches in Git is easier with --update-refs](https://andrewlock.net/working-with-stacked-branches-in-git-is-easier-with-update-refs/)
3. [The stacking workflow](https://www.stacking.dev/)
4. [git stack repo](https://github.com/gitext-rs/git-stack)
5. [Stacked git](https://stacked-git.github.io/)
https://github.com/stacked-git/stgit
https://github.com/martinvonz/jj
https://github.com/gitext-rs/git-stack
https://sapling-scm.com/
https://github.com/ezyang/ghstack
https://github.com/arxanas/git-branchless
https://github.com/VirtusLab/git-machete
https://github.com/ejoffe/spr
https://github.com/git-town/git-town
https://github.com/tummychow/git-absorb
https://github.com/torbiak/git-autofixup
https://github.com/iOliverNguyen/git-pr
6. [git-spice CLI](https://abhinav.github.io/git-spice/cli/)




* [itsy-gitsy: A static site generator for Git repositories](https://git.trevorbentley.com/itsy-gitsy/)
* [TIL: Mermaid Gantt diagrams are great for displaying distributed traces in Markdown](https://brycemecum.com/2023/03/31/til-mermaid-tracing/)
* [Mermaid lets you create diagrams and visualizations using text and code.](https://mermaid.js.org/intro/)
* [llm cmd undo last git commit—a new plugin for LLM](https://simonwillison.net/2024/Mar/26/llm-cmd/)

* Rust learning resources
1. [Rust Learning Resources](https://dev.to/cryptorustacean/rust-learning-resources-2jkc)
2. [Recommended learning resources for Rust in 2024](https://blog.stackademic.com/recommended-learning-resources-for-rust-in-2024-174cb686acc2)
3. [Rust Atomics and Locks, Mara Bos](https://marabos.nl/atomics/)
4. [The Rustonomicon](https://doc.rust-lang.org/nomicon/)
5. [Rust Design Patterns](https://rust-unofficial.github.io/patterns/)
6. [The Rust Performance Book](https://nnethercote.github.io/perf-book/)
7. [Practical WebAssembly](https://www.oreilly.com/library/view/practical-webassembly/9781098142513/)
8. [Async Rust](https://www.oreilly.com/library/view/async-rust/9781098149086/)
9. [Write Powerful Rust Macros](https://www.manning.com/books/write-powerful-rust-macros)
10. [Rust Advanced Techniques](https://www.manning.com/books/rust-advanced-techniques)
11. [Code Like a Pro in ust](https://www.manning.com/books/code-like-a-pro-in-rust)
12. [Asynchronous Programming in Rust](https://www.packtpub.com/en-us/product/asynchronous-programming-in-rust-9781805128137)
13. [Command Line Rust](https://www.oreilly.com/library/view/command-line-rust/9781098109424/)
14. [Rust Servers, Services, and Apps](https://www.manning.com/books/rust-servers-services-and-apps)
15. [Rust for Rustaceans](https://rust-for-rustaceans.com/)
16. [Programming Rust](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/)



* Companies for online deployments
1. fly.io
2. vercel
3. Heroku

* Markdown presentation tools
1. [Marp](marp.app/)
2. Reveal.js
3. Lookatme
4. slidev: has math/latex, mermaid

* terminal applicatiopns for developers
1. jq
2. yq
3. jqp
4. sshs
5. fzf

* websites for stock data
1. alpaca

* AI tools for video development
1. jupitrr to edit video
2. chat-gpt to create script
3. elevenlabs for voiceovers
4. mux

* moviemaking skills
1. gimbal walk
2. gimbal shots
3. shot types
- over the shoulder
- wide
- closeup
- establishing shot

* python libraries / companies for LLMs / RAG
1. langflow
2. langchain
3. langsmith
4. unstructured.io

* VS Code addins for AI
1. copilot
2. codeium
3. Cody AI

* github profile
1. shield.io has badges
2. course by github user CodeStackr
3. [Udacity course] https://www.udacity.com/course/github-actions--cd13461)

* video development skills
1. google slids
2. some other slide stack that does markdown + math
3. Davinci Resolve
4. Davinci Resolve Speed Editor
5. Wacom Tablet + krita
6. ATEM Mini Pro
7. Tools for video chapters / lower thirds
- H2R Graphics
8. VS Code
9. OBS Studio
10. Teleprompter
11. iPad (teleprompt upload and presentation)

* skills to teach
1. react
2. LLM
3. Rust language
4. Github actions
5. Rust problems
- Tim's Linkedin problems
- [Rustlings](https://github.com/rust-lang/rustlings)
- [Advent of Code](https://adventofcode.com/)
6. SQL window functions
7. free application server deployment
- vercel
8. python problems
- leetcode
- Advent of Code


* first videos
1. prime numbers
2. Newton-Raphson
- square roots
- Lambert W function
3. Solving math problems with Lamber W function
4. Github profile (pimp your ride)
5. TIL repo
6. Github CI/CD updater/scraper app
7. Polars

* projects to complete
1. Zola blog on github.io
2. Github profile
3. TIL content / repo
4. TIL on web
5. profile / portfolio application
6. python language project to replace os.path with pathlib
7. learn youtube / video production
- thumbnails
- lower thirds / chapters
- script production
- video editing

* pre-IPO stock tracking sites
1. Hiive
2. Carta
3. Forge Global

* Speakerdeck presentations
1. [Rust in Production](https://speakerdeck.com/mre/rust-in-production)
2. [A yeqar of Rust](https://speakerdeck.com/stevezeidner/a-year-of-rust)
3. [Rust Stack vs Heap usage](https://speakerdeck.com/deepu105/rust-stack-vs-heap-usage)
4. [Idiomatic Rust - Writing concise and elegant Rust code](https://speakerdeck.com/mre/idiomatic-rust-writing-concise-and-elegant-rust-code)


* Amazon stores
1. [SmallRig](https://www.amazon.com/stores/SmallRig/page/6EE43315-D8D3-412E-BC03-029F56132C78)


* [AI Resume Parser](https://github.com/starglow-it/ai-resume-parser/blob/main/README.md)
* [I’m sick and tired of prompt engineering. So I made an automated prompt optimizer (Part 2)](https://ai.plainenglish.io/im-sick-and-tired-of-prompt-engineering-so-i-m-making-a-prompt-optimizer-part-2-9ff3aa47641d)
* [19 Developer Tools that keep me productive](https://medium.com/@codingwinner/19-developer-tools-that-keep-me-productive-b1b745412465)
* [35% Faster Than The Filesystem](https://sqlite.org/fasterthanfs.html)
* [Introduction to Machine Learning Interviews Book](https://huyenchip.com/ml-interviews-book/)
* [A Practical Guide to using Pydantic](https://medium.com/@marcnealer/a-practical-guide-to-using-pydantic-8aafa7feebf6)
* [An Open Course on LLMs, Led by Practitioners](https://hamel.dev/blog/posts/course/)

* Job websites for 2024
1. [Python Coders' Jobs](https://www.pythonjobshq.com/)


* [The Complete History & Strategy of Visa](https://www.acquired.fm/episodes/visa)
* [What Visa earnings really tell us](https://www.popularfintech.com/p/what-visa-earnings-really-tell-us)
* [Twelve Labs -- Unlock the power of multimodal video understanding](https://auth.twelvelabs.io/)


* AI service sites
1. [Claude AI](https://claude.ai/)
2. [Chat GPT](https://openai.com/)


* [Henry A. Daverin](https://www.50-a.org/officer/JPRP)

* [Building Reliable and Robust ML/AI Pipelines](https://hugobowne.substack.com/p/building-reliable-and-robust-mlai)
* [Cut Code Review Time & Bugs in Half](https://coderabbit.ai)
* [These Are the 10 AI Startups to Watch in 2024](https://archive.ph/ZGNB3)
* [Datacamp youtube videos / streams](https://www.youtube.com/@DataCamp/streams)
* [Get Employed Sooner With Our AI Services!](https://www.jobsguru.ai/frontend/home.html)
* [I 10x’d my Coding Productivity Using this AI Tool: I wish I had known it Earlier](https://dev.to/github20k/i-10xd-my-coding-productivity-using-this-ai-tool-i-wish-i-had-known-it-earlier-2eoo)
* [AI Tooling for Software Engineers in 2024: Reality Check (Part 1)](https://newsletter.pragmaticengineer.com/p/ai-tooling-2024)
* [The Perfect Storm Causing an Insane Tech Hiring Market](https://newsletter.pragmaticengineer.com/p/perfect-storm-causing-a-hot-tech-hiring-market)
* [Follow-Up: the Insane Tech Hiring Market](https://newsletter.pragmaticengineer.com/p/follow-up-insane-tech-hiring-market)
* [More Follow-Up on the Tech Hiring Market](https://newsletter.pragmaticengineer.com/p/more-follow-up-hiring-market)
* [The Scoop #2: The Hiring Market](https://newsletter.pragmaticengineer.com/p/the-scoop-2)
* [The Tech Hiring Market: 2022 Predictions](https://newsletter.pragmaticengineer.com/p/2022-predictions)
* [The Scoop #4: Remote work and Interacting with Recruiters](https://newsletter.pragmaticengineer.com/p/the-scoop-4)
* [Inside Meta's Engineering Culture: Part 1](https://newsletter.pragmaticengineer.com/p/facebook)
* [The Tech Downturn](https://newsletter.pragmaticengineer.com/p/the-tech-downturn-newcomer)
* [Inside Meta's Engineering Culture: Part 2](https://newsletter.pragmaticengineer.com/p/facebook-2)
* [Preparing for Layoffs in Tech](https://newsletter.pragmaticengineer.com/p/preparing-for-layoffs)
* [What is Data Engineering?](https://newsletter.pragmaticengineer.com/p/what-is-data-engineering)
* [The Big Tech Hiring Slowdown Is Here and it will Hurt](https://newsletter.pragmaticengineer.com/p/big-tech-hiring-slowdown)
* [The Scoop: The 2022 Hiring Market, as seen by Tech Recruiters](https://newsletter.pragmaticengineer.com/p/the-scoop-the-2022-hiring-market)
* [The Scoop #40: Performance reviews, equity refreshers and cost cutting](https://newsletter.pragmaticengineer.com/p/the-scoop-40)
* [The productivity impact of AI coding tools](https://newsletter.pragmaticengineer.com/p/ai-coding-tools)
* [The Scoop #47: Datadog’s $65M/year customer mystery solved](https://newsletter.pragmaticengineer.com/p/the-scoop-47)
* [Stacked Diffs (and why you should know about them)](https://newsletter.pragmaticengineer.com/p/stacked-diffs)
* [Inside Stripe’s Engineering Culture - Part 1](https://newsletter.pragmaticengineer.com/p/stripe)
* [The Pulse #75: Will US companies hire fewer engineers due to Section 174?](https://newsletter.pragmaticengineer.com/p/the-pulse-75)
* [Inside Stripe’s Engineering Culture: Part 2](https://newsletter.pragmaticengineer.com/p/stripe-part-2)
* [Applied AI Software Engineering: RAG](https://newsletter.pragmaticengineer.com/p/rag)
* [13 Hidden Open-source Libraries to Become an AI Wizard](https://dev.to/composiodev/13-hidden-open-source-libraries-to-become-an-ai-wizard-4ng9)
* [Add this "AI Code Assist" badge to your Github Readme](https://dev.to/commanddash/add-this-ai-code-assist-badge-to-your-github-readme-178a)
* [Rust Hashmaps: A Hands-On Comparison](https://blog.stackademic.com/rust-hashmaps-a-hands-on-comparison-b20123e80353)

* [Song for Dave Kiss's competition videos](https://suno.com/song/09bc3c8f-3ac7-4cb6-bad9-a331f254f95b)

* [Mermaid Diagramming and charting tool](https://mermaid.js.org/)

* [Bolt Depot - Fastener shopping made easy](https://boltdepot.com/Catalog)

* [Storyteller tactics](pipdecks.com)

* [A course by Andrej Karpathy on building neural networks, from scratch, in code](https://karpathy.ai/zero-to-hero.html)
* [Andre Kaparthy's youtube channel](https://www.youtube.com/@AndrejKarpathy)

* Command line utilities
1. lazygit
2. fzf
3. gh
4. zellij
5. sshs
6. tig
7. warp

* [The Ultimate AI Tool Kit](https://doc.clickup.com/37456139/d/h/13q28b-204/5a46c0ced275cf7)
* [Run LLMs locally](https://medium.com/sourcescribes/trending-tools-for-running-an-llm-locally-980b984c0e92)
* [Mermaid for Gantt charts](https://brycemecum.com/2023/03/31/til-mermaid-tracing/)

* Video editing workflow
1. [AutoEditor – Edit your video in just a few clicks](https://news.ycombinator.com/item?id=41174996)

* Algorithms
1. [Fast data structures for disjoint intervals?](https://news.ycombinator.com/item?id=41000844)

* Learning management systems
1. [mux-player-react](https://www.npmjs.com/package/@mux/mux-player-react)
`mux-player-react` is not an LMS but it does provide the video player for such a system.


* Random gen-AI links
- [](https://docs.anthropic.com/en/docs/build-with-claude/tool-use)
https://github.com/SonicDMG/babbelfish.ai


* GraphRAG
- [](https://youtu.be/knDDGYHnnSI?si=61_WAU0xiOciUxP-)
1. DO a vector search to find an initial set of nodes
2. Traverse the graph around the nodes to add context
3. Optionally rank the results using the graph and pass the top-k documents to the LLM

* AI Engineer videos
- [AI Engineer on YouTube](https://www.youtube.com/@aiDotEngineer)

* LeetCode technique
- [LeetCode was HARD until I Learned these 15 Patterns](https://medium.com/@ashishps/leetcode-was-hard-until-i-learned-these-15-patterns-19d15f6d71f1)

* LLM from Scratch Workshops
- [Andrej Karpathy video](https://www.youtube.com/watch?v=kCc8FmEb1nY)
- [Sebastian Raschka video](https://youtu.be/quh7z1q7-uc)
- [Sebastian Raschka article](https://magazine.sebastianraschka.com/p/building-llms-from-the-ground-up)

