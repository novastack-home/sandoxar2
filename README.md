# Attributes

## ar-scale
Controls the scaling behavior in AR mode. Set to "fixed" to disable scaling of the model, which sets it to always be at 100% scale. Defaults to "auto" which allows the model to be resized by pinch.

| Default Value | Options |
| ------ | ------ |
| auto | auto, fixed|

# Slots

## ar-button
By placing a child element under <model-viewer> with slot="ar-button", this element will replace the default "Enter AR" button, which is a <model-viewer> icon in the lower right. This button will be visible if AR is potentially available (we will have some false positives until the user tries).