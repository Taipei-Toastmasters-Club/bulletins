---
layout: default
---

This is a place to host bulletins from Taipei Toastmasters Club. Feel free
to open them and contact us if you have any question.


### List

{% assign files = site.static_files | where: "file", true %}
{% for myfile in files reversed %}
* [{{ myfile.basename }}](/{{ site.repo_name  }}{{ myfile.path  }})
{% endfor %}


### Contact

You can contact us on [facebook](https://www.facebook.com/TaipeiToastmastets/).
Or you can know more about us on [toastmasters site](https://www.toastmasters.org.tw/page.php?page_type=club&id=1890&ver=en).



