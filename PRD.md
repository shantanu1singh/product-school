# Spotify Circles

## Author: Shantanu PM

## Overview

**Spotify Circles** aims to remove the hassle that users feel while using the platform to listen to music in a social context. Spotify currently does an incredible job at providing a great listening experience to a user by supplying high quality music curated from all over the world that is tailored to their personal interests.

As users engage in group activities such as commuting in a car or hanging out at a friend&#39;s house, they use Spotify to play their favorite songs by either connecting their phone to a speaker or television and selecting specific songs or a playlist available in their Spotify collection. Since most audio devices usually only support a single audio connection from a source, it robs the other social players from the ability to easily select their own personal favorite songs and add them to the current queue. Spotify Circles will allow all users in the group to be able to play their favorite songs or add them to the current playing queue easily, from within the application running on their own personal devices.

Since songs are also tailored to the tastes of one single user, the entire listening experience is not as enjoyable to all the other people present in the group. Spotify Circles will have the ability to create a dynamic playlist based on the interests of all the users in the listening group to accommodate for the variety of preferences ensuring that each listener has a great experience.

One of Spotify&#39;s core mission values is to make music from all around the world easily accessible to millions of fans around the world so that they can have amazing listening experiences and let music bring joy to their lives. With Spotify Circles, users will be able to listen to music with utmost ease in social environments and let all the song-picking and mechanical hassle recede into the background. This will amplify the pleasure they get out of the social experience and will help Spotify elate existing customers by providing them a feature that makes their lives easier and also help attract new customers as existing users use Spotify in a group environment with people who currently don&#39;t have a Spotify account or subscription.

Spotify currently only has YouTube as a competitor in this space as it provides a queuing mechanism but, with Spotify Circles, Spotify is going to extend on the queuing aspect by making the group listening circle work over any audio output and additionally using machine learning to make the listening experience even better and personalized to the group instead of a single person.

## Objectives

- Make group music listening experiences more user friendly.
- Provide dynamically curated content for listeners in a social environment based on individual preferences.
- Beat our competition in the social listening experience space.

## Success Metrics

- Number of customers using Spotify Circles to listen to music with other users.
- Number of customers using Spotify Circles more than once.
- Number of new customers acquired through Spotify Circles.
- Number of people recommending/inviting friends to Spotify through Spotify Circles.
- We expect a baseline growth of 5% in the number of active users 3 months post-launch.
- The target growth in number of active users is 10% over the 3 months post-launch.

## Personas

**Cathy, the college student**

Cathy is socially very active, and she has a wide circle of friends. Cathy uses Spotify in her daily life while she&#39;s at home finishing some homework or running outside. Cathy also uses Spotify in social interactions such as driving to places in a car with friends and at parties to play music that both her and her friends can enjoy. Cathy finds it hard and cumbersome to find new songs that she likes and is usually reliant on her friends to recommend good music to her.

## Scenarios

- Cathy is on a weekend road trip to LA with her friends. They&#39;re in her friend&#39;s car who is playing her own curated playlist on the speaker. While Cathy enjoys her friend&#39;s music, she wants her friends to listen to this one song she discovered on Spotify just the other day. After entering the car, Cathy gets a notification on her phone from Spotify suggesting that she could start a Spotify Circle. Cathy taps on it and starts a Spotify Circle with her friends and queues up the song she found. Both Cathy and her friends feel happy about the experience as they&#39;re all able to play and share their favorite music with the others from their personal devices.
- Cathy has invited all her friends over to her place for a small party. Cathy has recently been really busy with work and hasn&#39;t had the time to keep up with the latest music releases. Cathy knows that her friends love listening and dancing to music at house parties. She pulls up Spotify Circles and adds all her friends to the Circle once they arrive. She sets the mood of the Circle to &#39;dance&#39; and is happy knowing that she can trust Spotify Circles to play great &#39;dance&#39; music based on the latest hits that also encompass the personal favorites of all her friends. Her friends are really happy about the fact that they&#39;re able to dance to their personal favorite songs as well as discover new ones that the others like, without having to open up their phones to look for good music.
- Cathy has had a long week at work and is relaxing at home on the weekend. Cathy is about to start cooking and wants to play some music while she cooks. Cathy hasn&#39;t had the time to find any good music recently but recalls how she enjoyed all the songs that were playing at her friend&#39;s place last weekend when she was hanging out with her friends. Cathy opens up Spotify Circles and plays the song list from that one Circle and puts her phone aside. Cathy is glad that she can go back and play songs from a Spotify Circle. This helps her discover new music really easily as she tends to love the music her friends listen to.

## Designs

_Balsamiq mockups enclosed._

## Features In

_[M] denotes minimum viable experience requirement for Spotify Circles_

### Mobile app

##### Notifications

- [M] Location and proximity-based notifications to initiate a Spotify Circle.

##### UX changes

- [M] New landing page for starting a Spotify Circle.
- [M] New page to select the friends in close proximity to add to a Spotify Circle. (Will require the same application version that supports Circles on devices of nearby users)
- [M] New page for viewing all Spotify Circles from the past.
- [M] New page to select songs to add to the Spotify Circle during initiation.
- [M] New page to view all songs that are being played in a Spotify Circle.
- [M] New page to view all users that are part of a Spotify Circle.

##### Other features/scenarios

- [M] Any song played by a user in the Spotify Circle will be queued.
- [M] All Spotify Circles to be saved for all members for future browsing.
- Start a Spotify Radio station from a Spotify Circle. The radio station will play songs similar to the songs played in the Spotify Circle.
- Save all songs from a Spotify Circle on device for offline playback later.

##### Spotify Circle Moods

- Ability to set a _mood_ for a Spotify Circle.
- Ability to change the _mood_ for a Spotify Circle.
- Suggestions for _moods_ prioritized in order, based on preferences of all the people in the Circle.
- Songs matching the _mood_ that is set for the Spotify Circle to be dynamically curated based on the interests of people in the Circle.
- Auto-queue songs matching the _mood_ of the Spotify Circle based on the interests of other Spotify users once suggestions scoped to members of the Circle are over.

##### Updates

- [M] iOS application update with support for Spotify Circles.
- Android application update with support for Spotify Circles.

### Web and Desktop Client

- View all Spotify Circles from the past.
- View all songs that were played in a Spotify Circle.
- View all users that were part of a Spotify Circle.

## Features Out

- Ability to share Spotify Circles on social media. Since a Spotify Circle is privy to the members of the Circle, we would like to consider this option later. Additionally, since we&#39;re separately revisiting our social platform story, we will wait for its design to materialize before considering this feature.
- View Spotify Circle activity of other users on their user profile page. Similar reasons as above. Our users value privacy and this feature isn&#39;t required right now. Will be revisited once the social platform story is established.

## Messaging

[_Link to Press Release._](PressRelease.md)

## GTM Plan

### Marketing

#### Product

Launching Spotify Circles to make the group music listening experience on Spotify more user friendly. The initial launch will be a minimum viable product that allows users to initiate a Spotify Circle where participants can queue songs from their personal devices to a single audio output. View the &#39;Features In&#39; section for a full list of features that are included in the MVP.

The subsequent version of the product will have the ability to set a mood for a Circle where Spotify will dynamically curate content for listeners in a social environment based on individual preferences.

#### Price

Free for all users.

The goal is to increase platform usage and generate more money through greater advertisement exposure to non-Premium members (within the Spotify application) and get them to convert to a Premium membership by providing a unique delighter.

#### Place

Initially target users who are socially active and participate in group activities where music is an integral part of those Circles. A majority of young listeners who go to school and college fall in this category.

#### Promotion

The initial launch of the feature will be done during the first week of the school year which is the week of September 3, 2019. This is because students being in school gives us a greater chance of getting more adoption as students are more likely to listen to music together in different social contexts.

We&#39;ll be partnering with Google to help launch this product in integration with Google Maps. Our existing partnership with Google Maps currently lets users control the songs being played on Spotify from within the Maps application itself. We will leverage this partnership to encourage users to try out Spotify circles when they launch Google Maps and play songs through Spotify considering a large majority of people use Maps while commuting and a big section of that group is usually accompanied by another person during the commute.

We&#39;re also forging relationships with YouTube so that in the future customers are able to queue songs from either YouTube or Spotify to provide a unified experience across music streaming platforms to a single output device through Spotify Circles.

We will be advertising to young listeners on the platform through –

1. Initial launch through a blog post on the company website.
2. Share blog post on social media – Facebook, Twitter.
3. In-application advertisements using both audio (for non-Premium users) and visual channels.
4. Advertisements on social media – Facebook, Twitter, Instagram, YouTube.
5. Advertisements on posters and advertisement hoardings in proximity to college towns.

The advertisements will be focused on the key user experience which is to have great social experiences with music being an integral part of it. Advertisements will be focused on the key target persona which is young listeners who go to school/college.

### Messaging

Messaging for target persona Cathy who is a college going student and is socially active - &quot;Let&#39;s whirl in Circles together!&quot;

Some anecdotes:

&quot;Tired of connecting your phone to a speaker at your friend&#39;s party to make them listen to the latest hit you found last night? With Spotify Circles you can now easily listen to music with friends by eliminating all the mechanical hassle and making the experience more enjoyable.&quot;

&quot;Had a long week and not sure what to play at the party you&#39;re hosting on the weekend? With Spotify Circles you can now let Spotify find the right tunes for your party and ensure that every guest gets to listen to the songs they love!&quot;

### GTM Planning

#### Pre-Launch

The initial alpha versions of the feature will be rolled out to all Spotify employees to gather feedback. The feedback will be obtained through user interviews, surveys and internal tools. We will analyze usage metrics to understand how employees are using the new feature and this will help uncover initial bugs. We will also be analyzing the in-application time spent by the users along with conversion of non-Premium members to Premium subscriptions as part of this effort to validate our success metrics internally.

After testing the alpha versions, an early MVP beta version of the feature will be rolled out to a select group of young listeners who go to the specific schools/universities. We will gather feedback from these students through online feedback channels (UserVoice) and surveys. Some students will also be invited to the Spotify HQ to try out the new feature and give us feedback. We&#39;ll show them some of the messaging that we plan to use to get feedback on that too.

The Spotify Support team will be made aware of the launch so that they are prepared for any incoming issues from users who this feature was rolled out to. An FAQ guide will be handed out to the support team to help them answer the most common questions that customers might have once the feature is launched. This guide will initially be based on the questions that were asked by users during the initial testing of the new feature internally and will be augmented with additional items as we roll this feature out broadly.

The Spotify development teams will also be aware of the launch of the feature as they need to be prepared for any surge in incoming user traffic during the time of the launch. The development teams will be preparing to handle an uptick in traffic numbers by deploying additional backend servers.

Once we&#39;ve gathered enough feedback for the initial beta version, we will analyze it and make any changes that are required before rolling the feature out to additional users.

We will run advertisements within the application (visual and audio) to get people to try out the new feature. These advertisements will be delivered to non-Premium customers. We&#39;ll also be using in-application user interface banners to showcase Spotify Circles to both non-Premium and Premium users. Advertisements will also be run on social media (Facebook, Twitter, Instagram) to target our user persona. A short video showcasing the new feature will be posted on our Spotify channel on YouTube.

#### Launch

A press release will be made on the company&#39;s website to launch the new feature on Sep 3, 2019. This is so that schools and universities are in session during the product launch and we are able to target our user persona. A blog post will also be posted on the company&#39;s website along with social media channels such as Facebook and Twitter.

The days leading up to the press release will be used to ensure that the feature has been well tested internally and any major bugs identified have been fixed. We will also ensure that we have the right metrics in place so that we can analyze user behavior while using the product as soon as it has been released. This will help expedite the identification of other usability bugs.

We&#39;ll be partnering with Google to help launch this product in integration with Google Maps. Our existing partnership with Google Maps currently lets users control the songs being played on Spotify from within the Maps application itself. We will leverage this partnership to encourage users to try out Spotify Circles when they launch Google Maps to pull up driving directions, while playing Spotify, with other Spotify users in the vehicle.

An email will be sent out to all employees with links to the feature press release and blog posts written by prominent tech blogs covering the announcement to apprise them of the launch.

For future releases, we will be posting blog posts on the company website talking about new features being added to Spotify Circles such as using &#39;_moods&#39;_ in a circle. Tech blog writers will be made aware of these features and will be handed out new versions of the product earlier so that they can write reviews of these features.

Future releases will also be rolled out to our users in a gradual fashion with a subset of customers getting the new features in a release first followed by the others. This is so that we are able to gather valuable initial feedback for a feature and act on it before releasing it globally. Users will be notified of new features through app notifications on their devices.

Future releases will also include bug fixes along with usability improvements based on the feedback received from users from the initial launch. We will continue to monitor our feedback channels (on the website&#39;s community, UserVoice etc.) to gather as much valuable feedback as possible that will help us improve the product. We will ensure that we follow up on the highest voted feedback on our communities as quickly as possible to keep our customers happy.

We&#39;re also forging relationships with YouTube so that in the future, customers are able to queue songs from either YouTube or Spotify to provide a unified experience across music streaming platforms to a single output device through Spotify Circles.

#### Post-Launch

We will continue to run advertisements within the Spotify application to increase adoption. We will also showcase some advertisements on the Web and Desktop clients.

A new advertisement will be created for our YouTube channel which highlights the usefulness of the new feature.

We expect to get some media coverage from prominent tech blogs such as BuzzFeed, The Verge etc. which will help spread awareness of the new feature and increase adoption. As more listeners try out the new feature, they are likely to involve their friends, who are either current customers or prospective, in Spotify Circles. This will help drive adoption and move us towards our target of getting more customers.

During the post-launch period, we will continue to analyze the efficacy of our advertisements and get more coverage on advertisement platforms that are getting better acquisition rates for Spotify. We will also limit advertisements on platforms that aren&#39;t returning enough value in terms of user acquisition.

Metrics generated from within the application will be analyzed to understand usage patterns and discover bugs which will help us make the feature better in future releases.

User feedback obtained through different channels will be thoroughly analyzed to ensure that we are able to fix any issues as quickly as possible.
