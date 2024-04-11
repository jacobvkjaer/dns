# Quick guide

## Filtering

### Blocking

Missing blocking description

#### Example

In order to block the domain `foodora.dk`, one has to add `||foodora.dk^` to a blocklist.

It is important to be aware that domains often redirect to other domains over the course of various spans of browsing.

In order to then effectively block any access to the domain, all those domains should also be added to the list like so
`||foodora.dk^
||foodora.com^`
Provided there were only the two.

### Whitelisting

Missing whitelisting description

#### Example

In order to whitelist the domain `foodora.dk`, one has to add `@@||foodora.dk^` to a whitelist.

To ensure full functionality, all the related domains should be included.
`@@||foodora.dk^
@@||foodora.com^`
