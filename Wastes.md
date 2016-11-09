# Wastes

Once we are done mapping the different processes, we can start identifying wastes.
A good approach is to start finding the Scrap Rate (S/R) for all the processes. This is how often a process will fail and will need to be done all over again. For example, if you have to configure an environment 3 times before things work, the S/R will be 75%.
When a process never, or very rarely fails, you should not put a S/R number to avoid overflowing the map.
S/R should be captured in red.

Once this is done we can now map the different kind of wastes. There are 8 kind of wastes, described below. They should be marked in red on the map.

Notation  | Waste Classification  | Description   | Examples |
--- | --------------------- | ------------- | -------- |
D   | Defects               | Incorrect, missing, or unclear information or artifacts. Disrupts the system and adds time/effort needed to resolve. | Broken build / Incorrect configuration / Incorrect requirements |
M   | Manual (HandOffs)     | Overhead, coordination, hadoffs, or other inefficiencies surrounding the setup and execution of work. | Meetings / Manual deployments / Handoffs between teams |
W   | Waiting               | Delays in starting or completing the next value-adding step for a unit of work. | Waiting for approval - change windows / Waiting for resources / Waiting for schedule coordination |
PD  | Partially Done        | Work output that isn't in a complete, usable state (from customer perspective). Often needs input/action from others or further work. Increases defects, task switching, and waiting. | Undeployed and untested code / Incomplete environment setup / Batching within lifecycle |
TS  | Task Switching        | Context switching from partially done work to other work creates waste due to high expense of context switching and greater likelihood of errors. | Unenforced work in progress limits / Interrupts from outages / Cube "drive-bys" - ad-hoc info request |
EP  | Extra Process         | Non-value adding steps or processes that are required (formally or informally) as part of the standard flow of work. | Unnecessary approvals / Unused documentation / "Rubber Stamp" review boards |
EF  | Extra Features        | Features, usually added during implementation, that are not required by or justified by current business needs. Doesn't remove limitation on the business or create customer value. | "Someday we might need..." / Unnecessary upgrade or replacement / Features no one asked for |
H   | Heroics               | Unreasonable burden or extraordinary effort required of someone to successfully complete work or satisfy the customer. | Multi-day firefight-style deployments / Years of tribal knowledge required / Extreme project coordination required |

# Recommendations

Once we are done capturing the wastes we can move to recommendations.
Recommendations can be DevOps practices (such as Continuous Integration) or more general suggestions.
Generally speaking, it is a good practice to avoid talking about specific tools, we want to keep the discussion to a higher level.
With that said if a particular tool makes obvious sense it is okay to capture it directly. For example, if the customer should implement Continuous Integration, and they already stated their interest in VSTS, then it is okay to capture `CI (VSTS)` as a recommendation.
Note that a recommendation might (and very often will) span multiple process.
Recommendations should be marked in green.
