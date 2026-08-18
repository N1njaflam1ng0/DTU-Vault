> Deck note (p.1): three kinds of slides - normal ones gone through in the lecture, 'study at home' reading references, and hidden slides (exercises and answers, which is why the numbers don't add up). **You must be able to calculate a critical path and a PERT estimate.**
> Textbook: DS Handbook 185:2022, *Doing Projects*, ch. 6 (Complexity, pp. 127-147).

#### Typical complexities in projects
![[Complexity-slides-Jan-2023.pdf#page=5&rect=25,60,940,470|Complexity-slides, p.5]]
Six kinds, and they are not the same problem: technical/task, time, goal, social, organizational, legal.

The move that runs through the whole lecture: **complexity is managed by creating structure**. Each type of complexity has its own structuring tools.

![[Complexity-slides-Jan-2023.pdf#page=6&rect=25,35,940,505|Complexity-slides, p.6]]
- **Technical/task** - Work Breakdown Structure, systems mapping. *How are tasks dependent on each other? What is needed to start a task? What can and cannot run in parallel?*
- **Time** - scheduling/Gantt, milestones, critical path analysis. *How long does it take? When must I start to finish in time? When will I need others?*
- **Goal** - prioritizing, sequencing. *What objectives absolutely must be met? Are objectives in conflict? How do goals build on each other?*

![[Complexity-slides-Jan-2023.pdf#page=7&rect=25,35,940,505|Complexity-slides, p.7]]
- **Social** - stakeholder management, managing your client, managing the team. *Are there conflicts of interest? Misalignments of goals, values, understandings?*
- **Organizational** - resource scheduling, reporting requirements. *Do you have to coordinate resource access? Are others depending on your results? How to integrate the result into the organisation?*
- **Legal** - contracts, data management plan, NDAs. *What legal requirements apply? What are your contractual obligations?*

Note that the social and legal columns are where Complexity hands over to People and to Contracting later in the deck.

#### Hierarchy as the answer to complexity
![[Complexity-slides-Jan-2023.pdf#page=8&rect=25,35,940,505|Complexity-slides, p.8]]
Simon (1962): complex systems that survive are the ones built from stable sub-assemblies. Decomposition is not just a convenience for the planner - it is what makes a complex thing buildable at all.

![[Complexity-slides-Jan-2023.pdf#page=9&rect=25,35,940,505|Complexity-slides, p.9]]
The Lego exercise (Eilers, 2005): six 2x4 bricks of the same colour combine into **915,103,765** figures. Six identical elements, nearly a billion configurations - the point being that combinatorial complexity explodes long before the number of components looks alarming.

#### Systems thinking
![[Complexity-slides-Jan-2023.pdf#page=10&rect=25,35,940,505|Complexity-slides, p.10]]
Four ideas:
- **Boundaries** - what is inside the system, what is environment, and where the interface sits
- **Hierarchical principle** - systems contain sub-systems contain elements
- **Black boxes** - you deliberately don't look inside; you specify input and output
- **Relationships** - between elements, and across the boundary

The black box is the practical trick: you can only delegate a chunk of work if you can treat it as a box with a defined input and output.

#### Dependencies
![[Complexity-slides-Jan-2023.pdf#page=11&rect=25,35,940,505|Complexity-slides, p.11]]
Three types, in increasing order of coordination cost:
- **Pooled** - each part is done independently and assembled. Fx each student writes a section of the report and it is put together.
- **Sequential** - one delivery builds on the previous one.
- **Reciprocal** - the parts shape each other continuously. Fx the beginning of a project, defining the collaboration agreement.

This classification comes back twice: it decides which planning method fits (p.67), and it is what "integrating" means in the summary.

#### Agenda: core practices
![[Complexity-slides-Jan-2023.pdf#page=13&rect=25,60,940,470|Complexity-slides, p.13]]
Scoping (how to do it) → Estimating → Timing (when) → Resourcing (how much) → Improving (can we make it better) → Contracting (make or buy) → Connecting the dots.

"If you fail to plan, you are planning to fail." (Benjamin Franklin, p.12)



## Scoping - How to do it?

#### Scope and quality according to ISO21502
![[Complexity-slides-Jan-2023.pdf#page=15&rect=25,50,940,490|Complexity-slides, p.15]]
The purpose of scope management is to facilitate the creation of the deliverables, outputs and outcomes to achieve the stated objectives of the sponsoring organization or customer.
Activities:
- 7.4.2 Defining the scope
- 7.4.3 Controlling the scope
- 7.4.4 Confirming scope delivery

The purpose of quality management is to increase the likelihood that outputs are fit for purpose or use. Quality should be an integrated part of the project's plan.
Activities:
- 7.11.2 Planning quality
- 7.11.3 Assuring quality
- 7.11.4 Controlling quality

#### The breakdown starts at the purpose
![[Complexity-slides-Jan-2023.pdf#page=16&rect=25,35,940,505|Complexity-slides, p.16]]
The goal hierarchy: organisational strategy and the purposes of other stakeholders feed the project vision, which then breaks down into *what*. Scoping is the continuation of the Purpose material, not a separate exercise - you break down a purpose, not a blank sheet.

#### Goals-oriented vs work-oriented scoping
![[Complexity-slides-Jan-2023.pdf#page=17&rect=25,50,940,490|Complexity-slides, p.17]]
- **Goals-oriented**: makes the purpose more concrete while not limiting flexibility; delegates ownership and motivates; helps create a shared view among different stakeholders
- **Work-oriented**: fits routine tasks or low uncertainty; useful for an inexperienced team - though good practice is still to develop the work breakdown *together with* the people responsible for the work

#### Work Breakdown Structure
![[Complexity-slides-Jan-2023.pdf#page=18&rect=25,50,940,490|Complexity-slides, p.18]]
*Study at home.* WBS: "decomposition of the defined scope of a project or programme into progressively lower levels consisting of elements of work" (ISO 21502). It creates the backbone of the project and the overview of the work to be done, and is used to develop the schedule, resource requirements and cost.

Level of detail: hard to state in general - it depends on phase and project size. It must be detailed enough to allow scheduling, monitoring and budget control. Rule of thumb: the **8-to-80 rule** (a work package takes 8 to 80 hours). A work package is a group of related tasks - the smallest unit the project is broken down to, and small enough that it looks like a mini-project itself.

![[Complexity-slides-Jan-2023.pdf#page=19&rect=25,50,940,490|Complexity-slides, p.19]]
*Study at home.* A WBS is about the *work*. Related but different structures: functional breakdown (IT, legal, marketing, R&D), organisational breakdown structure (OBS), risk breakdown structure (RBS), product breakdown structure (PBS). They look alike but are not the same thing. In practice it is often useful to connect the WBS to the OBS by naming the person, department or subcontractor responsible for each area.

![[Complexity-slides-Jan-2023.pdf#page=20&rect=25,45,940,495|Complexity-slides, p.20]]
*Study at home.* How to make one: invite relevant stakeholders (for buy-in and for the information), identify the goal, identify deliverables, identify the activities needed for each deliverable. It is iterative - ask *why* going up and *how* going down until the WBS is stable.

How to evaluate one:
- Is it comprehensive?
- Is the level of detail appropriate? (Be accurate but not necessarily precise.)
- Are there significant clashes with organisational settings?
- Are there *reciprocal* dependencies between level 1/2 areas? (If so, the decomposition is wrong - you have cut through a tightly coupled system.)
- Is it deliverable-oriented rather than task-oriented? You may not be the right person to know which activities are required, but you can define deliverables and objectives at a higher level.

![[Complexity-slides-Jan-2023.pdf#page=21&rect=25,35,940,505|Complexity-slides, p.21]]
![[Complexity-slides-Jan-2023.pdf#page=22&rect=25,35,940,505|Complexity-slides, p.22]]
Worked example: the copper mining project (Lock 2007, pp. 167-8).

![[Complexity-slides-Jan-2023.pdf#page=23&rect=25,35,940,505|Complexity-slides, p.23]]
Four visualizations of the same WBS: outline, hierarchical structure, tree structure, tabular structure. Same content, different readability - the tree sells it to stakeholders, the outline is what you actually work in.

#### WBS Dictionary
![[Complexity-slides-Jan-2023.pdf#page=24&rect=25,50,940,490|Complexity-slides, p.24]]
"Document that describes each component of the WBS" (ISO 21500). It defines each work package and can be considered a mini scope statement: description, deliverables, activities, milestones, cost, level of effort, resources assigned, responsible.

#### Case: scope of super hospitals / Eurovision venue
![[Complexity-slides-Jan-2023.pdf#page=25&rect=25,35,940,505|Complexity-slides, p.25]]

![[Complexity-slides-Jan-2023.pdf#page=26&rect=25,45,940,495|Complexity-slides, p.26]]
The Eurovision scoping problem: 37 participating countries, broadcast in around 40, 170 million viewers, 1500-2000 accredited press and more than 10,000 accredited altogether. Against that, the venue options ranged from Messe C in Fredericia (8,000) through Jyske Bank Boxen in Herning (15,000) and Parken (50,000) to the B&W Sektionshal and a tent at DR Byen (10-15,000). The requirement drives the venue, the venue drives everything else - and the chosen option was the one with the least existing structure.

Reflection: how is the scope in your case defined - goal breakdown or work breakdown? Was it defined by the project team and stakeholders? Was it comprehensive?



## Estimating - How long and how much?

#### Estimating in ISO21502
![[Complexity-slides-Jan-2023.pdf#page=29&rect=25,60,940,470|Complexity-slides, p.29]]
Estimating is not a clause of its own - it sits inside schedule and cost:
- 7.6.2 Estimating activity durations
- 7.7.2 Estimating cost

#### Top-down vs ground-up
![[Complexity-slides-Jan-2023.pdf#page=30&rect=25,35,940,505|Complexity-slides, p.30]]
Two directions (Maylor 2010, p.177). Top-down starts from the whole and apportions; ground-up starts from the work packages and sums.

![[Complexity-slides-Jan-2023.pdf#page=31&rect=25,60,940,470|Complexity-slides, p.31]]
The exercise: where in the life cycle do you use each? Early, when there is no WBS and you need a figure for the business case, only top-down is possible. Ground-up becomes available once the work is broken down - and becomes the basis for control.

#### Approaches and techniques
![[Complexity-slides-Jan-2023.pdf#page=32&rect=25,45,940,495|Complexity-slides, p.32]]
Techniques: historical data, parametric, "as… but…s" / analogy (similar projects, fx reference class forecasting), expert judgement, calibrated estimation (a 90% confidence interval - a range you are 90% sure contains the right answer), learning curve, and **wishful thinking**.

Things to consider:
- Rapid, rough and right - **roughly right beats precisely wrong**; detail increases over time (the rolling wave again)
- Three-point estimates, qualitative understanding, thinking of alternatives
- The best techniques are still only estimates
- One size does not fit all: the level of precision depends on the project

![[Complexity-slides-Jan-2023.pdf#page=33&rect=25,40,940,500|Complexity-slides, p.33]]
*Study at home.* The techniques in detail:
- **Parametric** - based on parameters such as square metres or tons of steel, at any level of detail. Projects are rarely wholly unique; the lower levels of the WBS usually repeat.
- **Expert judgement** - one or more experts predict cost or time, iterating until consensus (Delphi). Cheap and can be accurate if the experts have direct experience of similar projects; very inaccurate if there are no real experts. Danger: the rough estimate becomes the target time.
- **Analogy / as…but…s** - compute by comparison with a similar project in the same domain. Needs a systematically maintained cost/time database; impossible if nothing comparable has been done.
- **Forecast** - a best guess under uncertainty (fx exchange rates). Use parametrics or proxies, separate fixed from variable costs, provide a series of estimates to see the impact on the budget, and factor in an element for risk.
- **Learning curve** - repeated tasks get faster as the person becomes familiar with the method, with the improvement in speed shrinking over time.
- **Wishful thinking** - optimism bias, politics (large figures are unacceptable, so the objective is placed above cost), improper use of estimates (ball-park figures become official without checking), and failure to be systematic (vagueness, an unqualified estimate to get the request off the desk).

![[Complexity-slides-Jan-2023.pdf#page=34&rect=25,35,940,505|Complexity-slides, p.34]]
The learning curve on time taken (Maylor 2010): steep at first, then flattening.

#### The estimation trap
![[Complexity-slides-Jan-2023.pdf#page=36&rect=25,60,940,470|Complexity-slides, p.36]]
Rough estimates become committed target times - and estimates usually contain large safety margins. Both at once: the estimate is padded *and* treated as a promise, which is the worst of both.

![[Complexity-slides-Jan-2023.pdf#page=37&rect=25,45,940,495|Complexity-slides, p.37]]
Politics reinforce optimism bias (Flyvbjerg, Bruzelius and Rothengatter, 2003):

understated costs + overstated benefits + understated environmental impact + overstated economic impact = **project approval**

The bias is not a cognitive accident - it is selected for. Projects that estimate honestly do not get approved, so the approved population is systematically the over-optimistic one.

![[Complexity-slides-Jan-2023.pdf#page=38&rect=25,35,940,505|Complexity-slides, p.38]]
The recommended cost uplifts by project type (Maylor 2010) are the correction: instead of trusting this project's estimate, apply the historical overrun of its reference class.

#### PERT
![[Complexity-slides-Jan-2023.pdf#page=39&rect=25,50,940,490|Complexity-slides, p.39]]
An approach to factor risk into the schedule using a three-point estimate:

$$\text{PERT} = \frac{o + 4m + p}{6}$$

where $o$ = optimistic, $m$ = most likely, $p$ = pessimistic.

The slide's example: $o = 8$, $m = 10$, $p = 24$ workdays.
$$\text{PERT} = \frac{8 + 4(10) + 24}{6} = \frac{72}{6} = 12 \text{ days}$$

You then use **12** days on the network diagram instead of 10. Note what the weighting does: the most likely value carries four sixths, but a long pessimistic tail still pulls the answer up. Skew in the estimate becomes visible in the schedule.

#### Summary
![[Complexity-slides-Jan-2023.pdf#page=40&rect=25,60,940,470|Complexity-slides, p.40]]
- Estimations are the basis for project selection and planning
- Estimations are guesses; techniques only help us make *educated* guesses
- Estimation discipline is fundamental
- Even unconsciously, estimates are built on unrepresentative experience
- Estimations are political
- Estimations usually include large safety margins
- The estimation trap: rough estimates become committed target times

#### Case: cost of super hospitals
![[Complexity-slides-Jan-2023.pdf#page=41&rect=25,35,940,505|Complexity-slides, p.41]]
Initial vs revised: total size 254,740 → 183,750 m², new construction 197,340 → 126,350 m². Economy (B DKK): new construction 6.0 → 4.0, refurbishment 0.4 → 0.3, parking 0.3 → 0.3, equipment 1.2 → 0.7. Cost per m² 28,884 → 27,000.

Read the numbers together: the cost per square metre barely moved, so the budget was not met by building more cheaply - it was met by **building less**. Scope absorbed the estimating error.

#### Case: the Health Platform
![[Complexity-slides-Jan-2023.pdf#page=42&rect=25,45,940,495|Complexity-slides, p.42]]
The Capital Region started using the system although it was unfinished and full of errors and omissions; without adequate tests; without adequate user training; with inadequate commissioning planning; with overly optimistic expectations about how long activity would decline (3 weeks expected, still declining at several hospitals 1½ years later); with overly optimistic expectations of the gains (2 years on, the region still could not follow up on its own targets for benefit realization); and without using available knowledge from abroad and from consultancies in assessing the business case (Rigsrevisionen / Public Accounts Committee, 2018).

Reflection: what estimation techniques were used, where and why? Were the estimates accurate? What were the consequences? Was the business case too optimistic?



## Timing - When to do it?

#### Project life cycles
![[Complexity-slides-Jan-2023.pdf#page=46&rect=25,40,940,500|Complexity-slides, p.46]]

| | Predictive | Adaptive |
| --- | --- | --- |
| Models | Sequential, waterfall, stage-gate, (concurrent/parallel) | Cyclical, spiral, agile, iterative, code-and-fix |
| Foci | Discipline, controllability, linearity; speed if concurrent | Learning, flexibility, change |
| Phases | Sequential (waterfall) or overlapping (concurrent) | Sequential, overlapping or parallel |
| High-level planning | Yes | Yes |
| Detailed planning | At the beginning, or rolling wave | Only per phase or iteration |
| When used | Outcome well understood; large and complex projects; need for fast completion (concurrent) | Outcome not well understood; rapidly changing environments |
| Customer involvement | Beginning, at scope changes, and project end | Continuous |

Note that *high-level* planning is "yes" in both columns. Adaptive does not mean unplanned - it means the detail is deferred.

#### Types of plans
![[Complexity-slides-Jan-2023.pdf#page=47&rect=25,50,940,490|Complexity-slides, p.47]]
- **Activity-oriented plans**: t > 0, activities, an *interval* in time
- **Event-oriented plans**: t = 0, milestones, a *point* in time

A milestone has no duration, which is exactly why it is useful for control - it cannot be 60% done.

#### Planning methods
![[Complexity-slides-Jan-2023.pdf#page=48&rect=25,35,940,505|Complexity-slides, p.48]]
**Double diamond** - diverge then converge, twice: first on the problem (discover, define), then on the solution (develop, deliver).

![[Complexity-slides-Jan-2023.pdf#page=49&rect=25,35,940,505|Complexity-slides, p.49]]
**Kanban** - a board of columns, work pulled through, with limits on work in progress.

![[Complexity-slides-Jan-2023.pdf#page=50&rect=25,35,940,505|Complexity-slides, p.50]]
**Scrum** - fixed-length sprints, backlog, daily stand-up, review and retrospective. (Intro video on p.69.)

![[Complexity-slides-Jan-2023.pdf#page=51&rect=25,35,940,505|Complexity-slides, p.51]]
**Gantt chart** - activities as bars against a time axis; the classic activity-oriented plan.

![[Complexity-slides-Jan-2023.pdf#page=52&rect=25,35,940,505|Complexity-slides, p.52]]
**Milestone planning** - the event-oriented counterpart: what state must be reached, not what work is done.

![[Complexity-slides-Jan-2023.pdf#page=53&rect=25,35,940,505|Complexity-slides, p.53]]
**Location-based scheduling** - time against *place* rather than against activity. Used in construction, where the constraint is that two trades cannot occupy the same location at once.

#### Scheduling according to ISO21502
![[Complexity-slides-Jan-2023.pdf#page=54&rect=25,50,940,490|Complexity-slides, p.54]]
The purpose of schedule management is to enable work to be undertaken in a timely manner and to reduce slippage to an acceptable level. The schedule should be an integrated part of the project's plan and developed under the direction of the project manager.
Activities:
- 7.6.2 Estimating activity durations
- 7.6.3 Developing the schedule
- 7.6.4 Controlling the schedule

#### The scheduling process
![[Complexity-slides-Jan-2023.pdf#page=55&rect=25,40,940,500|Complexity-slides, p.55]]
*Study at home.* Five steps:
1. **Identify activities** - via the WBS, which connects purpose with activities and builds the backbone
2. **Estimate times and resources** - bottom-up, comparative, parametric, three-point
3. **Identify interdependencies** - the four dependency types; identify critical path, early/late start, float
4. **Balance the schedule based on constraints** - resource levelling, resource and time constraints, crashing, stage gates and milestones
5. **Project control** - monitor progress, assess performance, intervene; handle change orders, delays, inspection failures, technical changes

The variability-on-the-estimate curve alongside makes the point that scope, time and the estimate are not independent.

#### Temporal dependencies
![[Complexity-slides-Jan-2023.pdf#page=56&rect=25,50,940,490|Complexity-slides, p.56]]
Four logical activity linkages. **If nothing else is noted in the network diagram, it is Finish-to-Start.**

| Dependency | Meaning | Example |
| --- | --- | --- |
| Finish-to-start (FS) | B cannot start until A finishes | Foundations dug FS concrete poured |
| Start-to-start (SS) | B cannot start until A starts | Project work started SS project management activities started |
| Finish-to-finish (FF) | B cannot finish until A finishes | Last chapter written FF entire book written |
| Start-to-finish (SF) | B cannot finish until A starts | New shift started SF previous shift finished |

#### Lag and lead
![[Complexity-slides-Jan-2023.pdf#page=57&rect=25,50,940,490|Complexity-slides, p.57]]
- **Lead**: advances the start or end of an activity (negative, "−")
- **Lag**: delays the start or end of an activity (positive, "+")

Notation: *type of dependence* & *+ or −* & *number of time units*. Fx **SS+3** means task B cannot start until three days after task A has started.

![[Complexity-slides-Jan-2023.pdf#page=58&rect=25,45,940,495|Complexity-slides, p.58]]
Lag is a deliberate delay put in for a reason - fx between plastering a wall and painting it, so the cement can set. Nobody adds delay without justification; it serves quality or a strategic timing goal.

![[Complexity-slides-Jan-2023.pdf#page=59&rect=25,45,940,495|Complexity-slides, p.59]]
Lead is advancement - starting to edit a document once one portion is ready rather than waiting for all 5,000 pages. Lead is also how **fast-tracking** works as a compression technique, and it carries rework risk: starting development when only part of the design is done.

#### Critical Path Method
![[Complexity-slides-Jan-2023.pdf#page=60&rect=25,50,940,490|Complexity-slides, p.60]]
CPM is a network diagramming technique used to predict total project duration.
- The **critical path** is the series of activities that determines the earliest time by which the project can be completed
- It is the **longest** path through the network, and has the least slack or float
- **Slack/float** is the amount of time an activity may be delayed without delaying a succeeding activity or the project finish date

Steps: develop the network diagram → add the durations along each path → the longest path is the critical path. If an activity on the critical path takes longer than planned, the whole project slips unless the PM acts.

A **forward pass** determines early start and finish dates; a **backward pass** determines late start and finish dates.

![[Complexity-slides-Jan-2023.pdf#page=62&rect=25,35,940,505|Complexity-slides, p.62]]
The node notation:
- **Earliest start (EST)** - determined by the preceding activities
- **Early finish** - the earliest the activity can be completed
- **Latest start (LST)** - the latest all preceding activities need to be complete
- **Late finish** - the latest the activity can be completed
- **Total float** - the difference between EST and LST

#### Worked example
![[Complexity-slides-Jan-2023.pdf#page=63&rect=25,35,940,505|Complexity-slides, p.63]]
Reading the boxes as *ES | duration | EF* on top and *LS | float | LF* below:

| Activity | ES | Dur | EF | LS | Float | LF | |
| --- | --- | --- | --- | --- | --- | --- | --- |
| F | 0 | 20 | 20 | 0 | 0 | 20 | **critical** |
| A | 20 | 10 | 30 | 25 | 5 | 35 | |
| B | 20 | 5 | 25 | 20 | 0 | 25 | **critical** |
| E | 20 | 15 | 35 | 25 | 5 | 40 | |
| D | 30 | 5 | 35 | 35 | 5 | 40 | |
| C | 25 | 15 | 40 | 25 | 0 | 40 | **critical** |
| G | 40 | 20 | 60 | 40 | 0 | 60 | **critical** |

Critical path: **F → B → C → G**, total duration 20 + 5 + 15 + 20 = **60**.

The parallel branches F→A→D and F→E both carry 5 units of float - they can each slip five days before G is affected, but not independently if they share resources. Float belongs to the *path*, not to the individual activity.

#### Behavioural aspects of the schedule
![[Complexity-slides-Jan-2023.pdf#page=64&rect=25,50,940,490|Complexity-slides, p.64]]
**Scheduling doesn't manage only time - it manages BEHAVIOURS.**
- Dependencies, activities and durations are not cast in stone
- Estimations are guesses, and they are biased and political
- No Gaussian distribution - we have optimism bias, so the distribution is skewed
- Safety is built into estimates
- Motivation
- **Parkinson's Law** - work expands to fill the time available, so the safety margin gets consumed
- **Student syndrome** - the work starts at the last possible moment, so the safety margin is spent before the work begins
- The critical path is not the only constraint
- Multi-tasking
- Unreliable reporting - the 90% ready syndrome

Together these explain why safety hidden *inside* each activity never accumulates into safety for the *project* - which is exactly the argument for critical chain buffers below.

#### Advice
![[Complexity-slides-Jan-2023.pdf#page=66&rect=25,60,940,470|Complexity-slides, p.66]]
"You should always keep 3 schedules: one based on optimistic, another based on pessimistic values and another one based on most likely. Give the optimistic one to the team, the pessimistic one to the boss and keep the most likely with you."

Worth reading against the ethics section of the People material - it is offered as practitioner's advice, not as a recommendation to be dishonest, and it is a fair question which it is.

#### Matching method to dependency
![[Complexity-slides-Jan-2023.pdf#page=67&rect=25,35,940,505|Complexity-slides, p.67]]
Which life cycle fits which method? Map it back to pooled / sequential / reciprocal. Sequential dependencies suit a Gantt and a predictive life cycle; reciprocal dependencies do not - no amount of network diagramming resolves a mutual dependency, which is why those parts want iteration.

Reflection: what types of schedule were present in the project? How was the schedule developed? How was it used through the life cycle?



## Resourcing - Who and how much?

#### Resources according to ISO21502
![[Complexity-slides-Jan-2023.pdf#page=72&rect=25,50,940,490|Complexity-slides, p.72]]
The purpose of resource management is to determine the resources needed to deliver the scope of the project in terms of quality, quantity and optimum usage.
Activities:
- 7.5.2 Planning the project organization
- 7.5.3 Establishing the team
- 7.5.4 Developing the team
- 7.5.5 Managing the team
- 7.5.6 Planning, managing and controlling physical and material resources

Note that four of the five activities are about *people* - this is where Complexity and People meet in the standard.

#### Types of resources
![[Complexity-slides-Jan-2023.pdf#page=73&rect=25,35,940,505|Complexity-slides, p.73]]
People, facilities, tools, equipment, infrastructure, materials - and money.

#### Constraints and the theory of constraints
![[Complexity-slides-Jan-2023.pdf#page=74&rect=25,50,940,490|Complexity-slides, p.74]]
Goldratt (1997) applies the theory of constraints to project management. **Constraints are not only the critical path.** They also include availability of resources, fixed external dates that cannot be moved, and behaviours and policies.

Suggestions:
- Identify the constraints, and avoid or manage them carefully
- Safety and buffers should be **owned by the project, not by the activity**, placed as late as possible and in favourable locations
- Buffers go at the end of non-critical paths (feeding buffers), ensuring they do not themselves become critical
- A project buffer goes at the end of the project

This is the direct answer to Parkinson's Law and student syndrome: pull the safety out of the individual activities, where it gets consumed invisibly, and pool it at the end where it is visible and defensible.

#### Case: Eurovision 2014
![[Complexity-slides-Jan-2023.pdf#page=75&rect=25,35,940,505|Complexity-slides, p.75]]
Reflection: did the project have access to the necessary resources? Were there changes to the project organization? What were the consequences?



## Cost

#### Cost according to ISO21502
![[Complexity-slides-Jan-2023.pdf#page=79&rect=25,50,940,490|Complexity-slides, p.79]]
The purpose of cost management is to establish the financial controls to be used throughout the project life cycle to facilitate delivery of the project within the approved budget.
Activities:
- 7.7.2 Estimating cost
- 7.7.3 Developing the budget
- 7.7.4 Controlling costs

#### Costing
![[Complexity-slides-Jan-2023.pdf#page=80&rect=25,50,940,490|Complexity-slides, p.80]]
Cost planning is based on estimation of predicted costs, benefits (not always financial) and risks - which together form the basis of the business case. Planned costs become baselines; budgets are turned into activities and outcomes. But requirements change as the project progresses, so it is an iterative process.

Is there a perfect estimate? No - costing processes are rarely objective, and stakeholders determine what is politically acceptable.

Why we need it: organizations need to decide which projects to pursue (portfolio management), and it provides the input to selection and the baseline.

#### Cost build-up
![[Complexity-slides-Jan-2023.pdf#page=81&rect=25,45,940,495|Complexity-slides, p.81]]
Elements of cost (Maylor 2010), stacked:
- **Time** - direct input of labour
- **Materials** - consumables and other items, at cost or cost + margin
- **Capital equipment** - the means of providing the conversion process, plus maintenance, running and depreciation; the entire cost when purchased specifically, with a possible residual value
- **Indirect expenses** - transport, training and so on, not directly value-adding but considered necessary
- **Overheads** - office, financial and legal support, managers and non-direct staff
- **+ Contingency** - a margin or allowance, fx 10 percent

![[Complexity-slides-Jan-2023.pdf#page=82&rect=25,35,940,505|Complexity-slides, p.82]]
The iPhone cost build-up (asymco.com, 2012) as a concrete illustration of how little of a price is the bill of materials.

#### Cash flow
![[Complexity-slides-Jan-2023.pdf#page=87&rect=25,35,940,505|Complexity-slides, p.87]]
Cash-in and cash-out over time. Cost is not the same as cash: the project can be profitable overall and still run out of money in the middle. **Payment milestones** are the lever - they determine when cash-in arrives relative to cash-out.

#### Case: Eurovision 2014 outcome
![[Complexity-slides-Jan-2023.pdf#page=90&rect=25,45,940,495|Complexity-slides, p.90]]
- Initial construction budget: DKK 18 M
- Final construction cost: DKK 90 M (a factor of five)
- Final result: DKK −57.9 M
- Total cost for Danish taxpayers: DKK 215.2 M

![[Complexity-slides-Jan-2023.pdf#page=91&rect=25,35,940,505|Complexity-slides, p.91]]
Cost overruns in general - the Eurovision figure is not an outlier but an instance.

Reflection: what was the budget? How was it calculated? Was it changed over the duration, and why?



## Improving - Can we do it better?

#### Control and milestone distance
![[Complexity-slides-Jan-2023.pdf#page=94&rect=25,35,940,505|Complexity-slides, p.94]]
Our ability to control is dependent on the distance between the milestones. Long gaps mean you discover deviation late; short gaps mean you discover it while it is still cheap. This is the same argument as the sprint length in Scrum.

#### Multi-tasking
![[Complexity-slides-Jan-2023.pdf#page=95&rect=25,35,940,505|Complexity-slides, p.95]]
Splitting three tasks across each other rather than doing them in sequence:
- Each task takes longer - and the *first* task, which could have been delivered early, finishes last
- Moving between tasks costs time to re-familiarise - wasted time
- Multi-tasking is often inevitable, but should be used with care

#### Crashing
![[Complexity-slides-Jan-2023.pdf#page=96&rect=25,50,940,490|Complexity-slides, p.96]]
Two conditions for any activity:
- **Normal** - the most likely duration
- **Crashed** - expedited by applying additional resources: specialized or additional equipment, more people (borrowed staff, temps), more hours (overtime, weekends)

Potential negative consequences: additional equipment and material cost, extra labour, negative effects on other projects, reduced morale from excessive hours and shifts, and lower quality from time pressure and inexperienced or tired staff.

![[Complexity-slides-Jan-2023.pdf#page=97&rect=25,50,940,490|Complexity-slides, p.97]]
Two basic principles when crashing:
1. Speed up the **critical path** (reduce the duration of critical activities), use concurrency, and/or change scope. Crashing a non-critical activity buys nothing.
2. When shortening the duration, choose the least expensive way - compute the cost/time slope for each option:

$$\text{Slope} = \frac{\text{crash cost} - \text{normal cost}}{\text{crash time} - \text{normal time}}$$

Crash time is shorter than normal time, so the denominator is negative; what you compare across options is the cost per unit of time saved. Crash cheapest-first, and re-check the critical path after each step - it moves.

#### Types of activities
![[Complexity-slides-Jan-2023.pdf#page=98&rect=25,45,940,495|Complexity-slides, p.98]]
Not everything can be crashed. Four types:
- **Resource-dependent** - duration can be changed; halve it by doubling the resources (experienced ones). Fx programming, digging, drawing work. *Speed up: add more people.*
- **Process-dependent** - duration is set by a process that must run to get the result; it cannot be rushed. Fx pregnancy, curing of concrete, training and education. *Speed up: difficult, sometimes through a change of equipment.*
- **Procedure-dependent** - a certain procedure must be followed, with uncertainty about its outcome. Fx steering committee meetings, consultation of stakeholders. *Speed up: fx the Ebola-driven change of regulation.*
- **Problem-dependent** - activities to solve a problem, where innovation is paramount and duration is hard to estimate at all. Fx design, development, creative tasks. *Speed up: difficult - through intermediary deadlines or forcing an end, 'time boxing'.*

Adding people only works for the first type. This is the serious version of the "nine women, one month" joke on p.121.

#### Value-added work
![[Complexity-slides-Jan-2023.pdf#page=99&rect=25,35,940,505|Complexity-slides, p.99]]
![[Complexity-slides-Jan-2023.pdf#page=100&rect=25,35,940,505|Complexity-slides, p.100]]
Accelerating the schedule and the lean view: the alternative to working faster is removing the waiting. Most of a lead time is usually not work at all.

#### Case: COVID-19 vaccine development
![[Complexity-slides-Jan-2023.pdf#page=101&rect=25,35,940,505|Complexity-slides, p.101]]
The clearest recent example of compression: phases that are normally sequential were run in parallel and financial risk was carried up front, so the *schedule* compressed without the *process* steps being skipped.

Reflection: was the project plan optimized, how and why? What was done to optimize the realization of value while limiting waste?



## Contracting - Make or buy?

![[Complexity-slides-Jan-2023.pdf#page=104&rect=25,60,940,470|Complexity-slides, p.104]]
"There are so many advisors and sub-advisors involved in the [channel fixed link] project that I hate to think of the amount of paperwork being produced. One thing is for sure, none of them are digging a tunnel." (The Sunday Times)

#### Why purchasing matters
![[Complexity-slides-Jan-2023.pdf#page=105&rect=25,35,940,505|Complexity-slides, p.105]]
Around **70%** of the money goes on purchasing, against 30% on salary and overhead. Broken into categories: civil engineering 21%, carpenter/roofing/facades 14%, installations 13%, concrete and stone 11%, interior and surface 7%, rentals/leasing 7%, steel 6%, professional services 6%, wood 2%.

The consequence is simple: this is where the money is lost and earned. Optimising internal efficiency addresses the smaller share.

#### It depends what you are buying
![[Complexity-slides-Jan-2023.pdf#page=106&rect=25,35,940,505|Complexity-slides, p.106]]
Volume against variety (Maylor 2011): standardized products at high volume and low variety; "as… but…" in the middle; first-timers at low volume and high variety. The purchasing approach - and the contract type - should follow the position on this map.

#### The relationship spectrum
![[Complexity-slides-Jan-2023.pdf#page=107&rect=25,40,940,500|Complexity-slides, p.107]]
From spot buy → regular trading → blanket contract → fixed contract → alliance → partnership:

| | Spot / regular | Blanket / fixed | Alliance / partnership |
| --- | --- | --- | --- |
| Trust based on | Only the contract | Contract and supplier competence | Goodwill and cooperation |
| Relationship | None personal | Formal personal | Strong personal |
| Negotiation | Tactics and ploys, price oriented, short term | Bargaining, price and service oriented, medium term | Mutual gains, total cost of ownership, long term |
| Performance measured | On non-compliance | Non-compliance and vendor rating | Both organizations measure each other and jointly develop remedial actions |

Note the Eurovision case in the People material: the contractual setup sat at the left end of this spectrum while the work needed the right end.

#### Contract types and risk allocation
![[Complexity-slides-Jan-2023.pdf#page=108&rect=25,60,940,470|Complexity-slides, p.108]]
Lump-sum, unit rate, guaranteed maximum price, incentive contract, guaranteed maximum liability, percentage fee, cost-plus percentage.

![[Complexity-slides-Jan-2023.pdf#page=109&rect=25,50,940,490|Complexity-slides, p.109]]
Contractual uncertainty and risk allocation (Winch 2009). Three options - fee-based, fixed-price, and incentive contracts - arranged along a spectrum of who carries responsibility for changes in specification, from client responsibility to supplier responsibility.

The trade-off: a fixed price transfers risk to the supplier, but the supplier prices that risk in, and every change becomes a negotiation. Fee-based keeps flexibility with the client and keeps the risk there too.

#### The role of third parties
![[Complexity-slides-Jan-2023.pdf#page=110&rect=25,45,940,495|Complexity-slides, p.110]]
Between principal (client) and agent (architect/engineer, or contractor), third parties handle: measurement of supplier achievement, speedy adjustment of minor changes, first-line dispute resolution, and trading in probity - the principal quantity surveyor, the bureau de contrôle, the supervising officer / the engineer, and the professional institutions (Winch 2009).

#### Procurement according to ISO21502
![[Complexity-slides-Jan-2023.pdf#page=111&rect=25,50,940,490|Complexity-slides, p.111]]
The purpose of procurement is to source products and services bought as part of resourcing the work that are of appropriate quality, represent value for money and can be delivered when needed within an acceptable level of risk.
Activities:
- 7.17.2 Planning procurement
- 7.17.3 Evaluating and selecting suppliers
- 7.17.4 Administering contracts
- 7.17.5 Closing contracts

#### The purchasing process
![[Complexity-slides-Jan-2023.pdf#page=112&rect=25,60,940,470|Complexity-slides, p.112]]
Prepare a brief (specification) → invite three or more to quote → evaluate the proposals objectively → decide who to appoint → notify the successful and the unsuccessful proposers → letter of appointment.

#### Case: super hospitals and the Eurovision contractual setup
![[Complexity-slides-Jan-2023.pdf#page=113&rect=25,35,940,505|Complexity-slides, p.113]]
![[Complexity-slides-Jan-2023.pdf#page=114&rect=25,35,940,505|Complexity-slides, p.114]]
Reflection: what types of contract governed the project, and how did the contractual setup shape the collaboration?



## Connecting the dots

#### Managing complexity
![[Complexity-slides-Jan-2023.pdf#page=117&rect=25,50,940,490|Complexity-slides, p.117]]
From the complexity perspective, we aim:
- **Separating** - to break the purpose down into more manageable chunks of work, so that work becomes doable and can be delegated to different people or teams
- **Integrating** - to coordinate these interdependent chunks so they complement one another and contribute to the project purpose
- **Adapting** - to evolve the project and respond to changing conditions

Three verbs, and every tool in the lecture belongs to one of them: WBS and estimating separate; scheduling, dependencies and contracts integrate; rolling wave, buffers and crashing adapt. (DS Handbook ch. 6.4, "How to DO it?".)

#### Planning according to ISO21502
![[Complexity-slides-Jan-2023.pdf#page=118&rect=25,45,940,495|Complexity-slides, p.118]]
The purpose of planning is to define the requirements, deliverables, outputs, outcomes and constraints, and to determine how the project's objectives should be achieved.
Activities:
- 7.2.2 Developing the plan
- 7.2.3 Monitoring the plan

A plan can include: benefits to be realized (7.3); scope - outputs and outcomes to be delivered (7.4), taking quality into account (7.11); resources needed such as people, materials, tools, equipment and other organizations (7.5); schedule - when activities are to be done (7.6); cost (7.7); risks inherent in the plan (7.8); and assumptions and constraints.

This clause is the index to the whole lecture - each item is one of the core practices.

#### Smooth journey
![[Complexity-slides-Jan-2023.pdf#page=119&rect=25,60,940,470|Complexity-slides, p.119]]
"Planning is an unnatural process. It is much more satisfying to do something and the nicest thing about not planning is that failure comes as a complete surprise rather than being preceded by a long period of worry and depression." (attributed to Sir John Harvey-Jones)

#### Making babies
![[Complexity-slides-Jan-2023.pdf#page=121&rect=25,50,940,490|Complexity-slides, p.121]]
The joke that summarises the methods (Steve Peacocke):
- **Nature**: a woman produces a baby in 9 months
- **Project management**: 9 women can make a baby in a month
- **Lean**: we concentrate on conception and birth and eliminate the waiting time in the middle
- **Scrum**: we take the baby out every 2 weeks to show the parents, ask if this is what they want, then plan the next two weeks' growth with any changes needed
- **Agile**: at any time we can change the baby's nationality or sex, or decide we now want a pair of socks instead
- **Kanban**: we make small baby parts one by one until we have a whole baby

It lands because gestation is a *process-dependent* activity (p.98) - the one type none of these methods can actually compress.

#### The four questions of a project
![[Complexity-slides-Jan-2023.pdf#page=122&rect=25,35,940,505|Complexity-slides, p.122]]
- **Purpose**: why? what?
- **Complexity**: how? where? when?
- **Uncertainty**: what if? what now? so what?
- **People**: who? whom?

Complexity is the *how*, and it only makes sense downstream of the *why* - a perfectly decomposed WBS for the wrong purpose is the "die quickly" quadrant from the Purpose material.
