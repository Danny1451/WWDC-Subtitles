# wwwww

CLI tool for doing useful things after scraping WWDC session metadata

## Usage

Once you are up and running, use `-h`/`--help` flags for more information about the interface and functionality.

## Getting Started

1. Follow the installation instructions for dependency [Kanna](https://github.com/tid-kijyun/Kanna), specifically the instructions for Swift 3 via Swift Package Manager.
1. Run `swift package update`.
1. Optionally run `swift package generate-xcodeproj` if you're interested in working with the implementation in Xcode.

## Warning

Web scraping is fragile by nature, and small changes to the page HTML naming or structure can break this tool. It may be you that finds this breakage first–please file an issue.

## Thanks

Based on [Guaka](https://github.com/nsomar/Guaka) and [Kanna](https://github.com/tid-kijyun/Kanna).

## Name

Yes, that is [five dubs](http://www.theonion.com/blogpost/fuck-everything-were-doing-five-blades-11056). As in, _world wide web dub dub_. Maybe _dub dub world wide web_. _dub dub dub dub dub_ if you like. Or even _dub dubbity dub dub dubbity_. Maybe it just looks like a squiggly line.

## Addition By Danny

Add another cmd called **subtitile**. Scraping WWDC session's webtvv files and transform to readable formate.

like this

```
.build/debug/wwwww subtitle -s 201 -v -y 2017  
```

I've already downloaded the 144 sessions subtitles,here are them:



| Subtitiles | nums|
| --- | --- |
| [App Frameworks](https://github.com/Danny1451/wwwww/tree/master/2017/App%20Frameworks)  | 50 |
| [Design](https://github.com/Danny1451/wwwww/tree/master/2017/Design)| 20 |
|[Developer Tools](https://github.com/Danny1451/wwwww/tree/master/2017/Developer%20Tools)|15|
|[Distribution](https://github.com/Danny1451/wwwww/tree/master/2017/Distribution)|5|
|[Featured](https://github.com/Danny1451/wwwww/tree/master/2017/Featured)|2|
|[Graphics and Games](https://github.com/Danny1451/wwwww/tree/master/2017/Graphics%20and%20Games)|9|
|[Media](https://github.com/Danny1451/wwwww/tree/master/2017/Media)|15|
|[System Frameworks](https://github.com/Danny1451/wwwww/tree/master/2017/System%20Frameworks)|19|





