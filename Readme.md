# ดู​หนั​งอ​อน​ไล​น์ ​อนงค์ 2 สามสี่ชาติ My Boo 2 (2025) เ​ต็​มเ​รื่​อ​ง

อนงค์ 2..สามสี่ชาติ ▶️▶️ https://t.co/odMweldk66

อนงค์ 2..สามสี่ชาติ ▶️▶️ https://x.com/ActionGithanime/status/1986780689187160132

อนงค์ 2..สามสี่ชาติ ▶️▶️  https://www.youtube.com/@my-boo-2-full-hd-thai

อนงค์ 2..สามสี่ชาติ ▶️▶️  https://www.facebook.com/groups/2013692562531204


<a href="https://mediafilm.cc/th/movie/1418302">▶️▶️ อนงค์ 2..สามสี่ชาติ ▶️▶️ ดู! "อนงค์ 2  My Boo 2-HD/</a>


[link=https://www.imdb.com/user/ur209085618/] ▶️▶️ ดู! "อนงค์ 2  My Boo 2-HD][/link]

ดูหนัง “อนงค์ 2..สามสี่ชาติ (My Boo 2) 2025” เต็มเรื่อง พากย์ไทย/ซับไทย HD ภาพยนตร์แอ็คชั่น–แฟนตาซี จากผู้กำกับ ขุนพันธ์ ก้องเกียรติ โขมศิริ เล่าเรื่อง 4 อนงค์ 2..สามสี่ชาติ ในตำนาน อนงค์ 2..สามสี่ชาติฝ้าย อนงค์ 2..สามสี่ชาติใบ อนงค์ 2..สามสี่ชาติดำ และ อนงค์ 2..สามสี่ชาติมเหศวร กับการต่อสู้ อาคม อำนาจ และ ความเ




![Xcode build](https://github.com/Dimillian/MovieSwiftUI/workflows/Xcode%20build/badge.svg?branch=master)

# MovieSwiftUI

MovieSwiftUI is an application that uses the MovieDB API and is built with SwiftUI. 
It demos some SwiftUI (& Combine) concepts. The goal is to make a real world application using SwiftUI only. It'll be updated with new features as they come to the SwiftUI framework. 

I have written a series of articles that document the design and architecture of the app: [Making a Real World Application With SwiftUI](https://medium.com/better-programming/collection-making-a-real-world-application-with-swiftui-4f9bc8c7fb71).

![App Image](images/MovieSwiftUI_promo_new.png?)

## Architecture

MovieSwiftUI data flow is a subset and a custom implementation of the Flux part of [Redux](https://redux.js.org/). 
It implement the State in an [ObservableObject](https://developer.apple.com/documentation/combine/observableobject) as a @Published wrapped property, so changes are published whenever a dispatched action produces a new state after being reduced. 
The state is injected as an environment object in the root view of the application, and is easily accessible anywhere in the application. 
SwiftUI does all aspects of diffing on the render pass when your state changes. No need to be clever when extracting props from your State, they're simple dynamic vars at the view level. No matter your objects' graph size, SwiftUI speed depends on the complexity of your views hierarchy, not the complexity of your object graph.

## SwiftUI

MovieSwiftUI is in pure Swift UI, the goal is to see how far SwiftUI can go in its current implementation without using anything from UIKit (basically no UIView/UIViewController representable).

It'll evolve with SwiftUI, every time Apple edits existing or adds new features to the framework.

## Platforms

Currently MovieSwiftUI runs on iPhone, iPad, and macOS. 

Follow me on [Twitter](https://twitter.com/dimillian) to get the latest update about features, code and SwiftUI tips and tricks! 
