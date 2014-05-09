# Unofficial Patreon Button

Showcase your Patreon project with this simple, static button.  It's able to
show your project's total pledge amount, its number of patrons or both.

To get started, take a look at [https://ptrn.me](https://ptrn.me)!



## Usage

These buttons are hosted via GitHub Pages, meaning all you need to do is
include an `iframe` and you're set.  Once included, you can configure it with
various parameters (see section "Configuration", below).  Here's the snippet:

``` html
<iframe src="https://ptrn.me/patreon-btn.html?creator=CREATOR"
  allowtransparency="true"
  frameborder="0"
  scrolling="0"
  width="62"
  height="20">
</iframe>
```

Both HTTP and HTTPS are supported.


## Configuration

You can change what's displayed in the bubble by changing the iframe URL.

### Required parameter

- `creator`: the name of the Patreon project.  When your project's URL is
  `http://patreon.com/my-cool-project`, this parameter is `my-cool-project`.


### Optional parameters

- `size`: add `size=large` to the `iframe` URL to change the button height to
  30px.  Default: standard size.
- `show`: what to display in the bubble -- the amount of pledged `money`
  (e.g. "$9,876"), the number of `patrons` (e.g. "123 patrons") or
  `both` (e.g. "123 » $9,876").  Default: `show=money`.
- `unit`: if the pledges are on a "per thing" basis, this can be noted here.
  For example, an unit could be "month", "video", "comic" or whatever.
  Default: not shown.



## Examples

### Default size, show pledge amount (money)

``` html
<iframe
  src="https://ptrn.me/patreon-btn.html?creator=neuesausderzukunft"
  allowtransparency="true"
  frameborder="0"
  scrolling="0"
  width="110"
  height="20">
</iframe>
```
[Live example.](https://ptrn.me/patreon-btn.html?creator=neuesausderzukunft)


### Large button, show money per video

``` html
<iframe
  src="https://ptrn.me/patreon-btn.html?creator=neuesausderzukunft&amp;size=large&amp;unit=video"
  allowtransparency="true"
  frameborder="0"
  scrolling="0"
  width="170"
  height="30">
</iframe>
```

[Live example.](https://ptrn.me/patreon-btn.html?creator=neuesausderzukunft&size=large&unit=video)


### Show number of patrons

``` html
<iframe
  src="https://ptrn.me/patreon-btn.html?creator=neuesausderzukunft&amp;show=patrons"
  allowtransparency="true"
  frameborder="0"
  scrolling="0"
  width="200"
  height="20">
</iframe>
```

[Live example.](https://ptrn.me/patreon-btn.html?creator=neuesausderzukunft&show=patrons)


### Show both number of patrons and pledge amount per comic

``` html
<iframe
  src="https://ptrn.me/patreon-btn.html?creator=neuesausderzukunft&amp;show=both&amp;unit=comic"
  allowtransparency="true"
  frameborder="0"
  scrolling="0"
  width="230"
  height="20">
</iframe>
```

[Live example.](https://ptrn.me/patreon-btn.html?creator=neuesausderzukunft&show=both&unit=comic)



## Bug tracker

Found a bug?  Please create an issue
[here on GitHub](https://github.com/carlo/patreon-buttons/issues).



## Author(s)

Carlo Zottmann, [@municode](https://twitter.com/municode),
[github.com/carlo](https://github.com/carlo), carlo@zottmann.org.

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
