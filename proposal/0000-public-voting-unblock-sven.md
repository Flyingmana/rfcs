# lift Ban of Sven Reichel

## Summary

`https://github.com/sreichel` (Sven Reichel) got blocked permanents after several CoC violations
and direct attacks at the projects Maintainers.
There is now a request from some contributors to lift this Ban as they see him as indispensable for the project.

## Motivation

OpenMage is in the end a community Project, and whenever there is no clear consens, the next bigger Group should be asked. In this case we are in the last round now and asking the Public to get a final vote on this.

## Detailed Explanation

### Reasons to allow him back

Some of his Contributions

* adding doc blocks to thousands of methods which is a work of months
* replaced the old Zend Framework with ZF1-Future, including creating the patches.
* added support for PHPstan where he worked on @tmotyls' plugin
* improved testing and workflow
* n98-magerun
* DDEV environment base for OpenMage



### original Reasons for the permanent Block

the permanent Ban happened on February 4th 2024, after multiple (5) personal attacks against Flyingmana in just a month.
He got over years a lot of warnings, a lot of offers on how to address his complaints in a more ordered and constructive way. There even was a temporary ban a while before.


#### founding accusations

A lot of the attacks revolved around accusing Flyingmana of collecting money in the name of OpenMage without doing anything and not providing any transparency.

Some accusations were even directly stating that Flyingmana would steal money from the project.


PR of adding the openCollective https://github.com/OpenMage/magento-lts/pull/3649
As stated there, I did start it in response to a community request in https://github.com/OpenMage/magento-lts/discussions/3495#discussioncomment-7541893  
And the usage of the collected founds will be based on this community maintained document https://github.com/OpenMage/organizational/blob/main/finance/expense_planning.md 
public accessable OpenCollective Page https://opencollective.com/openmage 

14th November 2023 Here is one more occasion where Sven was already told about all the context of the funding (after he asked in a very toxic way about it)
https://github.com/OpenMage/magento-lts/pull/3649#issuecomment-1811186501  

30th November 2023 
https://github.com/OpenMage/magento-lts/discussions/3683#discussioncomment-7717838
> sreichel on Nov 30, 2023
> @Flyingmana, you beg for money ... ? For a project you did nearly nothin for?

#### Code Stealing accusations

https://github.com/OpenMage/magento-lts/pull/3789#issuecomment-1925582934

> Das nächste mal, sag Bescheid! Das Du meine Arbeit kopierst, möchte ich auf keinstn Fall!

Google translate to english =>  
> Next time, let me know! I definitely don't want you copying my work!

This was after I already stated the code is based on a [PR](https://github.com/OpenMage/magento-lts/pull/3773) he closed before because he apparently could not solve a pipeline issue himself.
Also, the changes were purely configurations of the github pipeline.

#### various toxic occurences


Comment on a fresh PR  
https://github.com/OpenMage/magento-lts/pull/3413#issuecomment-1663241847  
> sreichel commented on Aug 3, 2023
> Untested? Just to have another commit?


Complaining about something which was done following a previous RFC he does not approve of
https://github.com/OpenMage/magento-lts/discussions/3422#discussioncomment-6623626  
> sreichel on Aug 3, 2023
> "we have to push" ... HELL NO!
> 
> You never cared about shops that just wanted to migrate to OM. Dropped support for v19 branch was such a big mistake imho ... but hey, its you personal playground now. Was a good descision to step back ...
> 
> Seems you are only acting on developers view (that i agree with for "next"), but not on store owners with limited resources ...
> 
> justinbeaty on Aug 3, 2023
> There was an RFC, and the majority of us decided to drop v19. It’s unfair to say @fballiano is treating this as anything close to his personal playground. 🤷‍♂️
> 
> ...
> 
> sreichel on Aug 3, 2023
> Think about how long I contributed to the project? For its orignal intention.
> 
> Are you telling me that the quality has improved in recent months?
> 
> Edit: "why it is okay" ... b/c this project is not community-driven anymore! It realy feels like a personal playground now ...



complaining he got a private block from one of the maintainers  
https://github.com/OpenMage/magento-lts/pull/3482

reaction to a callout of his sarcasm
https://github.com/OpenMage/magento-lts/discussions/3683#discussioncomment-7726301


on 3th February 2024  
https://github.com/OpenMage/magento-lts/pull/3773#issuecomment-1925147790  
> sreichel commented on Feb 3 • 
> God damn it. Either grant me permissions or fix it on your own. Phpunit does not work right atm, and i can not abort test runs .... zzzzz

on 4th February 2024, I dont even know what this was about
https://github.com/OpenMage/magento-lts/pull/3778#issuecomment-1925589759
> sreichel commented on Feb 4
> > If its for a project of you only, then its ok.
> > 
> > If its a plan in general for OpenMage, instead of renaming it, can you add a parallel one?
> > It has a specific usecase and scope, and from our side we should not shift the scope, just because its similar to what we need.
> 
> "our side"?
> 
> You === our? Who are you speaking for?

#### related to OpenMageModuleFostering

29th July 2020, called me a (weak) curseword in a private message, after I declined to give him write permission to all of https://github.com/OpenMageModuleFostering so he can execute a script of his.
I told him back then, it would be best he is adding it to the tooling repository I started https://github.com/OpenMageModuleFostering/Tooling/tree/master/src/Task
As it allows to Review the Script before, and run it on a reduced number of packages first to test the result.

But he declined and insisted giving him write access would be the only option for him.

Since then he regularly brings up, how I prevented the progress there.

The last time he commented on it was on the 08th February 2024

> I offered a working script to add modman and composer.json files (as requested here https://github.com/OpenMageModuleFostering/Tooling/issues/2)
>
> All extension could have it since years. I asked for write permissions, to update all repos, but it was declined. It was not perfect enough and not integrated into his "tooling". Wasted time.

### additional reasons against him

#### behavior

Even in his request to lift the ban from Mai, he still was stating Flyingmana should not expect an apology.

On beginning of July Sven did create an RFC himself, containing several lies (which lead to it getting removed)

One of them: 
> Now we have "opencollective", but no one - beside @Flyingmana - has access to it.
> Nobody knows about the funds and what happens to them. That`s one of the major issues!

Here the publicly accessible page, he did either not even try looking at it, or did state this lie on purpose. Either way its a clear sign for me, that "discussing" with him is not possible.
https://opencollective.com/openmage


Also he is constantly putting a lot of pressure on maintainers, not accepting authority, and expecting people to serve him and his visions.
Also while he is putting a lot of expectations and pressure on maintainers and contributors, he is reacting regularly bad if is confrontend with critic or requirements.


##### consistency

He is volatile, on multiple occasions he removed/deleted his PRs when something did not go as he wanted.

He started a Request for Github Sponsors, but then removed it again. 
When Flyingmana created a similar request half a year later, in an ordered way as an [RFC](https://github.com/OpenMage/rfcs/pull/11), he used this on occasion to blame Flyingmana for having only his own benefit in mind.

Over the years there were multiple times, where he threatened/promised to quit the project fully.

One time he quit on the 21th October 2023, for not having merge permission anymore. (which he lost automatically on one of the temporary bans)
Which occured together with a number of such comments on PRs he created originally.
https://github.com/OpenMage/magento-lts/pull/3234#issuecomment-1771792383  
> sreichel commented on Oct 20, 2023
> Thank for wasting my time.


##### egoism

For Sven it is more important to have his name on things, then to have the things done. (see Code Stealing accusations above)

He was using the Project to get a Free phpstorm license, and saw this as a blocker for the project to request founding.
https://github.com/OpenMage/magento-lts/pull/3649#issuecomment-1807638303



#### additional reasonst against him - personal (of Flyingmana)

A lot of the bigger contributions he provided, were changing a lot of code without any direct benefit. (docblocks are really nice, but they are not a selling point)
Additionally, all this changes did need a lot of time to Review, for many months my majority of OpenSource time was spent on reviewing his PRs, highlighting issues, possible BC Breaks, behavior changes.

He is focused so much on having controll and changing things how he wants, that he is not thinking about how to include others into the decision making.
For PRs he focuses on perfection, required documentation, which is increasing the effort for contributors, driving them away, and prefering declining a PR opposed to accepting gradual improvements.

At the same time he always wants to do multiple things together, and complains when others prefer to do things in separate PRs.  
https://github.com/OpenMage/magento-lts/pull/3789#issuecomment-1925569879  
> > thats something for a different PR
> 
> Everytime, everything I say ... I only hear no, not, but ...
> 
> ... but adopt my try ... 😠




## Possible Votes

Multiple votes (or even voting for all of them) are possible, the option with the single highest vote count decides

* 1) allow him back, without restrictions
* 2) allow him back, with a 1 month block whenever he violates again the rules
* 3) allow him back, with a permanent block if he violates again the rules
* 4) Do not allow him back
* 5) Do not allow him back, and also ban discussing it again for 2 years to be discussed again.


