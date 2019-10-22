# test-dvcs-connector

A repository that helps me to test the Jira DVCS connector.

DVCS connector code: https://stash.atlassian.com/projects/FUSE/repos/jira-dvcs-connector-server/browse

Setup:
1. Get Jira running with the DVCS connector (see the project's README for instructions)
1. Follow these instructions using `http://localhost:2990/jira` as the URL: https://confluence.atlassian.com/adminjiraserver/linking-a-bitbucket-or-github-repository-with-jira-938846899.html
1. Start an `ngrok` tunnel to port 2990
1. In GitHub, replace the application's URL with the `ngrok` tunnel URL (plus `/jira`, of course!)
1. Reference issues!! (For instance, issues TST-1 to TST-4 already exist)


