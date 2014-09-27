# ballotbox

_ballotbox_ is conceived as a stand-alone vote storage system for elections.

Its general goals are similar to a physical ballot box, primarily:

 * secret voting - separating the voter's identity from the stored ballot
 * secure voting - making tampering with ballots difficult without detection

In addition, _ballotbox_ aims to provide limited guarantees that voter only votes once.

## Scope

_ballotbox_ does _not_ aim to:

 * verify the identity of the voter
 * establish the ballot represents a valid vote for a candiate
 * hold any information regarding election candidates
