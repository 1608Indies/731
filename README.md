# 731 Assignment
### Note about GIT
Git is a very powerful and very useful tool when collaborating on a project. It can also be a complete pain in the ass. Things can, and will, go wrong at some point. When this happens please remember the following:
1. We are a team. If somethings gone wrong and you don't know what to do, reach out. Someone may know how to fix it, and if we don't we can work together to solve the problem.
2. We're all good at different things. It may take a while to get the hang of git and thats fine. Asking questions, even basic ones, is how we improve and learn.
3. Git can be rolled back. If you have broken everything, we always have the previous version.
4. Everyone makes mistakes sometimes.
5. No one here hates you.
6. No one has died.

The last two points may seem a little silly, but it's some of the best advice I ever got from a boss. While this assignment and degree are important to us all its goog to remember that even if things go catastophically wrong, theres a limit to how bad things can be.

## Rules for GIT usage
### Main workflow
1. Create a branch from the Develop branch, name it after the feature or bug you're working on
2. Commit work to branch after each session
3. Upon starting a new work session, rebase the branch from develop
4. When the feature or bug is finished create a pull request back into the develop
5. Get a second party to look at the work
6. If everything is okay merge the branch into develop
7. Check if CI/CD pipeline succeeds

### Branches
1. Give branch useful names e.g. feature-player movement, or bug-menu buttons broken
2. Once a feature or bug is completley finished, delete the branch
3. Unless an abosolute emergency or agreed upon by the group, NEVER MERGE OR PUSH DIRECTLY INTO MAIN

### Unreal/Unity Specific
1. Only one person can work on a blueprint, Level/Scene, asset, image or basically anything considered a Binary File at a time. Multiple people pushing the same binary file will result in overwrites and lost work.
2. Code you can go nuts on.

### CI/CD
1. Unless agreed upon by the team, do not touch the CI/CD files once they are working
2. If do need to make emergency changes, let the team know immediately
3. Pipelines sometimes just fail. If it fails once, try restarting it. If it fails twice, something is broken.
4. Git resources are finite. If only a single action fails it might not be necessary to restart the pipeline

## Final words on Git
The name "git" was given by Linus Torvalds when he wrote the very first version. He described the tool as "the stupid content tracker" and the name as (depending on your mood):

1. random three-letter combination that is pronounceable, and not actually used by any common UNIX command. The fact that it is a mispronunciation of "get" may or may not be relevant.
2. stupid, contemptible and despicable. simple. Take your pick from the dictionary of slang.
3. "global information tracker": you're in a good mood, and it actually works for you. Angels sing, and a light suddenly fills the room.
4. "goddamn idiotic truckload of sh*t": when it breaks.
