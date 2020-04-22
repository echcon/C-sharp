# Git Comment Convention

## Branch name
1. First name is [Prefix character][Name of branch(limmit 50 character)]
2. Name of branch will bi clone from source branch.
3. Create pull to request: Only request from Your branch to Source Branch.
4. Ex: [Dev] is branch. Create new branch with Issue news 88. => [IS news 88].
Request merge source: [IS news 88] -> [dev]

## Comment structure
1.	First line is a subject line. It should have size about 50 characters, maximum limit is 80. Subject line is capitalized and hasn't period at the end;
2.	A blank line separates subject from body;
3.	Detailed description of the change in the body, breaking paragraphs where needed.The body should explain what  you did and why vs. how. The body also starts with a capitalized letter. Bullet points are made with an asterisk (*);
4.	In case if a bug tracking system is used, bug Id is line is placed at the very end after a blank line.


## Subject line tags
- [FEATURE]: A new feature (also small additions). Most likely it will be an added feature, but it could also be removed;
- [BUGFIX]: A fix for a bug;
- [STYLE]: Changes in layout, page style and css files;
- [CLEANUP]: Code formatting, improves in code style and readability;
- [DOCS]: Changes to documentation;
- [TEST]: Adding, changing, refactoring tests - no production code change;
- [OTHER]: Anything not covered by the above categories.


## Flags have to be added under certain circumstances
- (!!!) : Breaking change. Significant changes in software architecture or logic, that affect existing features and extentions or change user experience;
- (DB): Changes that require database structure or data to be updated;
- (WIP): Work in progress. This flag will be removed, once the final version of a change is available. Changes marked WIP are never merged.


## Tags usage examples
1. [STYLE] Change size of tag h1
2. [CLEANUP] Few code formating
3. [BUGFIX] Fix bugs 101 and 110
4. [FEATURE] Add new universal system class object
5. (!!!)[FEATURE] Added new class ChartItem
6. (!!!)(DB)[FEATURE] Add new column ApplicationUserID


## Commit Message Example
(!!!)(DB)[FEATURE] Rewrite stored procedure

Additional information about commit changes
- Examble a commit: commentary. [dev][news 88][html, css, config] Change html style with css inline.


## Source
 - [Practice with GIT] (https://github.com/echcon/LinuxTut/blob/master/Git_to_use.md)
