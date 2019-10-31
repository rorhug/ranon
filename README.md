# ranon

The goal of this project is to create a seamless experience browsing the web in _reasonably_ private way.


[Project Progress](https://github.com/rorhug/ranon/projects/1)


### Goal

- When intentionally visiting a website _anonymously_ (not logged in), the host website should not be able to find out who you are by any means.
- Once logged into a website, that particular profile described by the domain, the email/username used to sign in and other configuration should be persisted and recalled when appropriate.
- By generating cookie stores, proxies and browser fingerprint attributes for each `{domain, account}`, users maintain isolated and untraceable relationships with each website.



Using the [containers API](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/contextualIdentities), Firefox allows creation of isolated cookie stores. Think of containers as multiple incognito tabs (rather than windows) that you can save!

There are [existing extensions](./existing.md) for privacy and container managment but either they don't provide enough functionality or have too many configuration options.


