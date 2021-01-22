# sandoxar2

<h1>Attributes</h1>
<h2>ar-scale</h2>
Controls the scaling behavior in AR mode. Set to "fixed" to disable scaling of the model, which sets it to always be at 100% scale. Defaults to "auto" which allows the model to be resized by pinch.
<strong>Default Value</strong>auto
<strong>Options</strong> auto, fixed


<h2>Slots</h2>
<strong>ar-button</strong>
By placing a child element under <model-viewer> with slot="ar-button", this element will replace the default "Enter AR" button, which is a <model-viewer> icon in the lower right. This button will be visible if AR is potentially available (we will have some false positives until the user tries).