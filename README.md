# Incorporating Changes

Sometimes we find that after we deploy a lab, some changes need to be made to it.

If that's the case, given our workflow, there are a few steps you need to take to get those changes incorporated into your version of the lab.

Remember, you're working on a forked version of a lab that lives on the flatiron-school-ironboard organization. You'll have cloned that fork onto your machine.

When we push changes to the version of the lab on flatiron-school-ironboard organization, a **pull request** will be opened on your fork. You'll see a 1 next to "Pull Requests" on your fork repo's page that looks something like this:

![PR Icon](https://s3-us-west-2.amazonaws.com/readme-photos/pull-requests+icon.png)

Click on that pull request. You should see this at the bottom of it.

![merge PR](https://s3-us-west-2.amazonaws.com/readme-photos/merge-pull-request.png)

**Merge** that pull request. This will merge the changes into the **remote** repository on Github.

Next, you'll need to bring those changes down to your local repository.

From the lab directory on your machine, run `git pull origin master`, which will bring down those changes.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/remote-intro-incorporating-changes-readme' title='Incorporating Changes'>Incorporating Changes</a> on Learn.co and start learning to code for free.</p>
