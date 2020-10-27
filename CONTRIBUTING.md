Thank you for taking interest into contributing to the Lufthansa Systems Technology Radar!

# How to handle changes to the Technology Radar
If you want to propose a change to the Technology Radar, follow the process below:
1. Open an issue on this repository, describe your proposal according to the rules in the Issues section
1. Discuss the proposal in the issue, reach consensus with the relevant stakeholders
1. Create a branch for the proposed change (see the rules below)
1. Check out the [Thoughtworks Technology Radar Example CSV](https://docs.google.com/spreadsheets/d/1M7eklh1oDrQpn9c0MTBHYJIG8apr5ulax7fPwVS7_-s/edit) as a baseline, and do your changes in the [Lufthansa Systems Tech Radar.csv](Lufthansa%20Systems%20Tech%20Radar.csv) file in the form of small commits (see commit rules below)
1. Open a PR whenever you feel you're ready, and wait until you get approval for the merge
1. Merge your changes, repeat the process from the first step for the next change proposal ;)

## Issues
- Feel free to open issues on this repository for any reason
- When opening an issue, please spend some time checking whether the same issue has already been opened by someone else
- Give a meaningful title for your issue
- Use one of the existing labels on your issue
- Please provide an explanation, your proposal, and possibly some technical background for the issue

## Branching
- Always create branches for your work
- Branch names should suggest the change, and contain lowercase alphanumerical characters, or the minus sign (-), eg: `hold-oracle-db` is a correct branch name, but `blabla/meaningless_info` is not

## Commits
- Please provide meaningful commit messages next to your commit, in English present term, eg: "Move Oracle DB to the hold ring" is a meaningful and valid commit message
- Avoid past term in the commit messages, keep the history consistent
- Multiline commit messages are permitted, with the restriction that the first line shall always be a meaningful, English sentence, using present term
- Multiple smaller commits are preferred over huge commits

## Pull Requests
- If possible, associate your Pull Request with an existing issue
- Keep your PR's small, and focus them on one change
- Describe the changes inside the PR description
- If a revier asks for changes, please mark it as resolved after it has been addressed
- PR's with unresolved issues will not be merged
- PR's must pass the validations that are done in GitHub actions to be able to merge
- Always delete the source branch after merging a PR

## General rules for text files
- Use UTF-8 file encoding
- Use unix-style line-endings (single "\n" sequence at the end of the line)
- Aside from the line terminator sequence, the ASCII horizontal space character (0x20) is the only whitespace character that appears anywhere in a source file. This implies that:
    - All other whitespace characters in string and character literals are escaped
    - Tab characters are not used for indentation.
- Add newline at the end of every file
