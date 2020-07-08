# SwiftUI-RoundedCornersView
In SwiftUI, you can freely set the corners of the View

![Simulator Screen Shot - iPhone 11 Pro Max - 2020-07-08 at 14.27.19.png](https://i.loli.net/2020/07/08/zYhZ2mUXPHRW6tr.png)

```swift
Text("大圣，")
    .font(.title2)
    .padding(/*@START_MENU_TOKEN@*/.all/*@END_MENU_TOKEN@*/, /*@START_MENU_TOKEN@*/10/*@END_MENU_TOKEN@*/)
    .background(RoundedCornersView(color: .green,
                                   topLeading: 0,
                                   topTrailing: 30,
                                   bottomLeading: 30,
                                   bottomTrailing: 0))
```
