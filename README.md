This program helps migrate a blog from [WordPress][] to [jekyll][] while
preserving most of the original markup and all metadata needed to rebuild
original permalinks, archives and DISQUS comments.

Most code is based on [exitwp][] by Thomas Froessman, with the notable
exception of `migrate.wpautop` which is a port of
`wp-includes/formatting.php:wpautop` from WordPress.

The original project has no explicit license, but due to code pulled from
WordPress this program is licensed under the terms of [GPLv2][].

[WordPress]: http://wordpress.org
[jekyll]: http://jekyllrb.com
[exitwp]: https://github.com/thomasf/exitwp
[GPLv2]: http://www.gnu.org/licenses/gpl-2.0.html
