# Unsound: Sources of Unsoundness in Verification

Software and proof verification has grown significantly in the last 15 years. Growth has come to the point where verification systems are complex and manually proving the soundness of those verification systems sometimes exceeds what a single research group can understand and verify as correct.

Even formally defining soundness can be challenging and its definition is varying from system to system. Specific research groups can have very specific notions of soundness they focus on, but those can diverge from what the users expect, especially if the users come from a different verification environment or they are approaching verification for the first time.

Participants to Unsound will be able to share their experience and exploits on how different verification tools can either be broken or expose confusing behavior, likely to be unexpected by users. We think this would be greatly beneficial not only because it will help all of us to iron out those unsoundnesses but also because it will facilitate understanding of the foundational differences between the assumptions of the various research lines.

The current academic environment encourages us to talk about the success case of our work. In this workshop we want to address and learn from failure cases and we want to reinforce the bedrock of our understanding. In practice, when we divert our focus to a specific aspect of verification we may (understandably) be less precise. For example, a line of research focusing on aliasing control in OO may be less precise when considering the implication in other areas, like termination. We believe that learning from the issues of many verification projects can broaden the attention of researchers to topics which so far escaped their focused area of research; e.g., from only type correctness to also avoiding stack overflows.

We believe that this environment would be particularly beneficial for young researchers that are in search of open questions in verification. This may provide a motivation to deep dive into the details of any particular tool, or to expand their individual area of expertise to get a wider and more objective and critical view of the whole area of verification.

We also wonder if in our fast expansion we accidentally glossed over some fundamental issue in verification, and if our mistake has now become engraved into the established wisdom and it is sometimes uncritically assumed as a valid reasoning stepping stone.

We are particularly interested in sources of unsoundness that are accidentally shared by many different unrelated research lines, and to develop an understanding on why this is the case.

The workshop would be its first instance and is meant to be welcoming for both people with strong theoretical skills, as well as people who just like hacking things. We do not expect fully polished submissions and we will not have formal proceedings. Students are especially welcome to attend.


## Examples for possible contributions would be:

* Definition of sound and unsound and how they can diverge between tools.
* Divergences between user assumptions and actual definitions of soundness.
* Common sources of unsoundness and why they emerge. 
* Bugs and unsoundnesses in the process of extracting a concrete program from a verified environment, e.g., from Coq to Haskell.
* Logic errors in the specification of a verification tool, e.g., universe inconsistencies.
* Bugs in the implementation of proof checkers.
* Overconfident generalizations of sound subsystems to larger settings, e.g., imperative techniques in OO settings.
* Disproving soundness statements in published papers about verification.
* Finding statements proven in published literature that should no longer be trusted because they relied on a broken verification system.
* Simply proving False in a verification tool, in particular we are interested in practical ways to trick available tools to accept wrong statements.
* Breaking reasoning about programs with types by breaking the type system of the programming language in new and interesting ways.
* Bad interactions between axiomatic choices in libraries used in proofs.
* Impacts of the false sense of security when the chain of trust is broken by subtle unsoundness in verification tools.


## Call for Papers

Unsound 2022 will be part of [SPLASH](https://2022.splashcon.org/) and take place as a hybrid event.

### Contributions:

Extended Deadline: 2022-09-16 (23:59 AOE)

The main body of the paper should have 4 pages of text. Additional material (bibliography, related work, and code examples) will not count toward this limit.
We strongly encourage authors to include instructions to reproduce results or exploits.

There will be a friendly peer review process, focusing on checking that the submitted material is appropriate for the workshop.

#### Publication

Informal proceedings will be made publicly available on the workshop web page. However, presentation at Unsound does not count as prior publication, and can later be published at a conference of the authors' choosing.

### Instruction to Authors

#### Submission

Authors should be aware of ACM’s policies on plagiarism [https://www.acm.org/publications/policies/plagiarism](https://www.acm.org/publications/policies/plagiarism).

Program Committee members are allowed to submit papers.

Papers must be submitted online at:

[https://unsound2022.hotcrp.com/](https://unsound2022.hotcrp.com/)

#### Formatting:

Submitted papers should be in portable document format (PDF), formatted using the ACM SIGPLAN style guidelines. Authors should use the acmart format, with the acmsmall sub-format for ACM proceedings. For details, see:

[http://www.sigplan.org/Resources/Author/#acmart-format](http://www.sigplan.org/Resources/Author/#acmart-format)

It is recommended to use the review option when submitting a paper; this option enables line numbers for easy reference in reviews.


## Who is involved?

Unsound is currently bootstrapped by [Marco Servetto](https://people.wgtn.ac.nz/marco.servetto/about) and [Jan Bessai](https://noprotocol.net/jan/).
You can chat with us in the [unsound-workshop channel](https://discord.gg/2RkFdC5Xu3) on Discord.

