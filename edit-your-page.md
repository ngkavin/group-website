# How to edit your personal page

1. Fork the group website repo https://github.com/uw-echospace/group-website (the "upstream")
2. Create a branch with a meaningful name, such as `add-ID-page` where `ID` is your github account or UW NetID
3. Find your UW NetID under `/content/authors/NETID`
4. Edit `/content/authors/NETID/_index.md`
    - Update various standard fields
    - Add a blurb about yourself and your project(s) below the `---` line
5. Replace `/content/authors/NETID/avatar.jpg` with your picture
6. Create a PR to the `master` branch of the upstream repo
7. The PR will trigger a build that goes to a temporary site shown on a comment to your PR, so you can tune your content there.
9. Tag @leewujung to merge your PR to master. Once merged, your info will be updated on the official page.
