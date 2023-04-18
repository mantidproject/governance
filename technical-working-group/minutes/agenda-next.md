# Recap actions from previous meeting:


# Agenda
- Upgrading python version update (Tom)
- Update on slow file browser (Tom)
- Should we be pinning all dependencies for release versions? (Tom)
- Managing dependecy updates (Tom)
- Have ILL had a chance to look at the MacOS ansible scripts?
- Event filtering update (Pete)
- Review [roadmap](https://github.com/mantidproject/roadmap/projects/1)
- AOB

# Minutes
Attendees: Guest, Hampson, Pellegrini, Perenon, Peterson

- No progress on changing from python 3.8 to 3.10. The move will wait until after v6.7 release.
- Slow file browser PR will be circulated "soon" for testing
  - built package installed via `mamba install -c "thomashampson/label/gtk-test" mantidworkbench`
- https://github.com/mantidproject/mantid/issues/35461 will be resolved by avoiding jupyter qtconsole v5.4.2
  - Tom will announce the workaround for users on forum.mantidproject.org
- ILL will look at osx/ansible script next week after their cycle ends
- ISIS will have 2 additional osx builders in the next month after configuring
- Event filtering will be ready for unscripted testing in the next two weeks. The remaining feature is to update the sample log viewer which will be done before the release.
