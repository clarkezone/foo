### How to do it

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```cs
            // Grab the compositor for the window
            compositor = Window.Current.Compositor;

            // Create a new ShapeVisual that will contain our drawings
            Windows.UI.Composition.ShapeVisual shape = compositor.CreateShapeVisual();

            // set this as a child of our host shape from XAML
            ElementCompositionPreview.SetElementChildVisual(VectorHost, shape);
```
