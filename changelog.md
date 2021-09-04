# Version 2.5.0
**Automated the Statuspage incident publishing & updating pipeline.** An incident will be automatically published whenever there is a crash in a particular service (this also avoids duplicate incidents). And whenever that service comes back online (can be a self-recovery also) the unresolved incident will be changed to resolve state.

# Version 2.4.0
**Now the users don't have to resend the messages which went unseen & unreplied when the bot was offline.** These messages will be used and acted upon once the bot comes online.

# Version 2.3.0

Introducing **Redis** for caching the commands that access the main database (such as follow, unfollow, following, watch, unwatch, watching, disconnect). Now by this feature system won't frequently access the main database and can directly access the cached requests from the WhatsApp users. **And this can also help in avoiding system abuse (like sending the same command, again and again, that won't have any effects on the main database after the first request is processed successfully).**

# Version 2.2.0

The [**public status page**](https://github-notifier.statuspage.io/) is up and running for each component in the system. Now whenever a component crashes due to an error a new incidence will be reported and the status of that component will be set to the `major outage` by that component itself. By this, the users can always be aware of outages/downtime of components. Scheduled maintenance can also be created and notified to the service users by this status page.

# Version 2.1.0

Added an Email-based error reporting so the error can be resolved as quickly as possible and systems health can be maintained. These emails are sent to the admins/owners/maintainers of the project. The email reporting is completely autonomous and done by the running systems itself whenever an error occurs.

# Version 2.0.0 (Major Changes)

Added a new set of commands so now users can also get the notifications whenever there is a new release in an open-source GitHub repository(s). These commands are similar to the GitHub watch feature.

Commands available in this version:

-   help
-   follow
-   unfollow
-   following - Get the list of user you are following
-   disconnect - Disconnect from the service
-   clear - Clear the chat history from the bot side
-   watch
-   unwatch
-   watching - Get the list of repos you are watching

# Version 1.2.0

Private commands are added for Admins/Owner only. This gives the rights to the admins/owner to broadcast the message to all the active WhatsApp clients using the service.

# Version 1.1.0

Minor changes includes the addition of command to the list.

Commands available in this version:

-   help
-   follow
-   unfollow
-   following - Get the list of user you are following
-   disconnect - Disconnect from the service
-   clear - Clear the chat history from the bot side

# Version 1.0.0

This project started with the idea of developing a bot for WhatsApp that will send notifications whenever GitHub user(s) performs any public activity. And to do this classic follow-unfollow model is employed. This version contained few simple functionalities such as follow, unfollow, and following GitHub user(s).

Commands available in this version:

-   help
-   follow
-   unfollow
-   following - Get the list of user you are following
