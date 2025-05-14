## Overseer FAQ

### What is Overseer?
Overseer is a bot designed to make and manage federated ban networks across multiple servers.

### How does Overseer work?
Overseer works by allowing servers to subscribe to ban lists from other servers. When a ban is added to a ban list, that ban is propagated across all subscribing servers. Anyone can create and subscribe to ban lists using the join code tied to each list.

### Is Overseer free?
Overseer is freemium: most features are free, but some advanced capabilities require a paid plan to cover hosting costs.

### How do I get started?
Run:
- `/guild setup` to configure your server,
- `/automod setup` to set up moderation logging.
You can also add an appeal link for banned users.

### How do I ban someone?
Use `/ban add` to:
1. Select a ban list you own or manage.  
2. Choose a reason and provide proof.  
The ban will then propagate to all servers subscribed to that list.

### How do I unban someone?
Use `/ban remove` to select the list, and the user will be unbanned across all subscribing servers.

### What are authorized users?
Authorized users are trusted individuals whom the list owner has granted permission to add bans. You can view them with `/banlist info`.

### How do I add an authorized user to a list?
Use `/banlist authorize` to pick a list you manage and then select the user to authorize.

### How do I remove an authorized user from a list?
Use `/banlist deauthorize` to select the list and the user you want to remove.

### How do I subscribe to a ban list?
Use `/banlist subscribe <join-code>` to subscribe to a list and automatically receive its bans.

### How do I unsubscribe from a ban list?
Use `/banlist unsubscribe` to choose which list to leave, and you’ll stop receiving its bans.
