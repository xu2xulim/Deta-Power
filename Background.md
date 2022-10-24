All members of a board will have access to all the cards. Currently, there is no intraboard permission to limit users' access to information.

**Disclaimer** :there may be such capability in the Enterpise plan but developer had not had the opportunity to work in that environment

With the Premium plan, the is the option to make a user an observer such that the edit capability is deactivated for the user.

There exist a power up called [External Share](https://trello.com/power-ups/60d93bb780ee244d5d2b1edd) that allows share a card/attachments via a shared link.

The **focus** of the paper is beyond this specific use case but on the fact that any microservice can use use to extend the capabilities of Trello.

### Modules
The following modules will be discussed:

- Custom Power Up deployed on node.js
- Webapp built a FastAPI app using jinja2 templates
  - acts a the interface on the card to grant permission to the external user
  - allows the external user access to a private space to view the card 
