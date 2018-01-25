Responsibility
==============

An important step in troubleshooting is **responsibility**.

At this stage you've already established the following:

* Observation: The computer doesn't behave the way you expect
* Expectation: Your expectation is correct
* Reproducibility: You're able to reproduce the issue and you identified the steps to do that

The goal now is to identify **what component is responsible** for the issue and the best way to find out is to proceed by elimination.

During the **reproducibility** phase you identified a series of steps to reproduce the issue. You should now try to reduce the amount of steps necessary and remove components which might play a role in the issue to idenfity which one actually does.

Here are some examples:

* An application crash when you run it in Russian.. does it also crash in English?
* The computer is slow to boot.. is it slow when offline? are there USB devices plugged?
* The desktop freezes.. does it happen with the default configuration? or without 3rd party applets?

Another strategy to identify which component is responsible is to try to reproduce the issues in different environments.

Here are some examples:

* You see an issue in Cinnamon, does it also happen in MATE?
* You see an issue in a particular release, does it also happen in previous releases?
* You see an issue in Linux Mint, does it also happen in Ubuntu?

By identifying what's common and what's not, you have a better chance of identifying where the issue is.

.. note::
	Here's an example of an issue where the responsible component was identified:
		"My Nike shoes hurt my right foot every time I walk. I feel no pain with other pairs of shoes, same socks, same places, same amount of time.".

At this stage, you still don't know enough to understand the **cause** of the issue, but you're able to successfully identify the component responsible for the issue.

.. important::
	Linux Mint is made of thousands of software components, many of them developed by very different teams. Identifying the right component is key to know which development team might be able to help and where to report an issue.

