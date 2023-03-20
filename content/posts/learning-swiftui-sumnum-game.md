
+++
title = "Learning SwiftUI and making a game"
description = "My initial impressions of using SwiftUI and making a game"
showcomments = true
date = "2020-07-01"
tags = ["programming" ,"swift"]
+++

When Apple announced SwiftUI about 2 years ago, I was extremely excited. I had previously used Microsoft's WPF and Silverlight with their declarative layour markup language that resonates very well with the way I think about UIs. In the past few months, I finally had a few weekends that I could dedicate to learning SwiftUI at a high level with a simple project. 

As I was looking for a project to tinker with, I remembered a number's game I used to play in middle school when I was back in Istanbul. It is a very simple game where the user tries to reach a target number in the allotted time using a set of numbers and arithmetic. I have fond memories of playing this game, so I decided to re-create it using SwiftUI on iOS. I named it [SumNum](https://www.sumnum.app).

Overall, I had a pleasant experience in using SwiftUI. There are still some rough edges around XCode support (even with LivePreview) such as cryptic compiler errors, random crashes and a pretty slow compilation result. However, even with these limitations it is still infinitely better than using Interface Builder. At this point I strongly believe that all Apple UI development will be moving to SwiftUI in the coming few years. 

I was able to implement an MVVM pattern with simple enough dependency injection and testing in next to no time. However, the Binding/State/EnvironmentObject/ObservedObject concepts are a bit more complicated than they need to be. If you do choose to go down that path, I strongly suggest watching the following [Apple Developer Session Video on Data](https://developer.apple.com/videos/play/wwdc2020/10040/). 

Animations were surprisingly easy to implement compared to other platforms I have seen. Especially the composability of each animation makes it very easy to re-use them within a given view. I used them for both the menus and gameplay with ease. 

[![SumNum Gameplay](http://img.youtube.com/vi/OvKWl93XQ5Q/0.jpg)](https://youtu.be/OvKWl93XQ5Q "SumNum Gameplay")


While I was working on the app, I wanted to add some complex animations that went way beyond animating simple shapes. In my search of a suitable animation I came across [Lottie Files](http://www.lottiefiles.com) by AirBnB. It has many free/low-cost animations by hundreds of animators around the world. They even provide a web/Swift based player that makes it easy to incorporate into iOS apps. I strongly suggest using them. 

Overall creating the basic game engine & the associated UI was extremely fast. I am very impressed with the implementation of both the Swift language and the SwiftUI framework. As the frameworks start evolving to shed Cocoa and eventually UIKit references, the experience should only get better. 

