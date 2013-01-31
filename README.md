IE Bootstrap Carousel
=====================

IE Bootstrap Carousel is a fork of Twitter's Bootstrap Carousel, which can be found here: http://twitter.github.com/bootstrap/javascript.html#carousel.  It is intended to bring support for Twitter's Carousel to Internet Explorer 8 and 9.  It does so by adding jQuery animations for browsers that do not support CSS3 Transitions.

How do I use it?
----------
1. Include either the development or the minified version of ie-bootstrap-carousel.js in your project. 
2. If, for some reason, you have another version of the bootstrap carousel js on your page you should remove.  Or at the very least make sure this one is declared last, so it will redefine the carousel methods.
3. Use the bootstrap carousel the way that you normally would.

Notes
-----
The default Bootstrap Carousel is meant only to show sliding animations.  There [are](https://coderwall.com/p/w4k7sw) [ways](http://stackoverflow.com/questions/10335181/twitter-bootstraps-carousel-fade-transition) to make it use a fade animation instead.  An attempt has been made to make this fallback work for fades as well.  The implementation tested with is a slight variation of [this one](https://coderwall.com/p/w4k7sw).

License
-------
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. ou may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.