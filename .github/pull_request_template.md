If you want to submit an unfinished piece of work in order to get comments and discuss, please mark the pull request as a draft and ping the repository maintainer.

**Please address only one topic or issue per pull request! Many small PRs are much easier to review and merge than one large PR.**

Before merging, all changes and new functionality should be marked in the CHANGELOG file, but feel free to just leave your CHANGELOG notes in the PR description, to avoid merge conflicts with other requests modifying that file. The maintainer will add these CHANGELOG notes for you if you do so.

Before considering your pull request ready for review and merging make sure that all of the following are completed (please keep the clecklist as part of your PR):

- [ ] The code is properly formatted and commented.
- [ ] Substantial new functionality is documented within the docs.
- [ ] All new functionality is tested.
- [ ] All of the automated tests on github pass.
- [ ] We recently started enforcing formatting checks. If formatting issues are reported in the new code you have written, please correct them. <small>There will be plenty of old code that is flagged as we are slowly transitioning to enforced formatting. Please do not worry about or address older formatting issues -- keep your PR just focused on your planned contribution.</small>


If possible, keep your git history not too wild (rebase and squash commits, keep commits small and semantically separated) so that review is easier.