# think-tank
Experimental Methodology for Brainstorming

# What we don't want:
-   **Design By Committee**
    - When a project has many designer but no unifying vision or plan. (Does not mean a committee cannot be used to effectively design.)
    - Expertise and ability not distributed equally. (Dunning-kruger effect)
    - Poor compromises made to keep everyone happy.
    - Solutions: 
        -   Roles. 
        -   Hierarchy.
        -   Formal process.
-   **Group-Think**
    -   Occurs within a group of people in which the desire for harmony or conformity in the group results in an irrational or dysfunctional decision-making outcome.
    -   Illusions of invulnerability, unquestioned belief, rationalised warnings, stereotyping, self-censorship. 
    -   Cased by: Desire to conform, insulation of group, lack of impartial leaders, lack of responsibility for errors. 
    -   Solutions: 
        -   Leaders can assign devils advocate roles, choose not to express opinions about a solution before presenting problem, independent groups to work on the same problem. 
        -   Peer review.
        -   Secret ballot - survey members of the group and keep responses anonymous. Prelude to structured group discussions by giving comfort to put everything on the table.
-   **Moral Hazard**
    -   One person takes more risks because someone else bears the cost. 
    -   Information asymmetry.
    -   Incentives exist to take risks.
    -   Management vs. technical split.
    -   Solutions: 
        -   Create roles and hierarchy with accountability.
        -   Align interests.
        -   Communication.
-   **Silos**
    -   Isolated teams, too much communication up and down the hierarchy not enough cross team. 
    -   Potential solutions missed.
    -   Solutions:
        -   Cross team communications.
# What we want:
Approach brainstorming from a different way by considering the above pitfalls and create an (possibly experimental) new methodology.

Ideally this new strategy would present itself to display an inventory of the group’s favourite ideas while making sure that people’s choices have not been influenced by the more dominant individuals in the group. The new strategy would also apply something of a democratic method which may lead to a larger support base for the resulting outcome.

**Requirements of the implementation:**

-   Web Based
    -   Platform whereby users can contribute to a central work space. Another can suffice as long as the following needs are met. The web seems most readily to provide what is required.
-   Anonymous Titles
    -   We want to strike a balance between the the accountability and weight of appointed roles and the freedom afforded by anonymity.
    -   Users of the system should have their names hid, but their titles shown. (i.e. Junior Software Developer, Software Architect)
    -   Logins may or may not be needed.
-   Border-less Access
    -   Anyone from any team should be able to lend an idea or component of any solution.
    -   Cross team communications and problem solving increase. 
-   Top-Down Flow
    -   Unifying plan or vision should be submitted by those authorised, then a solution built from filling each successive lower layer from the top all the way down.
    -   Ideally the highest layer being the problem or vision of a feature/product, and the lowest layer being something that can be readily placed into a sprint plan. 
    -   A contributing user may call an anonymous poll at any time to accept the existing layer and advance to the next, lower layer. A consensus must be reached to advance. This will give unsure users time to voice (text) any concerns.  
-   Decaying Forced Incubation Period
    -   A generous period of time allotted for users to contribute ideas without fear of thinking against the clock and prevents hasty decision making.
    -   Once the timer is up, engage in evaluation techniques, then vote on layer consensus.
    -   The largest amount of time should be allotted for the highest layer, then decreased for each successive, lower layer, as ideas and tasks become and narrower more technical in scope.

**Mix in solid brainstorming evaluation techniques:** (hatrabbits.com):

1.  Cluster the ideas
    *   Lay out all ideas and ask participants to group similar ideas, without consultation. 
    *   Set aside "loner" ideas.
2.  Name the clusters
    *   Umbrella themes (groups that fall into larger themes).
    *   Sub-themes (groups that should be or are in smaller themes).
3.  Remove duplicates
    *   Be careful! People can throw out good ideas, as subtle differences may not be apparent to others. Only delete *exact* copies.
4.  Number the ideas
    *   Fairly straightforward.
5.  Anonymous voting
    *   Everyone picks top three.
6.  Create a shortlist

**Proposed New Methodology:**

1.   Users login to portal, with only titles being an identifier.
2.   *Seeder* creates the *seed* idea or defines the problem to solve.
3.   Problem has an *incubation* period where ideas sit and collect notes from contributors. Anyone can and should contribute during this time. 
4.   Once *incubation* period is up, preform the steps of the brainstorming process linked above.
5.   Repeat the above and solve the solution layer by layer, and only move onto the next, lower, stage once a layer has been agreed by *anonymous consensus* to be finalised. (Expertise and contributions will shift depending on layer as we move from the high level to the low level) Anyone can kick-off the poll at anytime after the inclubation period.
6.   Once the layer of ideas reach sprint story sized chunks, the process is done. 
7.   Document and handover to sprint team. 
