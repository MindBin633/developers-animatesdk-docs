## fill.bitmapPath

#### Availability

> Flash CS4 Professional.

#### Usage

> fill.bitmapPath

#### Description

> Property; a string that specifies the path and name of the bitmap fill in the Library. This property is available only if the value of the [fill.style](#_bookmark423) property is "bitmap".

#### Example

> The following example sets the fill style of the specified item to a bitmap image in the Library:
>
> var fill = fl.getDocumentDOM().getCustomFill(); fill.style = "bitmap";
>
> fill.bitmapPath = "myBitmap.jpg"; fl.getDocumentDOM().setCustomFill(fill);

#### See also

> [fill.bitmapIsClipped](#_bookmark414)