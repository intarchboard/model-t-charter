
# Draft charter for an IAB program on the Internet threat model (model-t)

RFC3552/BCP72 describes the threat model that has been used in Internet protocol
design. Since that was written however, the world has changed in terms of the
threats experienced and in terms of how protocol endpoints are implemented and
deployed.  It is therefore timely to re-consider the threat model used in the
design of IETF protocols, and there appears to be sufficient interest in doing
so to justify an IAB program on this topic.

The model-t program provides an open venue for analysis of the Internet threat
model and environment and has as a goal to produce a potential update to BCP72 
that defines an Internet threat model that better matches today's reality and/or 
better describes the current threat environment. Specifically,
the intent is to document why an update is needed and provide a suggested 
update that could be considered by the IETF. A potential BCP72 update would
likely extend the set of threats considered. Reducing the protection offered 
by current comsec mechanisms is a non-goal. Similarly, re-consideration of 
the parts of BCP72 that are outside the very narrow part on Internet threat
model and the current threat environment are not in scope. (Should there be
a desire within the program to do more, then consideration could be given
to extending the scope and phasing the work, but initially, the scope is 
limited as  described here.)

The potential update to BCP72 would be text offered to the IETF for
consideration - it is not within the IAB's remit, nor that of an IAB program,
to directly modify a BCP. Nonetheless, an IAB program offers a good venue for
this work, as it perhaps allows for more focus on the evolving
architecture aspect within this space, compared to an IETF working group that 
aims to meet more specific milestones.

Updating BCP72 requires text that can be used by anyone developing an IETF
specification. This imposes significant constraints on that text in terms of
length, simplicity and the background knowledge required for the text to
produce useful results.  The program is therefore also likely to produce other
documents (as RFCs or otherwise) that motivate or provide background materials
to justify or further elucidate the proposed update to BCP72. Those background
documents don't have to adhere to the same constraints as an update to BCP72.

There is relatively broad agreement that the roles and trustwortiness of different
endpoints in a protocol exchange are important considerations. In specific cases there may be
quite different perspectives on the tradeoffs involved, e.g., to
what extent privacy, information centralisation, or the needs of
enterprise networks should be considered as the highest priority.  And
no doubt, other equally valid perspectives exist. The model-t
program is not a venue for attempting to determine the one true
perspective from which to tackle specific priorities. Our hope is that,
regardless of what one considers highest priority, 
there is joint interest in taking these issues into consideration
in protocol work, so that consensus for including this consideration
in an updated BCP72 could be reached (in the IETF).

Participants of the program are drawn from the IAB and the rest of the
community. Participation in this program is open to all interested
parties, and considered analysis of diverse inputs is important. The
IAB selects chairs for the program that are expected to facilitate
discussions. Specific individuals may be invited to participate on
particular topics from time to time based on their expertise without
needing to commit to a long-term engagement.

Work is carried out on the model-t@iab.org mailing list that is open to any
subscriber.  Virtual meetings of the program are announced on the mailing list 
and physical meetings during an IETF meetings will, as appropriate, be published on 
the IETF meeting agenda (possibly as side-meetings).

The program is created for an initial six months, after which
the IAB will review progress. 

Expected outputs from the programmme include:

- RFCs and other documents proposing, justifying and explaining new threat
  models and the current threat environment
- RFCs and other documents analysing how BCP72 matches (or doesn't match)
  today's reality
- Text to offer to the IETF as a possible update to BCP72

The IAB are happy to get community feedback on this program charter (but work
has already started informally) either on architecture-discuss@iab.org, on
the model-t@iab.org list or via this github repository. [1]


[1] https://github.com/intarchboard/model-t-charter/blob/master/model-t-charter-00.md

