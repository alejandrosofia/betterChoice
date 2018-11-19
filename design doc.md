# Design Doc

[Better Choice](http://apricots.io/betterchoice) aims to make voting easier. Information for federal, state and local elections tend to be scattered all over the place, and it can be overwhelming for voters.


## Goals

* Show upcoming election date
* Compile candidates on the ballot of a voter, as determined by their address
* Allow voter to save their selections of candidates
* Show polling location
* Remind user to vote


## Screens

| Main                                 | |
| :----------------------------------: |-|
| Sign up / Login in / Skip            | Only shown to logged out users |
| &#x2193;                             | |
| **Address Input**                    | |
| Enter voting address                 | Skip if logged in: use address from user object |
| &#x2193;                             | |
| **Voting profile**                   | |
| Address, voting divisions            | Only shown if first time, or there is no upcoming election |
| &#x2193;                             | |
| **Election**                         | |
| Date, polling station, contests      | |
| &#x2193;                             | |
| **Contest**                          | |
| Candidates, with stars for favorites | Option to add and delete candidates and only like **one** per open race
| &#x2193;                             | |
| **Candidate**                        | |
| Name, party, bio etc                 | Potentially link to social media and personal websites?

## Supplementary Data

To have richer information earlier in the election cycle, we would compile contests and candidates for each voting division.

For each candidate, we would like to have:

* Name
* Party
* Short bio
* Issue(s) you matched with them on
* Url
* Phone
* Email
* Social channels (e.g. Facebook, Twitter, Instagram)

