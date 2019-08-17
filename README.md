# Governance rules regulating the organization

### TL;DR
The **claw-project** organization (which includes all the repositories under [claw-project](https://github.com/claw-project) is run by
the lead maintainers and administrators of its repositories. Decisions are made
by consensus whenever possible. If consensus is not possible, the lead
maintainer of the relevant repository has the final say. Lead maintainers
cannot be removed unless they leave or hand over the repository to someone else.
However, repositories can be forked and removed from the organization.
The entire organization is run by consensus of its lead maintainers and
administrators.

###  Organization Governance
This document defined the rules and processes through which the
**claw-project** community makes decisions and shares control and leadership.
The governance model was designed to follow the spirit and tradition of
open source by embracing consensus, forking, and individual ownership as its
building blocks.

### Principals
* **claw-project** is an open, inclusive, and tolerant community of people
  working together to build open-source softwares.
* We value diversity of individuals and opinions, and seek to operate on
  consensus whenever possible.
* We strive to maintain a welcoming, including, and harassment-free environment
  throughout the organization, regardless of the form of communication.
* When consensus is not achievable, we defer to the individual owners of each
  repository to reach a conclusion; the powers of the individual owner are kept
  in check by the ability of the community to fork and replace its dependencies
  on the individual forks.

#### Core and Community repositories
Each organization repository belong in one of two groups:
* Core - the **claw-compiler** repository as well as any repository it depends
  on.
* Community - any repository **claw-compiler** does not depend on. Might be
  useful tools or extension around the **claw-compiler**.

#### Lead maintainers
Each repository is assigned a lead maintainer. Lead maintainers act as the
repository's BDFL (benevolent dictator for life) and are responsible for the
daily operations of the repository, for seeking consensus, and for making the
final decisions when consensus cannot be achieved. For repository, they have the
final say on releasing new versions.

Lead maintainers cannot be removed unless they leave, assign their position to
someone else, or have become inactive for 30 days and fails to respond to
attempts to communicate, at which point a new contributor will assume
responsibility for the repository. There are no other ways to remove a lead
maintainer as long as the repository remains part of the **claw-project**
organization.

The **claw-project** organization is managed by the lead maintainers and
administrators of the core repositories. The organization is divided in two
groups based on the designation of each repository (core and community):
* **Core contributors** - are those who maintain and contributes actively to the **claw-compiler** repository or one of its   
  dependencies. Core contributors work together to guide the core of the compiler framework, make decisions about releases and 
  breaking changes, and are responsible for the daily maintenance of the core repositories.
  They also decide to accept or create new repositories, as well as remove
  repositories from the organization. The core contributors operate on
  consensus only on all matters not specific to an individual repository.
  When no consensus is possible, each core contributor has the final say over
  the repositories they lead.
* **Community contributors** - are all the contributors that are not part of the
  **Core contributors**

#### Administrators of Repository
Each repository has 1 to N administrators. The lead maintainer is the first
administrator of a repository.
Only administrators have the rights to merge PRs into the master branch.
* **Becoming an administrator** - trusted contributors to a repository can
  join the administrator group when 2/3 of the current administrators of the
  repository agree.

#### Institution in Core contributors
Institution contributing actively to one of the core repository should have
one of its members as one of the administrator of the repository they
contribute to.
This nomination is not implicit and relies as well on the **Administrators of
Repository** rules.

#### Change in the rules
The current organization rules can be change if 2/3 of the lead maintainers and
administrators agree on the change.
