Run # Define PowerShell variables from environment variables
All branches in source repository: branch1, branch2, branch3, branch4, dependabot/github_actions/actions/upload-artifact-4, dependabot/maven/biz.aQute.bnd-bnd-maven-plugin-7.0.0, dependabot/maven/com.google.guava-guava-33.3.1-android, dependabot/maven/com.puppycrawl.tools-checkstyle-10.20.0, dependabot/maven/org.apache.maven.plugins-maven-checkstyle-plugin-3.5.0, dependabot/maven/org.apache.maven.plugins-maven-gpg-plugin-3.2.7, dependabot/maven/org.apache.maven.plugins-maven-jarsigner-plugin-3.1.0, dependabot/maven/org.apache.maven.plugins-maven-javadoc-plugin-3.11.1, dependabot/maven/org.apache.maven.plugins-maven-surefire-plugin-3.5.2, dependabot/maven/org.jcommander-jcommander-2.0, dependabot/maven/spring.version-6.1.13, main, other
Checking protection status for branch: branch1
Branch branch1 is protected.
Checking protection status for branch: branch2
Branch branch2 is protected.
Checking protection status for branch: branch3
Branch branch3 is protected.
Checking protection status for branch: branch4
Branch branch4 is protected.
Checking protection status for branch: dependabot/github_actions/actions/upload-artifact-4
Branch dependabot/github_actions/actions/upload-artifact-4 is not protected or an error occurred.
Checking protection status for branch: dependabot/maven/biz.aQute.bnd-bnd-maven-plugin-7.0.0
Branch dependabot/maven/biz.aQute.bnd-bnd-maven-plugin-7.0.0 is not protected or an error occurred.
Checking protection status for branch: dependabot/maven/com.google.guava-guava-33.3.1-android
Branch dependabot/maven/com.google.guava-guava-33.3.1-android is not protected or an error occurred.
Checking protection status for branch: dependabot/maven/com.puppycrawl.tools-checkstyle-10.20.0
Branch dependabot/maven/com.puppycrawl.tools-checkstyle-10.20.0 is not protected or an error occurred.
Checking protection status for branch: dependabot/maven/org.apache.maven.plugins-maven-checkstyle-plugin-3.5.0
Branch dependabot/maven/org.apache.maven.plugins-maven-checkstyle-plugin-3.5.0 is not protected or an error occurred.
Checking protection status for branch: dependabot/maven/org.apache.maven.plugins-maven-gpg-plugin-3.2.7
Branch dependabot/maven/org.apache.maven.plugins-maven-gpg-plugin-3.2.7 is not protected or an error occurred.
Checking protection status for branch: dependabot/maven/org.apache.maven.plugins-maven-jarsigner-plugin-3.1.0
Branch dependabot/maven/org.apache.maven.plugins-maven-jarsigner-plugin-3.1.0 is not protected or an error occurred.
Checking protection status for branch: dependabot/maven/org.apache.maven.plugins-maven-javadoc-plugin-3.11.1
Branch dependabot/maven/org.apache.maven.plugins-maven-javadoc-plugin-3.11.1 is not protected or an error occurred.
Checking protection status for branch: dependabot/maven/org.apache.maven.plugins-maven-surefire-plugin-3.5.2
Branch dependabot/maven/org.apache.maven.plugins-maven-surefire-plugin-3.5.2 is not protected or an error occurred.
Checking protection status for branch: dependabot/maven/org.jcommander-jcommander-2.0
Branch dependabot/maven/org.jcommander-jcommander-2.0 is not protected or an error occurred.
Checking protection status for branch: dependabot/maven/spring.version-6.1.13
Branch dependabot/maven/spring.version-6.1.13 is not protected or an error occurred.
Checking protection status for branch: main
Branch main is protected.
Checking protection status for branch: other
Branch other is not protected or an error occurred.
Protected branches: branch1, branch2, branch3, branch4, main
Migrating protection rules for branch: branch1
url                              : https://api.github.com/repos/sam-org1/s_repo
                                   1/branches/branch1/protection
required_pull_request_reviews    : @{url=https://api.github.com/repos/sam-org1/
                                   s_repo1/branches/branch1/protection/required
                                   _pull_request_reviews; dismiss_stale_reviews
                                   =False; require_code_owner_reviews=False; re
                                   quire_last_push_approval=True; required_appr
                                   oving_review_count=1}
required_signatures              : @{url=https://api.github.com/repos/sam-org1/
                                   s_repo1/branches/branch1/protection/required
                                   _signatures; enabled=True}
enforce_admins                   : @{url=https://api.github.com/repos/sam-org1/
                                   s_repo1/branches/branch1/protection/enforce_
                                   admins; enabled=False}
required_linear_history          : @{enabled=True}
allow_force_pushes               : @{enabled=True}
allow_deletions                  : @{enabled=True}
block_creations                  : @{enabled=False}
required_conversation_resolution : @{enabled=False}
lock_branch                      : @{enabled=False}
allow_fork_syncing               : @{enabled=False}
Branch protection rules applied to branch1 in target repository.
Migrating protection rules for branch: branch2
url                              : https://api.github.com/repos/sam-org1/s_repo
                                   1/branches/branch2/protection
required_status_checks           : @{url=https://api.github.com/repos/sam-org1/
                                   s_repo1/branches/branch2/protection/required
                                   _status_checks; strict=False; contexts=Syste
                                   m.Object[]; contexts_url=https://api.github.
                                   com/repos/sam-org1/s_repo1/branches/branch2/
                                   protection/required_status_checks/contexts; 
                                   checks=System.Object[]}
required_signatures              : @{url=https://api.github.com/repos/sam-org1/
                                   s_repo1/branches/branch2/protection/required
                                   _signatures; enabled=False}
enforce_admins                   : @{url=https://api.github.com/repos/sam-org1/
                                   s_repo1/branches/branch2/protection/enforce_
                                   admins; enabled=False}
required_linear_history          : @{enabled=False}
allow_force_pushes               : @{enabled=False}
allow_deletions                  : @{enabled=False}
block_creations                  : @{enabled=False}
required_conversation_resolution : @{enabled=False}
lock_branch                      : @{enabled=True}
allow_fork_syncing               : @{enabled=False}
Branch protection rules applied to branch2 in target repository.
Migrating protection rules for branch: branch3
Invoke-RestMethod: /home/runner/work/_temp/e6524b5c-7f2e-4f85-869f-45fceae68899.ps1:84
Line |
  84 |      Invoke-RestMethod -Uri $targetProtectionUri -Headers $targetHeade …
     |      ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
     |  {   "message": "Invalid request.\n\nNo subschema in \u0022anyOf\u0022
     | matched.\nFor \u0027items\u0027,
     | {\u0022login\u0022=\u003E\u0022Skanchi09\u0022,
     | \u0022id\u0022=\u003E181991838,
     | \u0022node_id\u0022=\u003E\u0022U_kgDOCtj5ng\u0022,
     | \u0022avatar_url\u0022=\u003E\u0022https://avatars.githubusercontent.com/u/181991838?v=4\u0022, \u0022gravatar_id\u0022=\u003E\u0022\u0022, \u0022url\u0022=\u003E\u0022https://api.github.com/users/Skanchi09\u0022, \u0022html_url\u0022=\u003E\u0022https://github.com/Skanchi09\u0022, \u0022followers_url\u0022=\u003E\u0022https://api.github.com/users/Skanchi09/followers\u0022, \u0022following_url\u0022=\u003E\u0022https://api.github.com/users/Skanchi09/following{/other_user}\u0022, \u0022gists_url\u0022=\u003E\u0022https://api.github.com/users/Skanchi09/gists{/gist_id}\u0022, \u0022starred_url\u0022=\u003E\u0022https://api.github.com/users/Skanchi09/starred{/owner}{/repo}\u0022, \u0022subscriptions_url\u0022=\u003E\u0022https://api.github.com/users/Skanchi09/subscriptions\u0022, \u0022organizations_url\u0022=\u003E\u0022https://api.github.com/users/Skanchi09/orgs
Error: Process completed with exit code 1.
