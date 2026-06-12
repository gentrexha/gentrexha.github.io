---
layout: post
title:  "High-Level Notes on DS/ML Job Hunting, Part 1"
date:   2026-06-12 00:00:00 +0100
categories: datascience machinelearning interviews career jobsearch
---
This is my job search framework, the approach I follow every time I look for a new job. Part 1 covers mindset, preparation, finding jobs and applying, plus the things I do before every interview. Part 2, coming soon, dives deeper into each interview round: HR/recruiter, technical, architectural, take home, and cultural fit. The examples are DS/ML flavored, but most of this applies to any tech role.

## Mindset

- Job finding is a long game. It's a marathon, not a sprint. I've applied to 60+ jobs every time I've looked for a new job in my career.
- When applying to new jobs, remember getting the first interview is the hardest step. Most people get filtered out here, because there are so many people applying and only very few getting interviews. There's a lot of information that is abstracted away on the company's side to make this possible.
- Don't be shy to reach out multiple times to the same people. You have to think of you applying to jobs as a sales process. In sales you can't be shy and you always have to try 3 times. When you don't get a response the first time, remember people are busy, a message could've been put on todo and forgotten, timing wasn't right. That's why you remind them. Never take things personal.
- Keep track of your applications and steps. Have meeting notes in them, questions you've asked, offer details, etc. I like to use Notion for this.
- Schedule times for applying N jobs each day (3-5 for me usually), because if I start mass applying my quality of job applications goes down drastically. I start to care less and less and that shows on my applications.

## General Preparation

- Know your shit. You have to have a good technical foundation. These recommendations are specific to DS, but applies to all roles, have a basic understanding of the material that's going to be asked of you in interviews
- For me, these two books have worked very well and I treat them like bibles during my job search, I read them every day multiple times through when I'm going through a new job application process:
    - [Ace the Data Science Interview](https://www.acethedatascienceinterview.com/)
    - [100 Page Machine Learning Book](https://themlbook.com/)
- They're high level concepts for basically 80% of all technical topics that can be asked in interviews. Read them, learn them, understand them. Keep rereading everything all the time during your interview process. It takes me roughly one week preparation to get through everything and be confident when going into interviews.
- Having said that, initial interviews will always be worse early due to rustiness, apply to jobs you care less about first, if there's somewhere you really want to work at, delay the job application until you got a few interviews under your belt.
- Have a 1 page resume, single column, ATS friendly, summary at the top, experience > skills > education order, bullet points for each thing you've achieved in a job describing what you did, how you did it, and what the result was in a data driven impact.
    - I use [ohmycv.app](https://ohmycv.app/) for generating and editing my resumes easily.
    - There's tools on the internet that style your resume and give LLM feedback why it's not optimal and how to optimize.
    - I'd even suggest to get someone professional to review it. There's services from [levels.fyi](https://www.levels.fyi) and Fiverr to get some feedback if you don't have a lot of experience in writing them. Asking someone with more experience is a cheaper way to do this.

## Finding Jobs and Applying

- Always personalize your resume to the job. THIS IS A MUST. DO NOT SKIP.
- I use this [n8n automation](https://gist.github.com/gentrexha/a761fb7b89224e7ec1cdc4b3bd041dc6) which scrapes the job description (JD) and personalizes my resume with skills and requirements from the JD.
- I don't care about motivation letters and will always leave them unfilled.
- Always apply through the job company first, don't use LinkedIn Easy Apply. Obviously if you can get a referral do that first.
- List of job portals I use:
    - [cryptocurrencyjobs.co](https://cryptocurrencyjobs.co/?query=Data)
    - [cryptojobslist.com](https://cryptojobslist.com/data?sort=recent)
    - [hiring.cafe](https://hiring.cafe/)
    - [web3.career](https://web3.career/data-science-jobs)
    - [wellfound.com](https://wellfound.com/jobs)
    - [aijobs.net](https://aijobs.net/)
    - [jobs.ams.at](https://jobs.ams.at/public/emps/)
    - [jobs.solana.com](https://jobs.solana.com/jobs?q=data)
- Make use of recruiters! Reach out to recruiting companies and send them your resume. If you want to go the extra mile: [this r/RemoteJobseekers post](https://www.reddit.com/r/RemoteJobseekers/comments/1fdpeg2/how_i_landed_multiple_remote_job_offers_my_remote/)
- SPEAK THEIR LANGUAGE. This is the most important step when personalizing resumes. Match your responsibilities, skills, technologies with the things they're looking for from the JD. Obviously don't lie blatantly saying you've worked with something that you have 0 knowledge/experience in, but for e.g.
    - If they mention supabase and you've worked postgres in the past, put Supabase on the Resume. A recruiter will leave you out of his selection because of this, because they don't know they're practically the same thing.
    - If they're looking for someone who 'solves problems consistently' write that you're a problem solver
    - If they're looking for someone who does data presentations to non-technical stakeholders, add a job bullet to multiple jobs where you've done exactly that.
- REACH OUT TO PEOPLE. This is the second most important step. Reach out to the hiring decision makers directly.
    - I do this by going on LinkedIn search searching for people using the `Current company` filter and searching for people who work there and writing to them. A simple `Hey there, saw you're looking for X, I have Y relevant experience and think I can help. Do you have 15mins this week?`. Depending on the company size, you reach out to different people:
        - **Small company:** CEO/CTO directly
        - **Medium company:** Team lead, CTO, head of tech, technical recruiter
        - **Big company:** Team Lead, Technical Recruiter
    - Cold email. Find their email by doing firstname@company.com or first.lastname@company.com - often gets to them directly
- FOLLOW UP. Always follow up after a couple days, keep track of this in your Notion so once you don't have an update for 2-4 days, write a short follow-up message.

## Interviewing

Congrats! You've made the hardest step and gotten an interview. There's always a similar path that goes for these things: `HR/Recruiter -> 1-3 Technical/Architecture/Take Home -> Cultural Fit -> Offer`. Here are a few tips that are valid before all interviews no matter which one and then we dive deeper into each.

### Before All Interviews

#### Research and Understanding Company Problems

- Research into the company, use their product if they have one, find out what they do, think about potential complex things they had to solve to get here, think about their revenue model, what do their customers look like, etc
- Understand company values, you need to reflect that you align with their values in each interview, especially early on. Understand what their values and missions are and align with those and let them know that you share those values too.

#### "Tell Me About Yourself"

- There's always the same question no matter what: `who are you, what do you do, tell me about yourself`.
- Practice it, it's always the same and should in 1-2 minutes tell a short story about who you are, how you got here (your experience), and why you think this is the job for you.
- Show research you've done into the company in the last part.

#### Salary Discussion

- Please never give a number first.
- You should always try to avoid doing so and say something along the lines: For me the most important thing is finding the right company and the right fit. I care about salary but the most important is finding the right company. Would you be able to share a rough salary range you have for this position so we know if we're in the same ballpark?
- I'd recommend always understanding their budget first, and not wasting time on interviews where these don't match. Obviously if you have nothing lined up and using them as practice can be a good idea sometimes, but that depends on you.
- Never give up the number first. You can always sell yourself short no matter how much you think you know your market value.
- This means you do not start negotiating until you already have a Yes-If. (Yes-If we agree on terms.) This is a fantastic blog post that goes into all of this in much more detail: https://www.kalzumeus.com/2012/01/23/salary-negotiation/ and this for a high level list of rules: https://haseebq.com/my-ten-rules-for-negotiating-a-job-offer/

#### Questions for Them

- The interview isn't over. This is where you can differentiate yourself from other candidates. IMO never ask about benefits, salary, perks, working hours, etc. This is where you can shine by asking the right questions. Focus on selling yourself, the interview isn't over!
- You should really spend some time into researching the company, possible DS problems they might be facing, if they have a product use it, and see what the customer journeys are. How data can help solve them? What data they might need or have had issues getting to the customer. Asking questions that show genuine understanding of their product and curiosity into what they're doing is the best way to differentiate yourself.
- Less impressive alternative: Scrape the page, scrape the job description, put it to AI - tell me some questions that show I'm genuinely curious about the product.
- Other general questions you can ask about:
    - People want to talk about themselves. How did you get here? What did you do? Just let them talk.
    - Top 3 challenges the business is facing.
    - What would be a big win for the business this year.

#### Notes and Follow-Up

- Take notes during the call. It's very impressive to have someone take those manually. Just ask is it okay if I take notes.
- But actually just use [local-ai-meetings](https://github.com/gentrexha/local-ai-meetings) for transcribing and summarizing your meetings locally and record everything from your device.
- Send follow-up email within 4 hours referencing something personal from the call that you bonded over. Keep it short, succinct, enthusiastic. You can say: I really enjoyed our talk, really nice to learn about the company and X specific issue you're facing, thank you for this opportunity, I'm very grateful, looking forward to next steps
- This keeps you top of mind and might even nudge them to a positive decision if they haven't made their assessment yet. Do this for all interviews.

In Part 2, coming soon: a deeper dive into each interview round, from the HR/recruiter screen to the cultural fit.
