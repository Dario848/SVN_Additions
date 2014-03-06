SVN_Additions
=============

Addional utils for SVN 1.7


<b>post-commit_slack</b>

This snippet enables the post-commit SVN operation and notification through Slack service (https://slack.com). Information of commit is drived by payload JSON and POST operation. Tested on Centos 6.4 with SVN 1.7. Lib perl-JSON is required. File must be copied into /myrepo/hooks directory and named "post-commit".
