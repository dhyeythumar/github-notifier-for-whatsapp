<p align="center">
    <img alt="logo" src="./assets/github_octocat.svg" width="160"/>
</p>
<h1 align="center">
GitHub User Activities & Repo Releases Notifier for WhatsApp 
</h1>

<h4 align="center">
Follow GitHub Users to get notified on their public activities & Watch GitHub Repos to get notified on public releases
</h4>

> Note:
>
> -   Check out the status of the services [**here**](https://github-notifier.statuspage.io/). And do subscribe to stay in the loop with new incidences such as critical system failure or scheduled maintenance as they would be reported over there.
> -   Check out the project's [**changelog**](./changelog.md) to know more on how the project is progressing.
> -   Only 1v1 conversations are possible with this WhatsApp bot because **following any particular GitHub User** or **watching any particular GitHub repo** is a personal choice. So by having this bot on a Whatapp group conversation doesn't make any sense. But still, if WhatsApp users want to add this bot to WhatsApp groups then you can open a **Discussion** in this repo. And will decide what to do based on the votes.

## What’s In This Document

-   [Introduction](#introduction)
-   [Getting Started](#getting-started)
-   [Commands](#commands)
-   [Future Development](#future-development)
-   [Support the project](#support-the-project)
-   [License](#license)
-   [Legal](#legal)

## Introduction

Want to follow your favorite GitHub Users? So you can stay updated with their GitHub public activities. Or you just want to watch the open-source GitHub repositories so, whenever a new release is published, you get notified, then this project is a gem for you. Now you can get the direct updates right into your WhatsApp, so you don't miss even a single public activity. Check out the [**Getting Started**](#getting-started) section right now to set the `GitHub Public Activities & Releases Notifier for WhatsApp`.

> For now, the source code of this project is private, so if you want to contribute to the source code, feel free to connect with me [here](mailto:dhyeythumar@gmail.com).

## Getting Started

To get started, click the following link [**Message**](https://wa.me/message/P6OA32I7W3XKG1) or can also enter the below URL in to your browser `https://wa.me/message/P6OA32I7W3XKG1`

Check out the [**Commands**](#commands) section for the complete list of **public commands** (available for all users) and their detailed explanation.

## Commands

-   General

    -   `/help` - Get a concise explanation of all the commands.
    -   `/disconnect` - Disconnect the service and clear the chats from the bot end.
    -   `/clear` - To clear the history from the bot side.

-   GitHub User(s)

    -   `/follow` - Follow the GitHub user(s) & get updates.

        ```
        // ---- for example ----
        /follow @dhyeythumar, @Sentdex, @sindresorhus
        ```

    -   `/unfollow` - Unfollow the GitHub user(s) and, you won't get any further updates for that user(s).

        ```
        // ---- for example ----
        /unfollow @dhyeythumar, @Sentdex, @sindresorhus
        ```

    -   `/following` - Get the list of GitHub user(s) you are following.

-   GitHub Repo(s)

    -   `/watch` - Watch the GitHub repo(s) & get updates whenever a new release is published.

        ```
        // ---- for example ----
        /watch Unity-Technologies/ml-agents, sindresorhus/Gifski, xojs/xo
        ```

    -   `/unwatch` - Unwatch the GitHub repo(s) and, you won't get any further updates for that repo(s).<br />

        ```
        // ---- for example ----
        /unwatch Unity-Technologies/ml-agents, sindresorhus/Gifski, xojs/xo
        ```

    -   `/watching` - Get the list of GitHub repo(s) you are watching.

## Future Development

> This section contains the list of features that are scheduled for future release & the list of completed features

-   [x] Add **Watch, Unwatch, Watching** feature on GitHub Repos so WhatsApp users can stay updated (notified) whenever there is a new release in a watched repo. [Version 2.0.0](https://github.com/dhyeythumar/github-notifier-for-whatsapp/blob/main/changelog.md#version-200-major-changes)
-   [x] Setup the status page so the bot users can be notified for every incident (failure/maintenance) with the services. [Version 2.2.0](https://github.com/dhyeythumar/github-notifier-for-whatsapp/blob/main/changelog.md#version-220)
-   [x] Add Redis for caching the commands to save the system/service from any abuse & saving any redundant requests to the database. [Version 2.3.0](https://github.com/dhyeythumar/github-notifier-for-whatsapp/blob/main/changelog.md#version-230)
-   [x] Take actions when messages/commands went unread (due to offline/sleep-mode of service 😴) so users do not have to resend the messages/commands. [Version 2.4.0](https://github.com/dhyeythumar/github-notifier-for-whatsapp/blob/main/changelog.md#version-240)

## Support the project

If you are using this project and happy with it or just want to encourage me to continue creating stuff, there are few ways you can do it:-

-   Starring and sharing the project
-   Become a maintainer

If you would like to see a feature implemented, don't hesitate to add it to the issues list.

Contributions are welcome! ✌

## License

Licensed under the [MIT License](./LICENSE).

## Legal

This service is in no way affiliated with, authorized, maintained, sponsored or endorsed by WhatsApp & GitHub or any of its affiliates or subsidiaries. This is an independent and unofficial service.


![visitors](https://page-views.glitch.me/badge?page_id=dhyeythumar.github-user-activity-feeds-for-whatsapp)
