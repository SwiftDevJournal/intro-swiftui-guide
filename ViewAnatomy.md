# Anatomy of a SwiftUI View

If you open the `ContentView` file, you should see the following code:

```
struct ContentView: View {
    var body: some View {
        Text("Hello, world!")
            .padding()
    }
}
```
This code is the starting point for creating a SwiftUI view. There are two important points to remember about SwiftUI views.

* SwiftUI views are structs.
* The `body` property is where you add controls.

## SwiftUI Views Are Structs

Why is it important to know that SwiftUI views are structs? SwiftUI views have a short life because they are structs. When the view changes, SwiftUI creates a new view.

You have to be careful declaring variables inside a SwiftUI view struct. Suppose you delcare the following variable in the view:

	var score = 0
	
And you have code that updates the score. When SwiftUI creates a new view, the score is reset to zero. The fix in this case is to use the `@State` property wrapper to tell SwiftUI to keep the value of the variable when it creates a new view.

	@State var score = 0
	
## Add Controls Inside body

The `body` property is where you add controls to the view. In the code example at the top of the page, the `Text` line is the control. A `Text` control displays static text.

You can add controls by typing them in Xcode's editor or by [dragging them from the view library](BrowsingViews).
