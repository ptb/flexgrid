[ptb/flexgrid] is a next-generation web page layout framework based on flexbox: the [CSS Flexible Box Layout Module]. It uses the same responsive [12 column grid] and CSS class names as [Bootstrap].

[ptb/flexgrid]: https://github.com/ptb/flexgrid
[CSS Flexible Box Layout Module]: http://www.w3.org/TR/css3-flexbox/
[12 column grid]: http://getbootstrap.com/scaffolding.html#gridSystem
[Bootstrap]: http://getbootstrap.com/

A [customized] version of [Modernizr] is used to detect support for flexbox. The flexbox layout is supported on Chrome, all versions of iOS, Safari 3+, [IE 10]+, [Opera 12.10]+, and [Firefox 22]+. Other browsers get the fluid [Bootstrap 3] layout, except Internet Explorer 6 and 7 which use a fixed layout.

[customized]: http://modernizr.com/download/#-flexbox-flexboxlegacy-printshiv-cssclasses-domprefixes
[Modernizr]: http://modernizr.com/
[IE 10]: http://msdn.microsoft.com/library/ie/hh673531.aspx
[Opera 12.10]: http://my.opera.com/ODIN/blog/opera-12-10-is-out
[Firefox 22]: https://developer.mozilla.org/en-US/docs/Firefox_22_for_developers#CSS
[Bootstrap 3]: https://github.com/twitter/bootstrap/pull/6342

Unlike other frameworks, it is just a grid, and thus requires only 1594 bytes for [flexgrid.css] and 2068 bytes for [modernizr.js]; with gzip both together are less than 1.67k! A display vs. [source re-ordering] variant is available as an option.

[flexgrid.css]: https://raw.github.com/ptb/flexgrid/master/flexgrid.css
[modernizr.js]: https://raw.github.com/ptb/flexgrid/master/modernizr.js
[source re-ordering]: https://raw.github.com/ptb/flexgrid/master/flexgrid-reorder.css

[Documentation], a [demo], and [source code] are available. Suggestions for improvement are welcome!

[Documentation]: http://ptb2.me/flexgrid/
[demo]: http://demo.ptb2.me/flexgrid/
[source code]: https://github.com/ptb/flexgrid
