# Deathly Hallows for Cloud Adoption

Somehow, I have been extremely fascinated about this "Tale of Three Brothers" story from the Harry Potter and the Deathly Hallows. Partly because I am big fan a story well told...


<a href="http://www.youtube.com/watch?feature=player_embedded&v=bN1_h_eGitE" target="_blank"><img src="http://img.youtube.com/vi/bN1_h_eGitE/0.jpg" alt="Tale of Three Brothers" width="240" height="180" border="10"/></a>

Strangely it so happens there are a couple things to take away from this story when you are adopting Cloud your application hosting needs. And you would be surprised to see the strange resemblance to actual story.

Its important to provide a background on the actual Deathly Hallows and how to map that to this article.  According the Tale of Three Brothers there exist three deathly hallows– The Elder Wand, The Cloak of Invisibility and The Resurrection Stone. Three hallows given by Death himself to three brothers. The story goes onto say that anyone who posses these three Hallows will conquer over Death.  Death with respect to this blog would be a failed adoption of the Cloud. And this traces the Three Deathly Hallows to conquer over Death.

## The Elder Wand

The Elder Wand should be a Cloud that gives the most powers,  and yet being the simple to wield.

The one with most powers is the one that has widest range of services, with support for widest choice of platforms, and distributed across multiple regions.

The one with the most simple API– well documented and easy to understand, and has a flourishing tools ecosystem, and community, should be the one that is the simplest to wield.

But its also essential to have a good generalization of the services, and scan the landscape for similar services to build on your own. This essential to plan for contingencies.

## The Cloak of Invisibility

This is essentially how you could choose to hide the Cloud Nativity from your deployments, and your application.

It is extremely important to choose your deployment mechanisms that could take you from one Cloud to another without much ado.

Also its essential to keep you application hidden away from any kind of Cloud Nativity. Make sure the app itself is not too dependent on any specific Cloud API; do remember to keep interaction directly to Cloud API to a minimum if not nil.

This is an essential design decision that anyone adopting to Cloud should take. This will definitely help from locking yourself into any single Cloud.

## The Resurrection Stone

Being a publicly available web application would mean to provide 100%(well almost) availability of your system. There are two aspects to this; the ability to anticipate and avoid failures, and the ability quickly respond to failures.

To anticipate and avoid failures it imperative to have a robust monitoring engine that drives the application availability consciousness. Its important whether you deploy on the Cloud or in a Physical Data Center, to have a monitoring system that  monitors system logs, application logs, system resources, databases and services. The monitoring system should also provide effective alerting workflows, among other things. The workflows should lead to automated or manual responses; either ways the key is to keep the system/application available and performing at the desirable levels.

The other facet is the ability to raise up or resurrect from failures. This could be achieved by having a completely automated mechanisms to redeploy applications, services and databases, and kick off where the system went down. Good backup strategies, excellent battle tested automation scripts, would make your resurrection a breeze. Or rather many times you could do with designing a good DR strategy.  

Cloud provides many options which makes it even more easier to respond to such failures. The property of the programmable infrastructures of the Cloud makes it very simple to setup your entire application stack; by just running a simple script.

## Afterword

I deliberately refrained from naming Cloud Providers or Frameworks. As you see from the article the Cloud Provider does not do anything in your scheme of providing an Highly Scalable and Available application stack. Remember how you choose/strategize  your Deathly Hallows is entirely your own making. I have just told you what they are.

I hope you enjoyed reading this as much as I enjoyed writing it.
