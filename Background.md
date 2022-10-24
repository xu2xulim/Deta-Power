All members of a board will have access to all the cards. Currently, there is no intraboard permission to limit users' access to information.

**Disclaimer** :there may be such capability in the Enterpise plan but developer had not had the opportunity to work in that environment

With the Premium plan, there is the option to make a user an observer such that the edit capability is deactivated for the user.

There exist a power up called [External Share](https://trello.com/power-ups/60d93bb780ee244d5d2b1edd) that you can share a card/attachments via a shared link.

However, the **focus** of this paper is beyond this specific use case but on the fact that any microservice can use use to extend the capabilities of Trello similar to the use of http request action from Trello Butler (Automation)

### Modules
The following modules will be discussed:

- Custom Power Up deployed on node.js
- FastAPI app using jinja2 templates
  - allows the Trello use to grant permission for an external user access to the card
  - allows the external user access to a private space to view the card 
