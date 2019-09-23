# Governance rules regulating the organization

### **claw-project** Organization and administrators
The **claw-project** organization (which includes all the repositories under 
[claw-project](https://github.com/claw-project) is organized by the **claw-project**
administrators. The founding organizations ETH Zurich and MeteoSwiss, and organizations which have
sign a collaboration agreement have at least one  **claw-project** administrator.
Organization administrators nominate lead maintainers and administrators of the different repositories.  
Decisions are made by consensus whenever possible. If consensus is not possible, the organization 
adminitrators have the final say. **claw-project** adminitrators cannot be removed unless 
they leave their organizations or their organization is not part of the CLAW collaboration anymore.

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

Lead maintainers are nominated by the **claw-project** administrators.

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
* **Becoming an administrator** - repository adminitrator are nominated by
the claw-project administrators.

#### Institution in Core contributors
Institution contributing actively to one of the core repository should have
one of its members as one of the administrator of the repository they
contribute to.
This nomination is not implicit and relies as well on the **Administrators of
Repository** rules.

#### Change in the rules
The current organization rules can be change if all the **claw-project** adminitrators agree.
