---
title: How the TDA team works
---


# How the TDA team works

The TDA team is made up of members across multiple Arup regions and parts of the organisation.

Currently the team predominantly works under the Global Automation MS Team site.

We have some specific discussion channels to collaborate with other developers across Arup.
- [TDA App Developers Community](https://teams.microsoft.com/l/channel/19%3a8f8cda5751444d79973b884a97de3de2%40thread.skype/450%2520-%2520TDA%2520App%2520developers%2520community?groupId=ce4aa135-8063-48df-aad3-997f92c09aca&tenantId=4ae48b41-0137-4599-8661-fc641fe77bea)
- [TDA GH Developers Community](https://teams.microsoft.com/l/channel/19%3a062dc9ef5a1c496a898530c723ad491f%40thread.skype/451%2520-%2520TDA%2520GH%2520developers%2520community?groupId=ce4aa135-8063-48df-aad3-997f92c09aca&tenantId=4ae48b41-0137-4599-8661-fc641fe77bea)


::: warning Under construction
To be updated with more content
:::

<!-- 
The Speckle team is still working out the workflow used to identify, priortize, deliver and support the various Speckle software components. As such, the below process is subject to change - please make any suggestions to David de Koning!!

## Discovery

### Step 1: Inputs into the discovery process are:

**User Outreach:**

* Bug reports
* feature requests / requests for help
* Spontaneous user feedback (e.g. emails, Teams threads...)
* Deliberate user feedback (e.g. interviews)
* Survey results

**Instrumentation:**

* usage stats
* bug reports

**Industry and Market Research:**

* reading books about broad trends
* attending conferences, meeting others in the industry
* Twitter

### Step 2: Collecting, Sorting and Filtering

There is a Miro board for collecting ideas, sorting them, and then identifying opportunities that merit further study. https://miro.com/app/board/o9J_lZR_a8g=/

At the left of the board, ideas are placed. They can be complaints, user stories, free form ideas, etc...

The product team will review these ideas regularly and sort them into clusters in the centre of the board.

Finally, opportunities will be identified on the right side of the board. This is unstructured for now, but may become an Opportunity Tree.

Once an opportunity is identified, someone will be asigned to flesh it out, get feedback from the dev team, users, etc... to identify various possible solutions, and shape the work into something that can be prioritized, evaluted on a cost-benefit basis, etc... Documentation for each opportunity will be stored on the Speckle Teams [Dev channel](https://teams.microsoft.com/_#/files/Dev?threadId=19%3A234d50c544c74736a3e89430f0e5b936%40thread.skype&ctx=channel&context=Focus%2520Areas&rootfolder=%252Fsites%252FSpeckleStructuresDevelopment-Dev%252FShared%2520Documents%252FDev%252FFocus%2520Areas)

**NOTE: the transition between a written pitch and issues in Jira is not yet nailed down. The pitch champion and the dev who is picking it up should have a discussion and decide how to represent it in Jira.**

### Step 3: Developing

The Speckle team currently uses a release-centric Kanban approach to define priorities and push progress. All Speckle development is tracked in a single Jira project: https://ovearup.atlassian.net/jira/software/projects/SPEC/boards/384

The Speckle backlog is not currently very organized or meaningful. It will be replaced by the documents described in Step 2 above.

We only use the following organizational features of Jira:

1. Board
  - all active development should be represented by a ticket on the board
  - all team members are encouraged to add and update tickets to reflect their current work and progress
  - All team members should provide a status update at the end of the week (Friday) by commenting on the relevant tickets. The intent is not to update all tickets weekly, but to organize the status updates with the ticket.
  - all work on all Speckle components sits on the same board
2. Tags
  - each ticket must be tagged with the component it relates to (e.g. `server`, `SpeckleGSA`, `grasshopper`, etc...), so that we can filter the board to only look at one component
3. Releases
  - tickets will be grouped into releases to identify what work is intended to be included in the next release
  - Small changes, bug fixes, etc... can be added to releases as the work progresses, but development should focus on releasing software as quickly as possible
  - Releases will be named as follows `ComponentName YYYY.n Subject`
    - `ComponentName` is the name of the specific software, e.g. Grasshopper, Revit, GSA, etc...
    - `YYYY.n` is the year and the sequence number of the release. Releases will be given a semver name during the release process, but we will track formal releases in Jira sequentially through the year. This means that a hot-fix release will not require renaming lots of things in Jira. When the order of future releases is not yet determined, placeholder releases can be created with the `n` set to `?`.
    - `Subject` describes the main aim of the release. If a release has multiple aims, it should probably be broken down into multiple releases.
    - tickets for future releases (not in active development) can sit in the backlog
  - A release captain should be designated for each release. They will be responsible for focusing the team on the release, and preparing builds that can be tested. They release captain will coordinate final timings with the Product Manager.

## Step 4. Bugs!!

(This section is a first draft)

User reports should be recorded as tickets in Jira, using the `Support Bug` type. This ticket has a field for `Reporting User` - please enter the name of the user who reported an issue, and fill in other information as required.

If there is any supporting documentation, please create a folder in the Speckle teams: `Dev > Focus Areas > Bugs > SPEC-nnn` (where `nnn` is the ticket number). This can be created at any time during bug resolution.

The steps for bug resolution are: Investigate -> Review -> ready to fix. Unless the fix is trivial, clear the bug with the Product Manager (David) before fixing it. It may be less important than whatever else you might work on!!

Bugs should not necessarily be forwarded directly to the developers to investigate. The first responder should first reproduce the bug and identify when and where it appears. -->