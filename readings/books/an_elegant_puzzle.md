# An elegant puzzle: systems of engineering management
## Will Larson

# 1. Introduction - Chapter 1
> "Organizational design gets the right people in the right places, empowers them to make decisions, and then holds them accountable for their results"

# 2. Organizations - Chapter 2
> "For quick change, process. Strong but slow, culture. Organization desigin lies between"

## 2.1 Sizing teams
> "Fundamental challenge of organizational design is sizing of teams"
### Guidelines
> Managers should support six to eight engineers
*  Tech Lead Managers (fewer than four engineers) \
Tend to take share of design and implementation work.
* Coaches (more than eight engineers) \
Safety nets for problemas. Too busy to invest in their team or team area of problem.
> Managers of Managers should support four to six managers
Ramp up with less, with more will be a coach
* On call rotations need eight engineers
> Shared rotations
> What about instead of one team member be responsible for operation each time have a rotation team
* Small teams are not teams
> teams should work equally indenpendently of losing one piece
> Small teams area fragile
* Guiding principles
> Teams should be six to eight during steady state. 
> To create a new team, grow an existing team then bud into two teams of 4 or five
> Never create empty teams
> Never leave managers supportin more than eight individuals

## 2.2 Staying on the path to high-performing teams
Loose framework to reasoning what a team needs to increase performance
> Falling behind - Add people
> treading water - reduce wip 
> repaying debt - add time
> innovating - add slack

## 2.2.1 Four states of a team
> Falling behind - backlog grows over time
> Treading water - Gets critical work done but cant pay debt
> Repaying dept - Repaying debt releases time to pay mode debt 
> Innovating - debt is low, morale is high, and the majority of work is satisfying new user needs
Team try to climb and entropy drags them back.

## 2.2.2 System fixes tactical support
Team transitions from a state to anothe when they have the correct solution
The managers role is to identify and apply the correct solution and support the team to make the solution work. 
> Falling behind fix is to hire: internal realocation trying to optimize rarely works. As is does not increase company capacity.
> Treading water team's fix is to reduce wip: Concentrate in finishing more things
> Repaying dept team's fix is add some time to things keep working, and compounding value of paying debt grows
> Innovating is a bit different: keep the slack in team schedule so the team can keep quality work
This fixes are slow. 
Keeping the focus may delay first value form some project, but will increase the overall value over investment in time

## 2.2.3 Consolidate your efforts 
> Dont over spread investment in too many fronts as manager trying to apply fixes to teams
> Prioritize one team at time. 
> Adding nem members to team disrupts that team gelling process. 
> Organizations may grow indefinitely but team don't.

## 2.2.4 Durable excellence
This approach is slow, but leads to enduring real improvements.

## 2.3 A case against top-down global optimization
> Should a team with capacity surplus help another falling behind?

## 2.3.1 Teams first
> Sustained productivity comes from high-performing (HP) teams.
> HP teams are sacred. Disassemble leads to overall decrease in productivity.
> Teams take long to gel. 
> Account for re-gelling costs.
> Ex. Hire in falling behind teams not in innovating ones. 

## 2.3.2 Fixed costs
> Team generally have hith fixed costs and low variable ones
> Decreasing 1 engineers leads to a small reduction in fixed cost, and may lead a treading water team to fall behind
> Fixes costs come in many flavors as operations duties, answering support doubts.

## Slack 2.3.3
> Moving resources to a team can slow teams down as it create upstream constrains of other team dependencies
> Slacking teams  can be often removed from analysis of resource constrains.
> Thinking in systems. (Donella H. Meadowns)

## 2.3.4 Shift scope; rotate
> Preserve teams, change scope.
> Move responsibility to slacking teams, but keeping slack enough.
> Avoids regelling costs
> Move member to teams that need help for a fixed time. To avoid them to seek membership.

## 2.4 Productivity in the age of hypergrowth
> "Process is always six month behind"

## 2.4.1 More engineers more problems
> Fixed cost of hiring.
> How much takes to a dev to be productive.
> Increasing engineers leads to increase in: new layer of management, coordination, load on development tools, more incident treatment and more on-call specialty.

## 2.4.2 Systems survive one magnitude of growth
> Most systems are design to to support one or two orders of magnitude of growth
> The cardinality of supported systems increases over time as you add teams , and as “ trivial ” systems go from unsupported afterthoughts to focal points for entire teams as the systems reach scaling plateaus ( things like Apache Kafka , mail delivery , Redis , etc. ).
> What kills productivity are not systems rewrites, is migration. 
> Active-active design

## 2.4.3 Ways to manage entropy
> 
