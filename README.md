How to embed Wisembly on your website or your app
=================================================

There are two ways to embed Wisembly in a webpage or in an application: by simply including our responsive mobile view in an iframe or by developping your own Wisembly implementation on top of our [APIs](https://app.wisembly.com/api/doc/).

## iframe / webview integration

- Pros:
  - no development involved
  - full Wisembly features set
- Cons:
  - no hand over graphic customization (unless asking us)

### Code needed and example

```html
<iframe src="https://app.wisembly.com/m/keyword#widget" width="300px" height="400px" border="0" marginheight="0" marginwidth="0" frameborder="0"></iframe>
```

Where:

- https://app.wisembly.com/m/keyword#widget must be updated accordingly whith **your own Wiz keyword**  
  _eg: if your keyword is kickoff2014, then your url would be https://app.wisembly.com/m/kickoff2014#widget_
- width is in pixel the desired iframe width (you could also use percents, like `width="100%"`)
- height is in pixel the desired iframe height


## API integration

- Pros:
  - full hand on customization
  - only features you want (and implement)
- Cons:
  - need developpers to implement it
