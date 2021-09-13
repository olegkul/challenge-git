![Outlier.org](https://i.imgur.com/vJowpL1.png)

---

# Step for fixing challenge

$ git clone https://github.com/outlier-org/challenge-git.git

$ git checkout --track origin/feature/base64

$ git checkout --track origin/feature/useragent

$ git checkout feature/base64

$ git rebase feature/useragent

fix conflicts on project

$ git rebase --continue

$ git checkout master

$ git merge feature/useragent

$ git merge feature/base64

$ git log
commit 96360171a317c678c9ee00162b98ab46d0ee5a8b (HEAD -> master, feature/base64)
Author: David <david@outlier.org>
Date:   Fri Jun 14 12:26:08 2019 -0700

    feat: add base64 endpoint

commit 33e41571c2ceeb0e61b456a7678753a57fc6dd91 (origin/feature/useragent, feature/useragent)
Author: David <david@outlier.org>
Date:   Fri Jun 14 13:26:16 2019 -0700

    feat: add user-agent endpoint

commit 7f2f4661c7cf351317ecedb0f9da22979a61637b (origin/master, origin/HEAD)
Author: David <david@outlier.org>
Date:   Fri Jun 14 12:26:08 2019 -0700




