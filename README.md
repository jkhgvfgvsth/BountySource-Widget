# BountySource Markdown Widget Tutorial

## The Bounty URL
Bounty URLs are structured like using:
https://www.bountysource.com/issues/{number}-{name}/

### Example:
https://www.bountysource.com/issues/76879471-example

76879471 = {number}

example = {name}


Sometimes it auto-shortens longer names.

## Adding Widget:

Add Widget like this:

```'[![Bountysource](https://api.bountysource.com/badge/issue?issue_id={number})]({bounty-URL})```


Example:

```[![Bountysource](https://api.bountysource.com/badge/issue?issue_id=76879471)](https://www.bountysource.com/issues/76879471-example)```


Which looks like:
[![Bountysource](https://api.bountysource.com/badge/issue?issue_id=76879471)](https://www.bountysource.com/issues/76879471-example)

**Note**: This example should work everywhere markdown is supported :)
