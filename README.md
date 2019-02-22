# hatenablog-thought

Blog theme for [Hatena Blog](https://hatenablog.com/) named Thought.

You can install this theme from [the theme store](http://blog.hatena.ne.jp/-/store/theme/17680117126965268278) and use it.

## Development

Setup:

```
yarn install
```

Start monitoring and compiling Sass:

```
gulp
```

Set up the CSS for “Design CSS” of Hatena blog:

```
@import 'http://localhost:3030/thought.css';
```

## Classes

You can style the content using the following CSS classes.

<dl>
  <div>
    <dt><code>button</code></dt>
    <dd>Change the link element to look like a button.</dd>
  </div>
  <div>
    <dt><code>border</code></dt>
    <dd>Enclose the element with this class in a frame. Unlike ordinary border, it is applied so that it overlaps the inside of an element. It is supposed to be used mainly when attaching a frame to an image.</dd>
  </div>
</dl>
