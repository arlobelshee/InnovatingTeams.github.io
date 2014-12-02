### What unbelievable success looks like

There are a set of software companies and teams out there with unbelievable results. They report metrics like the following.

 * **< 1/80 person-days** # of bugs written. Bug is defined as any unexpected or non-desired behavior that could have been seen by anyone other than the developer who wrote it, whether or not it was actually seen.
 * **> 80%** Percent of bugs written that are found and fixed within an hour and before it is actually noticed by anyone other than the developer who wrote it.
 * **> 10x** Organizational productivity compared to industry norm. Produce a given piece of software in about 1/10th the cost and time of average.
 * **< 5%** Percent of total operating costs spent on tech support + operations manpower + RMA. And total operating costs remains much smaller than development costs.
 * **< 48 hours** Average time to market for a new product.
 * **< 12 hours** Average time to market for adding a new capability to an existing product.
 * **< 6 weeks** Average time for new product to deliver sufficient recurring revenue to predict fully assess market viability for a new idea. Measured from when the concept first appears to the company.
 * **< 2 hours** Average time to re-organize internal structures to respond to an unexpected new market threat or opportunity.
 * **< 8 person-days** Total lost work due to an unanticipated and extreme direction change. Even dramatic changes only impact 1-4 teams (usually 1). Total of abandoned work in progress + time to re-tool + lost work due to morale effects is less than 1/2 a team-day for the directly-impacted teams and 0 for anyone else.
 * **> +50** Staff Net Promoter for the question "would you recommend working here to a friend?"

### It is reproducible

These results have been replicated many times, in many industries and company sizes. When we look at teams with these results we see common patterns. Teams who did not have these results have adopted these patterns and gotten these results...sometimes.

There is a way of working that delivers this kind of success. But it is very different from the typical American business structure. This means our habits and culture work against us, making it hard to implement the pattern.

Those of us who have managed to change their culture find this pattern easy to live. Thus they describe this way of working as simple. But culture change is not easy. So those of us in more traditional cultures describe this way of working as impossible or obviously stupid. Both groups are right.

### But in the real world...

This all sounds great but seems impossible to most companies and teams. They have a set of constraints which (appear to) prevent them from attaining success. Or they've tried working in this approach and not gotten the promised results&mdash;and they don't know why.

Does the following sound familiar?

Kitchen Sink employs about 40,000 software developers, making every kind of software known to man. As a large company they can easily invest in emerging markets. They develop new markets to continue driving revenue off their core products.

Historically they have been very successful. They have developed efficient ways to develop software. However, they are facing new competition.

They are no longer fighting against other large companies. Instead there is a marketplace of tiny companies that bring narrow products to market quickly.

No one product threatens Kitchen Sink, but the set of all the products creates an ecosystem that innovates faster than Kitchen Sink both in existing markets and in discovering new markets.

Kitchen Sink is not dumb. They know how these little companies are working and have tried to do the same. There are many Agile teams in Kitchen Sink already. They have automated testing and delivery. They use Lean concepts to manage cross-team work. They have read Lean Enterprise and developed data analysis groups to help understand customers better.

Each part helped a little, but successes tended to be local and small. While small companies report 500% improvements in productivity, Kitchen Sink keeps getting 20% improvements. They have almost given up, almost assumed that big enterprises are just always slower than small companies.

And they are stuck.

Kitchen Sink wants to run experiments to learn about its customers. They want to use the lessons of Lean Startup&mdash;validated learning, customer development, and persevere or pivot decisions.

However, they can't run experiments, for a bunch of reasons:

* They have a successful brand. They can't risk releasing products which would harm that brand.
* Every time they change the product they introduce bugs. These bugs take time to find and fix. This means their minimum product cycle is too long for real experimentation.
* Their products have a lot of cosmetic bugs. These cause user frustration and confusion. Since frustration and confusion have more impact on user behavior than product capabilities, their data would be too messy. A slight difference in cosmetic bug between two versions would overwhelm any difference they might have seen between the two variations they were trying to test.

These problems are all product issues. Kitchen Sink sees value in fixing them. However, they are already being out-innovated by their competitors. They can't afford to slow down to fix these problems because they will go out of business.

They do know about TDD. They've heard that it allows them to pay off technical debt over time. They have also heard about refactoring, but probably under its watered-down, less useful definition. So they don't see exactly how it is possible to pay down a little technical debt in 2-3 minutes as part of regular work, but they know that an incremental approach is used by other companies.

They also know that any attempt to pay technical debt would require a new way of working. The technical results they are getting today are a result of the team systems they use today. To get different results, they will need a different system.

And they can't just change the way they work. No one in the company has the power to really make a real change. Furthermore, working in this new way would require a lot of new learning. And learning is expensive at Kitchen Sink.

Kitchen Sink can't address the technical debt because:

* The company is organized hierarchically, by function. This means that getting anything done requires cooperation from multiple parts of the organization. This also drives decisions to have to be made by management. Individual contributors simply don't have access to all the right people to get anything done.
* They've got a lot of specialists who have a decade or more of experience at their current job. Regaining that expertise would require another decade.
* The company isn't a strong learning organization. The hierarchy traps knowledge in the minds of individuals. Some knowledge moves around between co-workers in a function. However, since people can't share work, knowledge only really moves via formal training and occasional mentorship. Both are inefficient ways to learn.
* Managers are overwhelmed. There are too many details for them to handle, so they make decisions based on summary data. It takes a long time to make a decision because individuals have to wait for a manager's calendar to open up.
* Managers are held accountable for the results of their products. However, most of the execution is done by individual contributors. Since most of the outcome of any product has to do with the execution and not the decision, managers are accountable for something outside of their control. Therefore, managers attempt to control how work is done so they can meet their accountability.
* Individual contributors know better ways of working. But changing to those would require learning and cooperation of their peers. This is a risk. They are very likely to appear ineffective in their first year, which may cost them their jobs.
* Managers can't cause a change because the thing that has to change is the moment-to-moment behavior of individual contributors (ICs). That behavior is not visible to management.
* ICs can't cause a change because they can't easily get alignment with other ICs and they can't take the risk of looking bad at annual review.
* The only way for the company to change direction is for it to re-org. Changing product mix requires changing reporting structures. This happens often so it isn't worth any one team improving itself much.

People have tried to fix these problems. They've even fixed some of them for individual teams. But all these improvements are temporary. Within a year or two a manager will be replaced or the team will be changed in a re-org and they will have to start all over.

Kitchen Sink needs a systemic change. They need to be able to make local improvements that also improve the company as a whole and provide a smooth migration path from its current structure and culture to a new and more effective one.

They see what they need to accomplish. They understand their problem. They are aware of the common solutions. They've just been unable to solve it.

### The success pattern

The most effective way to build software today is:

 * **Work together** in teams. Share not just the planning but the actual work.
 * **Learn constantly** across the organization. Your rate of learning is your limiting constraint.
 * **Prove it** at every step. Never let a mistake linger to increase risk or corrupt your data.
 * **Refactor everything**. Reduce the cost and risk of change to both your product and your process so you can incorporate learning.
 * **Use data** to validate your learning. Run experiments to guide your changes.

The specific practices used to implement this pattern vary. New techniques become available as skill improves and the environment changes. Each practice becomes obsolete as new options become possible. But teams can't just start with the final practices because those require a culture and set of skills that are not yet in place.

Innovating Teams has seen these skill progressions. We can help you implement real teams that deliver unbelievable results.

### How teams get there

We have observed that teams tend to follow a standard progression, whether they receive outside coaching or not. Teams follow this same trajectory regardless of business domain or company size. Team-specific context changes only two things: the detailed practices they implement to achieve each step and how far they need to progress in order to succeed.

This happens because:

 * Everyone wants to be a **Lean Startup/Enterprise** using **validated learning** to direct their products and processes. That learning comes from **running experiments**. However,
 * Experiments require a **low cost of change**, a **low cost to revert**, and **extremely high quality**. Wins come from accumulating small gains. Each experiment discovers a subtle advantage for one option. High quality is required to be able to detect the subtle signals; low cost is required to allow us to run many experiments. However,
 * Current products have high cost of change and low quality: **technical debt**. No team can afford to stop production and pay off technical debt. They need to pay technical debt incrementally without slowing down production or introducing bugs. This requires a process change. However,
 * The company suffers from **process debt**. Reporting structures, processes, meetings, and traditions all reinforce today's ways of working. It is hard to learn new approaches, expensive to agree on changes or run experiments, and difficult to tell if any given change had positive impact.

Teams tend to start at the bottom and work their way back up this progression. They stop when either the environment doesn't let them progress further or their current way of working meets business needs.

### We can help

You own your growth along this trajectory. We can speed you up and decrease cost and risk. We can help with 5 phases of your ongoing transformation:

1. Create **learning teams**. Create high-performance teams that get better every day. Techniques include:
 * Structure organizations for success. Create single-assignment, cross-functional teams.
 * Align teams using chartering, performance chain analysis, and champions network.
 * Help teams share work and learning via mobbing and pair programming.
 * Train managers in servant leadership. Train individual contributors in consent-based decision-making and team accountability.
 * Teams drive their own experiments and habit changes via retrospectives.
 * Visualize the work via iterative (Scrum boards), continuous (Kanban, value chain), or plan-driven (phase-gate, spiral) approaches.
 * Visualize the process via working agreements, simple rules, value chain, cross-team interaction agreements, and failure demand metrics.
 * Enable change by Anzaneering&mdash;intentionally identifying forces and systems that threaten personal safety and fixing them.
 * Identify and leverage points of resistance&mdash;structural or people&mdash;to keep your changes focused on what your business actually needs.
2. Get **legacy code** under control. Pay off technical debt incrementally, without spending productivity or introducing bugs. Techniques include:
 * Make atomic, known-safe changes via mechanized refactoring.
 * Extract the spec from existing code via acceptance and unit testing.
 * Create new code spec-first via test-driven development.
 * Gain single- and multi-team alignment with legacy code strategies.
 * Visualize progress with legacy code metrics and visualizations.
3. **Ship at will**. Attain continuous delivery or whatever shipping cadence matches your market. Techniques include:
 * Automate everything in your build and ship process.
 * Enable either versioned or progressive release, with automated rollback in either case.
 * Enable zero-downtime deployments.
 * Leverage your specs to automate verification.
 * Simplify tools to reduce cost of release and operations.
 * Script and automate operations to attain a DevOps or NoOps approach.
 * Visualize success with release metrics and visualizations.
4. **Validated learning**. Plan based on data and change plans easily. Run experiments to deeply learn about your customers. Techniques include:
 * Define valid experiments.
 * Replace backlogs and other plans with data to reduce the amount of time spent building the wrong thing.
 * Enable cross-team data sharing to enable decentralized, global optimization.
 * Visualize validated data with models.
 * Understand the market with business and customer behavior metrics.
5. Create a **learning organization**. Create an innovation network from your learning teams that learns constantly and adapts to changing business circumstances. Techniques include:
 * Use Working Out Loud to enable informal cross-team collaboration and alignment on product and process, and to enable discovering new potential partner teams.
 * Create a culture of collaboration via decentralized champions and catalysts.
 * Create an innovation network by enabling temporary multi-team relationships via contracting.
 * Visualize learning with information spread and innovation metrics.

### Consulting / Coaching services

**Arlo Belshee**, our Lean/Agile Coach and Team Craftsman, is available to help you transform your organization. He has 15 years of experience with Agile and Lean software development in companies ranging from 3 to 120,000 employees. he has helped dozens of organizations and work groups become high performance teams.

If your team is willing to be the best&mdash;and put in the effort it takes to get there&mdash;Arlo can show you how.

### Tooling

Teams share some common tooling gaps. We are building tools to address those needs. All tools are designed to integrate well with your existing tools. We don't force teams to transition toolsets; we provide options they can use to enhance their own work.

We are currently building the following tools.

* **Destiny** helps teams own their destiny. Teams can track experiments and habit changes and see improvement over time. Metrics allow teams to gain credit from managers for learning from both successful and failed experiments.
 * Maintain your current team charter. See all your agreements in one place. Ramp up new hires faster and keep managers aware of how you work.
 * Easily define experiments or habit changes using our templates.
 * Search for other teams that have encountered the same problems you are having and see what experiments they ran and what results they got.
 * Search your own team's experiment history to show what you have learned and recall the results of long-ago experiments.
 * Report on experiment outcomes in a consistent, simple format so that managers can see your team's improvement and reward it.
 * Track long-term effects of habit changes to ensure that your habits stick and your processes continue to deliver value.
 * Report on habit changes and long-term improvements to management.
 * Guide your retrospectives, keeping them on track to deliver experiments and habit changes&mdash;real change.
 * Maintain and improve system models over time. Progressively develop understanding of how your team works and fails so that you can make more effective changes.
* **Who's  on it?** helps anyone in the organization understand the organization as a whole. It dynamically shows your current innovation network so that you can see who is doing what and who is partnered with whom on what.
 * Teams manage relationships via lightweight interaction agreements.
 * Measure health of relationships via metrics against the agreements.
 * Team members and managers alike can see when relationships are missing or need improvement. People can decide where to optimally spend attention.
 * Search by topic to see which teams are actively working on that topic.
 * Integrates with Yammer to search in-team and cross-team discussions for topics.
 * Get reminded about relationships which have served their purpose so they can be officially dissolved and free the teams to innovate independently.
 * Discover areas of the product or process where consistency is more valuable than innovation. Collaboratively come to agreements over time to optimize the whole network.
