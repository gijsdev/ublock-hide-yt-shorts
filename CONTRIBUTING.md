# Contributing

I only want to state a couple of rules when submitting a pull request:

## Only include YouTube Shorts
The function is in the repository name.

## Never change the metadata on top of the list
*Metadata = Title, Version, Last modified etc. on the top of the list.*

This will only be done by one of the maintainers. You may or may not be the only pull request accepted between a version bump for example.

## Always include the full subdomain
Don't start your filter with `youtube.com` but with either `www.youtube.com` or `m.youtube.com`.
This is to prevent hiding elements on other subdomains like `studio.youtube.com`.

## Don't make your selector more complicated than it needs to be
Don't keep unnecessary `.style-scope` classes in your filter, for example.

## Always try to include "Short(s)" or "Reel(s)" in your filter
Always try to select an element which has the name or text "Short(s)" or "Reel(s)" in it.

## Try to avoid :has-text() selectors
It's more performant to use element selectors instead of :has-text() selectors. If there really is not other way to identify the element, then you can use :has-text().

## Point to the specific elements with a screenshot or description
It's not always immediately clear what elements you're talking about. Try to include a screenshot of the elements or a link to a specific page where you will find the elements.