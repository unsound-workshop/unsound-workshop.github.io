## Unsound: Sources of Unsoundness in Verification

Software and proof verification has grown significatively in the last 15 years.
Growth has come to the point where verification systems are complex and manually proving the soundness of those verification systems sometimes exceeds what a single research group can understand and verify as correct. 

Even formally defining soundness can be challenging and its definition is varying from system to system. Specific research groups can have very specific notions of soundness they focus on, but those can diverge from what the users expect, especially if the users come from a different verification environment or they are approaching verification for the first time.
 
Participants to Unsound will be able to share their experience and exploits on how different verification tools can either be broken or expose confusing behaviour, likely to be unexpected by users.
We think this would be greatly beneficial not only because it will help all of us to iron out those unsoundnesses but also because it will facilitate understanding of the foundational differences between the assumptions of the various research lines.

The current academic environment encourages us to talk about the success case of our work. In this workshop we want to address and learn from failure cases and we want to reinforce the bedrock of our understanding.
In practice, when we divert our focus to a specific aspect of verification
 we may (understandably) be less precise.
For example, a line of research focusing on aliasing control in OO may be less precise when considering the implication in other areas, like termination.
We believe that learning from the issues of many verification projects can broaden the attention of researchers to topics which so far escaped their focused area of research; e.g., from only type correctness to also avoiding stack overflows.

We believe that this environment would be particularly beneficial for young researchers that are in search of open questions in verification. This may provide a motivation to deep dive into the details of any particular tool, or to expand their individual area of expertise to get a wider and more objective and critical view of the whole area of verification.

We also wonder if in our fast expansion we accidentally glossed over some fundamental issue in verification, and if our mistake has now become engraved into the established wisdom and it is sometimes uncritically assumed as a valid reasoning stepping stone.

We are particularly interested in sources of unsoundness that are accidentally shared by many different unrelated research lines, and to develop an understanding on why this is the case.
