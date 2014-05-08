# Unofficial Patreon Button

Showcase your Patreon project with this simple, static button featuring its
up-to-date monthly pledge amount.

To get started, checkout http://ptrn.me!



## Usage

These buttons are hosted via GitHub Pages, meaning all you need to do is
include an `iframe` and you're set. Once included, you can configure it with
various parameters. Here's the snippet:

``` html
<iframe src="http://ptrn.me/patreon-btn.html?creator=CREATOR"
  allowtransparency="true"
  frameborder="0"
  scrolling="0"
  width="62"
  height="20">
</iframe>
```

### Required parameter

- `creator`: the name of the Patreon project.  When your project's URL is
  `http://patreon.com/my-cool-project`, this parameter is `my-cool-project`.


### Optional parameter

- `size`: add `size=large` to the `iframe` URL to change the button height to
  30px.



## Examples

### Basic button

``` html
<iframe src="http://ptrn.me/patreon-btn.html?creator=neuesausderzukunft"
  allowtransparency="true"
  frameborder="0"
  scrolling="0"
  width="62"
  height="20">
</iframe>
```

### Large button

``` html
<iframe src="http://ptrn.me/patreon-btn.html?creator=neuesausderzukunft&amp;size=large"
  allowtransparency="true"
  frameborder="0"
  scrolling="0"
  width="100"
  height="30">
</iframe>
```



## Usage with SSL

In order to avoid `insecure content` warnings when using GitHub Buttons on a
page behind an SSL certificate, simply host a copy of the `patreon-btn.html`
file on your secure directory and substitute your domain in the iframe include:

``` html
<iframe src="https://YOURDOMAIN.com/patreon-btn.html?creator=CREATOR"
  allowtransparency="true"
  frameborder="0"
  scrolling="0"
  width="62"
  height="20">
</iframe>
```



## Bug tracker

Have a bug? Please create an issue here on GitHub at
https://github.com/carlo/patreon-buttons/issues.



## Author(s)

Carlo Zottmann, [@municode](https://twitter.com/municode), https://github.com/carlo,
carlo@zottmann.org.

My thanks go to [Mark Otto](https://github.com/mdo) for his original Github
buttons project which this project is a heavily modified fork of.



## Copyright and license

Copyright 2011 Carlo Zottmann.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
