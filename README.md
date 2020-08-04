# Oppressive Language

**Why use a metaphor when a direct description is both succinct and clear?**

The Internet Engineering Task Force (IETF) document titled [Terminology, Power, and Oppressive Language](https://tools.ietf.org/id/draft-knodel-terminology-00.html) argues for and describes alternatives that shift specific language conventions used by RFC Authors and RFC Editors to avoid oppressive terminology in the technical documentation of the RFC series.

Complex and subtle configurations of sexist, racist, or ethnocentric language used in technical conversation, documents, or code can derail or interfere with one's ability and desire to comprehend and follow important information.

This repository is intended to be an open source collection of oppressive language used in the technical vocabulary and recommends more appropriate terminology.

## Principles

- Technical documentation is intended to live in perpetuity. Societal attitudes to oppressive language shift over time in the direction of more empathy, not less.
- That oppressive terms in technical documentation are largely hidden from the larger public, or read only by engineers, is no excuse to ignore social-level reactions to the terms. If the terms would be a poor choice for user-facing application features, the terms should be avoided in technical documentation and specifications, too.
- The digital technology community has a problem with monoculture. And because the diversity of the technical community is already a problem, a key strategy to breaking monoculture is to ensure that technical documentation is addressed to a wide audience and multiplicity of readers.
- The technical community is not entirely comprised of only white men. Eradicating the use of oppressive terminology in technical documentation recognizes the presence of and acknowledges the requests from black and brown engineers and from women and gender-non-conforming engineers to avoid the use of oppressive terminology.


## Terminology

### Master / Slave

*Master-slave is an oppressive metaphor that will and should never become fully detached from history. It has strong reference to the practice of slavery.*

**Recommended alternatives:**

- Primary-secondary
- Leader-follower
- Active-standby
- Primary-replica
- Writer-reader
- Coordinator-worker
- Parent-helper

**References:**

- https://tools.ietf.org/id/draft-knodel-terminology-00.html#rfc.section.1.1
- https://en.wikipedia.org/wiki/Master/slave_(technology)

### Blacklist / Whitelist

*The metaphorical use of white-black to connote good-evil is oppressive. While master-slave might seem like a more egregious example of racism, white-black is arguably worse because it is more pervasive and therefore more sinister.*

**Recommended alternatives:**

- Blocklist-allowlist
- Block-permit

**References:**

- https://tools.ietf.org/id/draft-knodel-terminology-00.html#rfc.section.1.2
- https://en.wikipedia.org/wiki/Blacklisting
- https://en.wikipedia.org/wiki/Whitelisting

### Brown Bag

*The phrase "brown bag" can be associated with the Brown Paper Bag Test, a form of racial discrimination. The test was allegedly used to ensure that only those with a skin color that matched or was lighter than a brown paper bag were allowed admission or membership privileges.*

**Recommended alternatives:**

- Lunch & learn

**References:**

- https://en.wikipedia.org/wiki/Brown_Paper_Bag_Test
- https://www.ferris.edu/HTMLS/news/jimcrow/question/2014/february.htm

### Male / Female

*Many cable connectors are assigned the labels male/female, in reference to whether they are the insertive or receptive component. This naming convention makes an inappropriate reference to genitalia and is exclusive of the LGBTQ+ community.*

**Recommended alternatives**
- A / B
- Plug / Socket
- Sword / Sheath

**References:**
- https://www.lastwordonnothing.com/2015/11/27/a-modest-proposal-for-re-naming-connectors-and-fasteners/

## Contributing

This repository is intended to be an open source collection of oppressive language used in the technical vocabulary and recommends more appropriate terminology. Contributions are welcomed and encouraged from the community.

When adding an item to the **Terminology** section above, please use the following format:

```
### <term>

*<explanation of why this term is oppressive>*

**Recommended alternatives:**

- <alternate 1>
- <alternate 2>
- ...

**References:**

- <link 1>
- <link 2>
- ...
```

## Resources

[Terminology, Power, and Oppressive Language (IETF)](https://tools.ietf.org/id/draft-knodel-terminology-00.html)

[Metaphors in man pages (Julia Evans)](https://jvns.ca/blog/2020/05/08/metaphors-in-man-pages/)

[Easily rename your Git default branch from master to main](https://www.hanselman.com/blog/EasilyRenameYourGitDefaultBranchFromMasterToMain.aspx)
