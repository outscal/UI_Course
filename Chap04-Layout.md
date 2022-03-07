## Layout

- **Rect Transform -**
    
    The Rect Transform is a transform component that is used for all UI elements. It has position, rotation, and scale just like other transforms, but also has a width and height to specify the dimensions of the rectangle.
    

![rect transform.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5d025dc1-f0a7-48a8-abda-c9de18d37bc0/rect_transform.png)

- **Pivot -**
    
    The pivot affects the outcome of a rotation, resizing, or scaling. When the toolbar Pivot button is set to Pivot mode, the pivot of a Rect Transform can be moved in the Scene View.
    

![pivot.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/dbfad7c6-721a-4883-816f-adfb4b673b5c/pivot.png)

- **Anchors -**
    
    Rect transform includes a layout concept called anchors. Anchors are shown as four small triangles in the scene view. If Rect transform is attached to a parent Rect transform, then the child Rect Transform can be anchored to the parent one in many different ways like to the center or to any of the corners. A useful feature of the anchor handles is that they automatically snap to the anchors of sibling rectangles to allow for precise positioning.
    

![anchors.gif](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/240b7b4f-b58d-448a-af44-fb3c95ffa40b/anchors_2.gif)

![anchors1.gif](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/36a97f72-70ec-470e-b103-c5950ce5b9cf/anchors.gif)

![anchors2.gif](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cdfe430c-cba1-4a87-97d1-d20044484681/anchors1.gif)

![anchors3.gif](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7237d635-14eb-42f5-b790-c529506bab71/Untitled.png)

- **Anchors presets -**
    
    This option can be found in the inspector, it is present in the upper left corner of the Rect transform component. By clicking this button it brings up the anchors presets option, in which there are some pre-defined anchor positions. You can use those anchor positions to set your UI element. You can anchor the element to the center, or to the sides, or you can stretch them along the horizontal, vertical, or in both directions.
    

![anchor presets.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/beb00f4c-765c-45c8-b52e-de583498e72c/snchors_presets.png)

##
