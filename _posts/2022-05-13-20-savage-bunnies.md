---
layout: post
title: Savage Bunnies
---

Hi folks, welcome to **War(un)lock blog #20**! I'm enjoying the spring with a vacation to the southeast and avoiding the horrible, cold rain that had plagued NYC until recently. It's time to pack the winter coats and unpack the antihistamine medication.

I couldn't think of a good title for this month's blog post, but [a Kickstarter that I had funded in late 2020](https://www.kickstarter.com/projects/1260269319/mostly-monsters-the-art-of-allison-theus) had finally arrived in the mail a week ago! I had followed the artist and her work for almost 10 years, and I was super excited to finally buy a book collating all the illustrations I've seen in her blog. Plus, the extra set of savage bunny stickers were icing to the monstrous cake!

<div style="text-align:center"><img src="/images/blog20/blog20-kickstarter.jpg" width="350"></div>

### What I’ve been up to

Over the past month, I took some vacation to visit the Research Triangle are of North Carolina - Raleigh, Durham, and Chapel Hill. I enjoyed hiking among the many national parks, learning about the state's history through museums, and eating a lot of good food. (There were even whiskey flights in one restaurant, but I didn't want to get a hangover during my trip.)

As per tradition (established by previous years of domestic and international trips where I've run into SO many board game shops), I've visited Game Theory in Raleigh. I was super excited to get a copy of a TTRPG called [Blades in the Dark](https://www.evilhat.com/home/blades-in-the-dark/), where you play as a band of criminals in a ghost-punk setting. The staff also geeked along with me and recommended [Coyote and Crow](https://coyoteandcrow.net/), another TTRPG set in an alternative reality where European colonialism never happened.

But of course, nothing feels as great as returning home with some [BCD Tofu House](https://www.bcdtofuhouse.com/) leftovers and cuddling with a cute cat. (Even if he tries to get me off of my office chair so he could nap in it for a few hours.)

<div style="text-align:center"><img src="/images/blog20/blog20-bobbit_hole.jpg" width="350"><img src="/images/blog20/blog20-heron.jpg" width="350"></div>

<div style="text-align:center"><i>Exploring Eno State Park in Durham.</i></div><br />

<div style="text-align:center"><img src="/images/blog20/blog20-fried_fish.jpg" width="350"><img src="/images/blog20/blog20-tiny_houses.jpg" width="350"></div>

<div style="text-align:center"><i>Fresh fried fish outside and tiny houses in the woods.</i></div><br />

<div style="text-align:center"><img src="/images/blog20/blog20-pope_house.jpg" width="350"></div>

<div style="text-align:center"><i>The Pope House. It was closed when I passed by it, but I definitely want to check it out on a future visit!</i></div><br />

### What I’ve learned

I was listening to some [Sawbones podcasts](https://maximumfun.org/podcasts/sawbones/) for informational humor as I passed the time during traveling. I learned a lot about how much medicine is happenstance, then establishing standards based on what worked. I didn't have quite a lot of time to research on a particular topic this month. BUT in future blog posts, I may use them for inspiration for the next `What I’ve learned`!

<hr />

Are you interested in how a tech lead, product manager, and engineering manager tackle a massive project and magically translate it into tickets? Why are they seemingly obsessed with managing all that documentation anyhow?

Well, it’s not the most interesting topic, but I find it enlightening on the whole process. If done right, **the work breakdown process** should be invisible to the software engineer. If done wrong, the results of work breakdown will become the ire of the software engineer.

#### Background

In short, knowing how to distill a large and complex project heavily depends on your understanding of both the business use case and the tools available to build the actual product. Software engineering (and really engineering in general) is hard because it involves designing and implementing software based on constraints. It’s easy to create different software designs that can *technically* work for the business use case, but it’s difficult to pick the best one that is cheap, extensible, resilient, and easy to implement.

Work breakdown takes experience and practice to get because it involves communication, systems design, coding experience, curiosity, and a whole lot of writing. It’s a big problem, but work breakdown ultimately boils down to a “divide and conquer” method. And yes, this process involves a lot (and I mean A LOT) of documentation. There is so much information to organize and distill that some details may get lost in the storm. Also, documentation provides a form of communication that can be spread en masse and asynchronously.


#### Team roles

So what’s typically in an engineering team? YMMV between engineering organizations, but so far, the common theme is:

- The **engineers** are the bread and butter of the team. They take a ticket and are able to deliver work based on the requirements outlined in the ticket. Ideally, they should be able to work without blocking each other, and collaborate to knowledge share.
- The **tech lead** acts as the engineering ATC, making sure that the team is not blocked from a technical perspective. (For example, a broken CI pipeline or linter can really slow down delivery!) They also act as the eyes and ears between the engineers and the team leadership. Finally, they determine what tech stack the team should use - provide the a toolbox of vetted out tools for the rest of the team to use.
- The **engineering manager**, by contrast, acts as the people ATC. They act as the shield of the team against the onslaught of paperwork and politics that could otherwise slow down the team. They also make sure each team member has the opportunity to achieve their professional goals. Finally, they mediate between the needs of the business with the interests of the engineers.
- Finally, the **product manager** helps sift through messy business requirements into concrete product requirements that the engineering leadership can break down into technical requirements. It saves the rest of the team from talking to strangers.

For the team leadership, the client is usually external to the team. The product manager is the liaison between the team and the external client.

For the engineers within the team, the team leadership should act as the client. That also means the team leadership should understand the project well enough to explain the use case and requirements based on the context.

#### How do?

Now that we’ve talked about the purpose of work breakdown and team roles, let’s go through the steps of work breakdown. I come from a perspective of a tech lead who also needed to dabble in product management and people management, so these steps are more holistic but shallow in parts.

I want to mention that junior and mid-level engineers *shouldn’t* worry about learning the process. It’s good to get a peek of the process, but this is also non-trivial work. Always ask for clarification if requirements aren’t clear - grooming is hard work.

##### 1) Talk to your client.

- Do you understand the **business use case**? Do you understand why the choices were made?
- **Who is your client?** Who can you contact for further questions?
- Is there **documentation** to reference? Is the documentation trustworthy?

##### 2) Understand your constraints.

- What does your **client expect** from the project?
- Do you understand the **tools available** to you? Are you using familiar technology, or dabbling with new technology?
- **How much time** do you have to deliver the project?
- What **kind of rapport** do you have with your client? The client can help you immensely with supporting you, or become the bottleneck.

##### 3) Based on your constraints, propose a technical design, or some designs.

- What **tradeoffs** does your design have? Does it align with the business requirements?
- Can you explain your technical design to people with **various degrees of technical expertise**? [The C4 model](https://c4model.com/) is helpful to frame your design in different lenses.
- What sort of **risks** does the design have, and are they worth having?
- Does the design account for any **collaborating systems or teams**?
- Does the design account for **technical debt** in the future? Some designs are an intermediary step to a larger goal, or is the result of duress.

##### 4) Based on your technical design, break down the work into manageable chunks.

- The design should be **compartmentalized** such that work can be broken down without too much coupling. Like threading, a software engineering team should be able to work on tickets **without blocking each other on coupled work**.
- **Break down work** like the C4 model. Break down the work into components, then sub-components, until each ticket represents less than a sprint’s worth of work. There should be a **variety of work** for a diverse team of engineers to pick from.

##### 5) With your tickets, add the content.

- The ticket should give a **background** of why this ticket was created. We’ve now distilled this work from the big audacious goal, so we should circle back to make sure it’s not diverging from the goal.
- The ticket should also have **acceptance criteria**, or what requirements are needed for the ticket to be considered “completed”.
- The ticket **should NOT have implementation details**. That’s what the software engineer’s job is for - they are trusted to build the software based on the requirements. They know what they have available to build the thing, be able to ask questions if they don’t know, or raise a flag if there’s an obstacle involved.
- The ticket should be written so that **the assigned engineer should ONLY manage its status** and maybe writing comments. They shouldn’t be worried about how to manage tickets - otherwise, they’ll have to more time managing tickets and less time doing work.

At this point, work breakdown has been completed. **Let’s relish in the fruits of our labor!**

##### 6) Deal out the tickets to the team in order of priority.

With the tickets now groomed and ready to be tackled, they can now **be dealt to the team**. The tickets should be ordered in terms of priority and logical order, then allocated a value based on time and complexity of work. The engineering manager should make sure the tickets are distributed based on engineer interest and capabilities, as well as PTO.

#### That’s a wrap

Work breakdown is definitely not a glamorous job in the perspective of a typical software engineer. It’s glue work that ensures that the team works effectively. When done right, it’s easy to notice when it’s done wrong!

### A chapter closed

Thank you for reading this blog post!

If you have any questions, feedback, etc. - don’t hesitate to send an email through [susanna@warunlock.com](mailto:susanna@warunlock.com)!

Please stay safe, and take care!


