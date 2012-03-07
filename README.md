# Media Type Template

Ever wanted to define your own media type? `application/json` just not doing it
for you? `application/xhtml+xml` got you down with its strictness? Well, you
can show the W3C who's boss!

## What you get

A nice pretty template to start filling out all the deets.

Simple, HTML5 markup. Pretty CSS. Pre-made sections. It's all here.

## Why would I want to do this?

Often, making use of a new media type is the first step in building a
[Hypermedia API](http://hypermediaapidesign.com), and it's always kinda
annoying. You should really publish your spec, but then you have to write all
this HTML. And writing HTML sucks.

## Any other stuff I should know?

Yeah! After you define a type, you should [register it with the
IANA](http://www.iana.org/assignments/media-types/index.html). That's the next
step towards making it a standard.

## Wait, I thought this was for custom stuff?

So your webservice lets you do something cool with Widgets online. So you make
`application/vnd.foocorp.widgets+json`. You register it with the IANA, and it
[goes under the vendor tree](http://tools.ietf.org/html/rfc4288#section-3.2).
Then some other comapny comes along, and they also do sweet things with
Widgets. They ideally will work with you on making the media type applicable
to both themselves and you.

Widgets are sweet, so pretty soon, an entire group of companies uses the
`application/vnd.foocorp.widgets+json` media type. Pretty sweet! But foocorp
isn't really special anymore here. We're all working together on this. So then
you make an RFC for `application/widgets+json`, and now it's a global standard.
Congrats! You're an awesome Internet citizen!

