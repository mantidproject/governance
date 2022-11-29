# Recap actions from previous meeting:

- ORNL had an issue with long workbench start up times. Deleting `~/.cache/fontconfig` avoided the problem.

# Agenda
- General Updates:
  - 6.5.0 release went out on 19th October without fix for above startup issue.
  - No .rpm/.deb released for the first time.
  - Timelines for [next release](https://github.com/mantidproject/mantid/milestone/112)
- Martyn leaving the ISIS Data Reduction team (but not ISIS). 
  - Electing a new chair
- How can we best proceed with updates such as a change of formatter: [#34743](https://github.com/mantidproject/mantid/pull/34743)
  1. Mass update of all files: Timing is hard, merge conflicts for unmerged PRs increases likelihood of other errors creeping in
  2. Pre-commit updates files as they are changed: Gentler approach, improve as we go. Downside is reviews are more challening as PRs have changes from formatter too. Needs have deadline for full switch at some point.
  3. Change sections of the repository over the course of the release
  4. (comment from Simon Heybrock): 'Software Engineering at Google' has a whole chapter on this. They use something they call 'sharding'. See https://abseil.io/resources/swe-book/html/ch22.html for details.
- linode server costs
- AOB
