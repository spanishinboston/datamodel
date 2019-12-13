# datamodel

- “Type”, <categorical>, Type of FP, [“Lexical” | “Phonological”]
- “Value”, <string>, Value of the FP, [“am” | “ah” | “em” |“eh” |  “um” |“uh” | any lexical pause]
- “VowelQuality”, <categorical>, Quality of the vowel when it pertains to a phonological pause so that vowel formants can be extracted
- “SilencePresence”, <categorical>, Presence or Absence of a Silence after an FP
- “SilenceDuration”,  <numerical>, Duration of the silence after the FP
- “PositionInUtterance”, <categorical>, Position of FP in Utterance, [“Pre” | “Internal” | “Post”]
- “PreviousVerb”, <categorical>, Previous Inflected Verb
- “FollowingVerb”, <categorical>, Following Inflected Verb
- “IntoUnits”, <numerical>, Duration of the Intonation Unit FP belongs to (stop time-start time of IntonationUnit)
- “LexItemsIU”, <numerical>, Number of lexical items (words) in the IU, excluding the pause and any false starts. 
