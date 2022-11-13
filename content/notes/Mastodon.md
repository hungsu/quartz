A [[Federated service|Federated]] social network using [[ActivityPub]], competing directly with [[Twitter]] and gaining great interest in 2022-11 with Elon Musk's acquisition of Twitter.

My Mastodon profile is [here](https://mstdn.social/@hungsu), on mstdn.social, one of the larger instances. In the weeks I've been here I've had a few thoughts about Mastodon and federation in general

## Advantages over Twitter

**No ads or promoted content**. Twitter's ads are *always* repulsive low value content, even when tailored to me. They are either links to blog posts *saturated* with even more ads, or products I never buy.

**No viral content**. Mastodon has a purely chronological timeline with no algorithm, and lacks Twitter's *Quote Retweet*. By designing itself to not encourage viral moments, Mastodon has opted out of the "outrage theatre" that twitter had become. Instead, Mastodon hopes for people to post content purely out of their own desire to create.

**No addiction mechanisms or dark patterns**. Since Mastodon has no reason to addict you to it, it can do without Twitter's addictive features, which include:
- Less visible likes - I found myself skimming over things with few likes and gravitating towards things with many likes. On Mastodon you're instead left with just the content, unless you click deeper to see the likes.
- No Quote tweets
- No Ratios - punishment for having too many comments relative to likes
- No notifications of people liking replies to you

Scott Feeney also has a whole [blog post](https://scott.mn/2022/10/29/twitter_features_mastodon_is_better_without/) on them

## Disadvantages to Twitter

**No one is on there**. None of my friends are there, so I've been forced to have passing interactions with strangers. Fun, but nothing lasting.

**Confusing UX**. Federation is a strange concept to most people. For many, Mastodon is the first federated service they've ever used, myself included. Notably, replying to or following a person on another Mastodon Instance is not straightforward, and requires entering your own username and instance name each time.

## Helpful tools for getting more out of Mastodon

https://moa.party/ allows automatic posting to twitter from mastodon

If you have your own home page, add this to it to advertise your mastodon 
```HTML
<a rel="me" href="https://your.server/@your_username">Mastodon</a>
```

## Self hosting

If you choose to host Mastodon yourself, be aware that the default settings have scaling problems, such as with a surge of traffic from Twitter exodus:

https://nora.codes/post/scaling-mastodon-in-the-face-of-an-exodus/