## Directory Theme

A fork of https://github.com/luk1337/Directory-Theme adapted for OpenQuake

```nginx
	location / {
	    fancyindex on;
	    fancyindex_exact_size off;
	    fancyindex_footer /.fancyindex/footer.html;
	    fancyindex_header /.fancyindex/header.html;
	    fancyindex_css_href /.fancyindex/style.css;
	}
```
