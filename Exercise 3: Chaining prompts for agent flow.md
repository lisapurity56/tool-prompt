## CHANGING PROMPTS FOR AGENT .
Not Machine-Readable

It’s plain natural language.
A program would need brittle string parsing (regex, NLP, etc.) to extract:

Location

Temperature

Condition.


“Paris is experiencing cloudy skies at 18 degrees Celsius.”

“18°C and cloudy in Paris.”

“Currently cloudy, temperature 18.”

Same meaning — different structure.
This breaks automation.
Identify numbers

Detect unit (°C vs Celsius vs degrees)

Handle phrasing variations

Handle word-based numbers (“eighteen”)

This is fragile and error-prone.
