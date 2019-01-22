# custom-element-samples
This repository contains two samples of the HTML web pages that can be used in a Custom element (BETA).

[Custom elements](https://developer.kenticocloud.com/v1/docs/extending-kentico-cloud-beta) help you with extending the basic functionality of Kentico Cloud UI and thus improving the content editing experience. Custom element is essentially a small HTML application that exists in a sandboxed <iframe> and interacts with the [Kentico Cloud](https://kenticocloud.com/) app via the [Custom Elements API](https://developer.kenticocloud.com/v1/reference#custom-elements-api).

Note that Custom elements are only supported in the latest versions of our SDKs.

[![Forums](https://img.shields.io/badge/chat-on%20forums-orange.svg)](https://forums.kenticocloud.com)

# Custom elements' samples overview
## ColorPicker
[ColorPicker](https://github.com/Kentico/custom-element-samples/blob/master/ColorPicker/color-picker.html) is a simple Custom element based on a [color-picker](https://github.com/tovic/color-picker) JavaScript library. It allows user to choose a color from palette and sets it as a HEX string, e.g. '#ff0000' for red color, '#00ff00' for green, and so on. Selected color is then seen as the Custom element's background. When the element is disabled, its color palette is still visible in a content item but does not react when clicked on.

## Markdown editor
[Mardown editor](https://github.com/Kentico/custom-element-samples/blob/master/Markdown/markdown.html) is a WYSIWYG Custom element which allows users to write formatted text using [SimpleMDE](https://github.com/sparksuite/simplemde-markdown-editor). In this sample element, you can find examples of setting dynamic height and reacting on the window 'resize' events. When the element is disabled, the editor is set to the readonly mode.

# How to create a custom element
You can find a detailed tutorial on how to create a Custom element in our [documentation](https://developer.kenticocloud.com/v1/docs/extending-kentico-cloud-beta).

# Feedback & Contributing

Check out the [Contributing](https://github.com/Kentico/delivery-sdk-net/blob/master/CONTRIBUTING.md) page to see the best places to file issues, start discussions, and begin contributing.

You can also contribute by adding your own Custom element here. Create an HTML web page, include the Custom Elements API in the code, describe what your element does in the Readme file, and send us a pull request.

![Analytics](https://kentico-ga-beacon.azurewebsites.net/api/UA-69014260-4/Kentico/custom-element-samples?pixel)
