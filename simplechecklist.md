% TAGS [PREVENTION]  [BUSINESS]

# Simple checklists

## Problem

Most security checklist are time consuming and an insult for security professionals.

## Solution

Use simple proven checklists. And instead of using AI, just use your own brain and experience. Its far better and aware of the context.

A modern information system environment can be characterised by a number of elements:
* Hardware
* Software
* Databases
* Networks
* Processes
* People
* Vendors (e.g. Cloud Service Provider)




| Information System element | Secure means | A simple measurement |
| :---- | :---- | :---- |
| Hardware | Choice trusted hardware. E.g. a vault. | Never trust hardware. |
| Operation System | Choose a trusted operating system. | Never trust an operating system, but using an operating system that is secure by design is a good start.  |
| Software  | Make only use of trusted software. | Only use signed software and if possible use [trusted build](https://nocomplexity.com/documents/securityarchitecture/prevention/reproduciblebuilds.html#reproducible-builds)  |
| Databases (Storage)  | Make only use of trusted storage systems | Never trust your database. This accounts for Cloud but also for on-premise hosted databases.  |
| Networks  | Always use a trusted network. | In reality a network can never be 100% trusted. The potential vulnerabilities , even with a trusted internal network, will always be larger than you can imagine.  |
| Processes | Easy processes are less vulnerable for fraud and manipulation. | Keep the process simple. Complex processes requires complex automation, often over various organisational boundaries and many systems. Simple always wins. |
| People | Train people. Continuously.  | Use different authorisations for different users and different roles. |



- Create simple validation template in markdown (risk based\!)  
- Testing against new CVEs:

Patching a CVE as quickly as possible is critical as published PoC exploit code is typically weaponized. When a new CVE is out you are vulnerable. It does not matter if exploit code is already published on the Internet or not. Assume that Criminals are misusing the CVEs already.


:::{admonition} And use good secure software development practices! Examples of good secure practices are: 
:class: tip, dropdown

* The gold-standard for these practices are the NIST Secure Software Development Framework (SSDF) ([https://csrc.nist.gov/Projects/ssdf](https://csrc.nist.gov/Projects/ssdf) )  or 
* the Supply Chain Levels for Software Artifacts (SLSA). ([https://slsa.dev/](https://slsa.dev/) )

Or find more simple checklists in the [Open Security Reference Architecture](https://nocomplexity.com/documents/securityarchitecture/prevention/simple-checklists.html#simple-checklists)
:::