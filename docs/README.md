# starter

* Portainer
    * docker-compose up portainer 
    * port 9000; admin/fikeis85
* Docs
    *   Jekyll theme
        *   https://rundocs.io/
        *   https://github.com/rundocs
    *   Markdown
        *   https://kramdown.gettalong.org/quickref.html#quick-reference
        


## site.pages

<!-- prettier-ignore-start -->

| source          | link                                                           |
| --------------- | -------------------------------------------------------------- |
{% for page in site.pages -%}
| {{ page.path }} | [{{ page.url | relative_url }}]({{ page.url | relative_url }}) |
{% endfor %}

<!-- prettier-ignore-end -->

