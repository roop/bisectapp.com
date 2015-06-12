---
layout: post
title: Reimagining the iPad split view for a Markdown editor
---

Apple just took the iPad experience to the next level with some lovely
[multitasking enhancements][ipad_multi]. The coolest feature of the lot
is clearly Split View, which will be available only on the iPad Air 2\.
Craig Federighi's demo in the WWDC Keynote featured Safari open on the
left half of the iPad screen and Notes open on the right half, with both
apps interactive at the same time.

That said, the apps on either half of the screen don't talk much _to
each other_. You can add a link to the current note in Notes from
Safari's share menu; you can tap on added links in a note to open them
in Safari on the left pane. That's as far as it gets - the app on
one half has no way to talk specifically to the app on the other half.

iOS 9's Split View multitasking stops at this point, but this idea can
go much further when we apply it to specific tasks.

Bisect is an app that helps you write notes or posts in Markdown as you
browse the web. Bisect uses the same split-screen idea, but adapts it to
a Markdown editor.

Here's some of the stuff you can do with Bisect:

 * Browse the web as you write a blog post, and add a Markdown link
   reference from the browser

<figure>
    <a href="/blog/images/add_ref.gif" />
    <img src="/blog/images/add_ref.gif" />
    </a>
</figure>

 * Link the current selection

<figure>
    <a href="/blog/images/link_selection.gif" />
    <img src="/blog/images/link_selection.gif" />
    </a>
</figure>

 * Create a link to the current webpage as you write

<figure>
    <a href="/blog/images/insert_current_browser_url.gif" />
    <img src="/blog/images/insert_current_browser_url.gif" />
    </a>
</figure>

 * See a live Markdown preview of your post, updated as you type

<figure>
    <a href="/blog/images/live_preview.gif" />
    <img src="/blog/images/live_preview.gif" />
    </a>
</figure>

Bisect does this by including the browser, the editor and the preview as
separate components in the same app.

Bisect is currently in beta and will be available in the App Store in
July 2015. Bisect works on all iPads running iOS 8.

If you like what you see here and want to use this on your iPad,
please [sign up for the beta]. If you'd like to try this on an iPhone,
please [contact me].

[ipad_multi]: http://www.apple.com/ios/ios9-preview/#ipad
[ipad_multi_fallback]: http://www.macstories.net/stories/initial-thoughts-on-ios-9s-ipad-multitasking-a-deep-transformation/

[sign up for the beta]: http://bisectapp.com/#join-beta
[contact me]: http://roopc.net/about/

