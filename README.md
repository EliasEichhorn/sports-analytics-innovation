# sports-analytics-innovation
# Expected Rest Advantage: NBA Fatigue Metric

## Project Overview
A metric that combines back-to-back games, travel distance, and minutes played into a single "fatigue-adjusted performance" score for each player and team.

## Decision-Making Problem
Helps coaches and front-office staff decide when to rest players and how to manage minutes across the schedule.

## Proposed Analytics Approach
Uses game logs, travel schedules, and player tracking data (minutes, distance run). Analysis compares performance in high-fatigue vs. low-fatigue situations. No implementation is required at this stage.

## Use by Decision Makers
A coach sees a simple dashboard before each game showing green/yellow/red fatigue levels. A GM uses season-long trends to plan rest and roster depth.

## Connection to Chapter 7
This idea is in the **creative phase**. It is a new concept with a defined problem, but it has not been tested or shown to decision makers yet.

## Prototype Enhancement
**What is being changed:** Add a second data source, player sleep and recovery data from wearables, to refine the fatigue score.

**Why this could improve decision-making:** Schedule-based fatigue (back-to-backs, travel) misses individual differences. Recovery data would let coaches rest the players who actually need it, not just those on a tough schedule.

## Next Steps
Prototype refinements will be developed on a separate branch and evaluated before adoption.

## Prototype Evaluation
**Should the prototype be integrated?** Yes. The enhancement adds individual-level information without changing the core metric, and it addresses the biggest weakness of the original idea.

**Feedback that would influence the decision:** Coaches saying the fatigue score is easy to read and useful before games, medical staff confirming the wearable data is reliable, and the front office confirming players consent to data sharing. If decision makers found the score confusing or the data unreliable, I would hold off.

## Reflection on Innovation and Version Control
**How branches support low-risk experimentation:** Branches let analytics teams test changes without touching the main project. If the prototype had failed, the working version would have stayed intact, so experimenting costs almost nothing.

**How GitHub helps ideas gain traction with decision makers:** GitHub keeps a visible, documented history of how an idea was proposed, tested, and evaluated. Decision makers can review the reasoning at any point, which builds trust and makes it easier to give feedback and approve adoption.

**How this workflow aligns with Chapter 7:** The README was the creative phase, the prototype branch was the prototyping phase, the evaluation section was the engagement phase, and merging into main was the build phase. Version control makes each innovation phase visible and reversible.
