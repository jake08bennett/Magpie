Exploration: Using the API:

1)What value is returned by indexOf if the substring does not occur in the string?
		The value which is returned if the substring is not in the string is -1.

Exploration: Understand the new method:

findKeyword("She's my sister", "sister", 0);

| Iteration | Psn | Before | After |
|-----------|-----|--------|-------|
| 1         | 9   | " "    | " "   |

findKeyword("Brother Tom is helpful", "brother", 0);

| Iteration | Psn | Before | After |
|-----------|-----|--------|-------|
| 1         | 0   | " "    | " "   |

findKeyword("I can't catch wild cats.", "cat", 0);

| Iteration | Psn | Before | After |
|-----------|-----|--------|-------|
| 1         | 8   | " "    | "c"   |
| 2         | 19  | " "    | "s"   |

findKeyword("I know nothing about snow plows.", "no", 0);

| Iteration | Psn | Before | After |
|-----------|-----|--------|-------|
| 1         | 3   | "k"    | "w"   |
| 2         | 7   | " "    | "t"   |
| 3         | 22  | "s"    | "w"   |