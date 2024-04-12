Process, commands used, and any challenges faced

Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

PS C:\Users\marke> git clone https://github.com/thomaspark/gridgarden.git
fatal: destination path 'gridgarden' already exists and is not an empty directory.
PS C:\Users\marke> cd gridgarden
PS C:\Users\marke\gridgarden> git remote -v
origin  https://github.com/thomaspark/gridgarden.git (fetch)
origin  https://github.com/thomaspark/gridgarden.git (push)
PS C:\Users\marke\gridgarden> dir


    Directory: C:\Users\marke\gridgarden


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         4/12/2024  10:17 AM                css
d-----         4/12/2024  10:17 AM                images
d-----         4/12/2024  10:17 AM                js
d-----         4/12/2024  10:17 AM                node_modules
-a----         4/12/2024  10:17 AM              0 .nojekyll
-a----         4/12/2024  10:17 AM             17 CNAME
-a----         4/12/2024  10:17 AM          34864 favicon.ico
-a----         4/12/2024  10:17 AM          11781 index.html
-a----         4/12/2024  10:17 AM           1089 LICENSE
-a----         4/12/2024  10:17 AM            568 package-lock.json
-a----         4/12/2024  10:17 AM            288 package.json
-a----         4/12/2024  10:17 AM           3174 README.md
-a----         4/12/2024  10:17 AM             40 _config.yml


PS C:\Users\marke\gridgarden> nona index.html
nona : The term 'nona' is not recognized as the name of a cmdlet, function, script file, or operable program. Check
the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ nona index.html
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (nona:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\marke\gridgarden> nano index.html
nano : The term 'nano' is not recognized as the name of a cmdlet, function, script file, or operable program. Check
the spelling of the name, or if a path was included, verify that the path is correct and try again.
At line:1 char:1
+ nano index.html
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (nano:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\marke\gridgarden> code index.html
PS C:\Users\marke\gridgarden> git log
commit 3322d58d34e5debb787cafcb0266fcceb623f79d (HEAD -> master, origin/master, origin/HEAD)
Author: csyun <92949174+Changsoon-Yun@users.noreply.github.com>
Date:   Fri Mar 1 05:40:09 2024 +0900

    fix: fixed typos in Korean translation (#185)

commit 2c7aef3a993afc379ff55a7eba228e711e4c8187
Author: Thomas Park <hello@thomaspark.co>
Date:   Fri Nov 10 16:38:42 2023 -0500

    add youtube link to footer

commit e11f74c8511c757ae418896c919e333cfa1030b8
Author: Thomas Park <hello@thomaspark.co>
Date:   Wed Aug 16 22:04:31 2023 -0400

    remove duplicate level translation

commit 430fdd15764dfa712eb639f5bb0466ad9bfee293
Author: Thamizh <91716052+ThisisThamizh@users.noreply.github.com>
Date:   Thu Aug 17 07:32:21 2023 +0530

    Tamil translation fix (#180)

commit 0f446c6a3429b76c78ea6d4d084c544e134184f0
Author: Thomas Park <hello@thomaspark.co>
Date:   Tue Aug 15 09:54:38 2023 -0400

    add slovak to language menu

commit 8d9c64e263953ec54262fee79ba74deb7358f9d7
Author: Thomas Park <hello@thomaspark.co>
Date:   Tue Aug 15 09:51:45 2023 -0400

    slovak translation credit in readme @jjhen99

commit 381a406cbcfb04fc37dc2d4ec640248a1758b18c
Author: Thomas Park <hello@thomaspark.co>
Date:   Tue Aug 15 09:51:07 2023 -0400

    fix missing comma in levels

commit 2007b9188c63d5c716fca1bdc553033db7a08368
Merge: 9395abf 4869417
Author: Thomas Park <hello@thomaspark.co>
Date:   Tue Aug 15 09:48:25 2023 -0400

    Merge pull request #178 from jjhen99/SvkGridGarden

    Added slovak translations for Grid Garden and also added </p> to some…

commit 48694174b13b6e0bc58d2d22b49b6f69c82c98b6
Merge: 6aeee7e 9395abf
Author: Thomas Park <hello@thomaspark.co>
Date:   Tue Aug 15 09:47:43 2023 -0400

    Merge branch 'master' into SvkGridGarden

commit 9395abf4b14ef1f2cc763655e379c884ea6fdca3
Author: Thomas Park <hello@thomaspark.co>
Date:   Tue Aug 15 09:07:57 2023 -0400

    tamil translation credit in readme @ThisisThamizh

commit 83b6382694785926f358d0bb6d91aac6f60a59ba
Author: Thamizh <91716052+ThisisThamizh@users.noreply.github.com>
Date:   Tue Aug 15 18:36:28 2023 +0530

    translate to Tamil language  (#177)

    * Tamizh input - docs.js

    * Tamizh addition - messages.js

    * Tamizh tooltip - index.html

    * Thamizh input - levels.js

    * missed translation fix  levels.js/`order 2`

commit 6aeee7e63f8a2956cc5e90f395ff89f8191a8048
Author: jjhen99 <j.j.henthorn@gmail.com>
Date:   Sat Aug 12 18:07:52 2023 +0200

    Added slovak translations for Grid Garden and also added </p> to some lines starting at line 905 of levels.js



------------------

PS C:\Users\marke> cd Desktop
PS C:\Users\marke\Desktop> git clone https://github.com/markerson7/gridgarden.git
Cloning into 'gridgarden'...
remote: Enumerating objects: 1882, done.
remote: Counting objects: 100% (280/280), done.
remote: Compressing objects: 100% (147/147), done.
remote: Total 1882 (delta 168), reused 202 (delta 130), pack-reused 1602Receiving objects:  99% (1864/1882), 2.23 MiB | 2.22 MiB/s
Receiving objects: 100% (1882/1882), 3.20 MiB | 2.71 MiB/s, done.
Resolving deltas: 100% (959/959), done.
PS C:\Users\marke\Desktop>


---------------------

PS C:\Users\marke\Desktop> cd gridgarden
PS C:\Users\marke\Desktop\gridgarden> git branch PLP-Assignment
PS C:\Users\marke\Desktop\gridgarden> git checkout PLP-Assignment
Switched to branch 'PLP-Assignment'
PS C:\Users\marke\Desktop\gridgarden>

------------------

PS C:\Users\marke\Desktop\gridgarden> git branch
* PLP-Assignment
  master
PS C:\Users\marke\Desktop\gridgarden> git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\marke\Desktop\gridgarden> git merge PLP-Assignment
Updating 3322d58..dca35ad
Fast-forward
 index.html | 2 ++
 1 file changed, 2 insertions(+)
PS C:\Users\marke\Desktop\gridgarden>

-----------------------------

PS C:\Users\marke\Desktop\gridgarden> git add index.html
PS C:\Users\marke\Desktop\gridgarden> git commit -m "Creating Conflicts"
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
PS C:\Users\marke\Desktop\gridgarden> git push origin master
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/markerson7/gridgarden.git
   3322d58..dca35ad  master -> master
PS C:\Users\marke\Desktop\gridgarden>


-----------------------------


PS C:\Users\marke\Desktop\gridgarden> code index.html
PS C:\Users\marke\Desktop\gridgarden> git add index.html
PS C:\Users\marke\Desktop\gridgarden> git commit -m "Resolved conflicts"
On branch resolve-conflict
nothing to commit, working tree clean
PS C:\Users\marke\Desktop\gridgarden> git commit -m "Resolved conflicts"
On branch resolve-conflict
Your branch is up to date with 'origin/resolve-conflict'.

nothing to commit, working tree clean
PS C:\Users\marke\Desktop\gridgarden> git checkout main
error: pathspec 'main' did not match any file(s) known to git
PS C:\Users\marke\Desktop\gridgarden> git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\marke\Desktop\gridgarden> git merge resolve-conflict
Updating dca35ad..6e4df56
Fast-forward
 index.html | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\marke\Desktop\gridgarden> git branch -d resolve-conflict
Deleted branch resolve-conflict (was 6e4df56).
PS C:\Users\marke\Desktop\gridgarden>


--------------------------


PS C:\Users\marke\Desktop\gridgarden> git add index.html
PS C:\Users\marke\Desktop\gridgarden> git commit -m "Add index.html for GitHub Pages"
[master 760988b] Add index.html for GitHub Pages
 1 file changed, 9 insertions(+), 272 deletions(-)
PS C:\Users\marke\Desktop\gridgarden> git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 429 bytes | 214.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/markerson7/gridgarden.git
   dca35ad..760988b  master -> master
PS C:\Users\marke\Desktop\gridgarden>

--------------------------------

