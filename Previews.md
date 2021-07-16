# Previewing SwiftUI Views

If you open the `ContentView` file, you should see the following code at the end of the file:

```
struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
    }
}
```

This code is preview code that works with Xcode's preview canvas. The canvas lets you see how the view looks without having to build and run the project.

## Changing the Preview Code

Unless your SwiftUI view takes arguments, you won't have to change the preview code.

Suppose your SwiftUI view takes a document of type `Document` as an argument. There are two common ways to pass an argument to the preview. The first is to call the constructor of the struct or class you're passing to the view.

```
ContentView(document: Document())
````

If you get a syntax error passing the document that way, use the .constant and supply the constructor to the struct or class.

```
ContentView(document: .constant(Document()))
```

## Showing and Hiding the Canvas

The preview canvas appears in the editor next to your code. If you do not see the canvas, click the button on the right side of the tab bar above the editor and make sure Canvas is selected.

![ShowCanvas](images/ShowCanvas.png)

Clicking the button is also the way to turn off the canvas.
