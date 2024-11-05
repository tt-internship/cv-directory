# cv-directory
**A CV directory, used for easy mix and match when playing CV bingo**

[Join the ciscussions on this idea](https://github.com/tt-internship/cv-directory/discussions)

## Problem
The issue is that in consulting, regardless if that is in context of a bureau or if your are a freelancer, you often engage in assignments based on matching a consultant's CV up against a specific request from a client. This way of running a business obviously lead to a very specific requirement that each consultant's CV must be detailed and updated at all times. Something that is considered a tedious and borring task for most consultants. But the problem is deeper than that; when a consultant is preseted as a potential hire for a specific assignment, it's most likely that it's not the entire CV that can be presented. It must be carefully adapted to each single bid. Somthing that is also considered tedious and boring. And as if that wasn't enough; It's likely that the information needed is not yet in the consultnat's CV. So for this occasion the CV needs to be updated, now! Somthing that most consultants finds a disturbance since they are probably in the middle of something else. And to top it up, it's likekly that the format, the look'n'feel of this CV carefully compiled for the occassion needs has special requirements. The skin of a certain department, the file format sent to the client, the lay-out, short- or long version...

## Solution
One solution is to break the consultant's CV op in smaller reusable snippets, sepearting the content from the lay-out and the context, and then make all this content available as options which can then be filtered and marked for relavancy. When a CV is compiled it's a _version_ of that consultant's CV and stored and version controlled as such. When the content is a match the lay-out and ofrmat is applied from a template format. It could be a content languages such as `MarkedDown` stitched togeter using a template language such as `liquid` to generate a generic format, which can then be styled using a formatting language, such as `CSS` and tuend into a (file) format ofg you own choice.

The CV content data must be in a searchable database (could be a relational database or a document (no-sql) database and an interface must be built to search stitch and filter this content together into a final result.

## Value
The value such a solution would create would be to enable a consultant to maintain only the content og a CV and not care about the lay-out at all. The bid managers would have a central system to search, match and fileter from and the various designs and templates couldbe endless.

## Features
A list of poissible additional features could be.

- Import content to your CV from an import of
    - your LinkedIn Profile
    - Word documents
    - PowerPoint slides
    - ...other sources
- Extrac all your CV data in format you can own (e.g. take with you if you change job)
- Sync up you LinekdIn profile with (selected) content from your CV
- Build personas - Combine content from more CV's into made-up imaginary CVs
- Build a free on-line tool where all persons could maintain their personal CV and companies could then be allowd to search and utilize the data of their own employees or freelancers.

## Entities
Consultant, CV, bid-manager, template, assignment, filter, version, search, match, snippets, content, lay-out, (file)format.

## Technology
Free of choice, but you will have to argue you choice.
