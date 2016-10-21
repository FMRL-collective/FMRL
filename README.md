![logo](https://github.com/FMRL-collective/FMRL/blob/master/logo_400.png)
# FMRL
*An open-source musical collective*

# Founding Principles
FMRL is founded upon several principles that define its primary output and culture.

## One-click listening
Listeners can start listening to music just by clicking a URL link. No sign-up or sign-in, no user interface is required. Just old school virality through the sharing of URLs.

## Audio only
Every FMRL musical experience is accompanied by a completely blank page. FMRL are focused on innovating online music consumption, so let's get the music sorted first.

## Genre agnostic
The FMRL collective exists to make it easy for its member to make FMRL musical experiences. While we expect the output of some members to align with existing genres, we want to support the creation of new genres and remain unbiased.

## Real-time synthesis
No streaming MP3's, no WAV samples, every sound must be synthesised in the browser after the page loads. We know that's tough, but let's see how far we can push it.

## Open-source
FMRL is built upon open-source principles. All FMRL related output will be managed on GitHub, enabling FMRL experiences to be forked and the evolution of FMRL to be traced.

# Logistics
Having founding principles is great, but let's discuss how we operationailse them to start creating music.

## Single-page applications
Each FMRL experience should be considered a single-page application (SPA). While this will undoubtedly lead to a fat client model, the *audio only* principle will ensure resources are focused on music synthesis. On load, each SPA should setup an AudioContext using the Web Audio API. After this, the SPA can do anything. Web-workers and WebGL might be useful for off-loading expensive computation. The [FMRL-root](https://github.com/FMRL-collective/FMRL-root) will be a boilerplate with the neccesary requirements for getting started building a FMRL experience.

## Committee
All of the above is just a first draft and is completely open for discussion. We need to build a committee to lay down some plans for the future of FMRL. Message me if you are interested in discussing further.
