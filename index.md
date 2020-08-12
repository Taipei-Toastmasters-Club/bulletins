---
layout: default
---

This is a place to host bulletins from Taipei Toastmasters Club. Feel free
to open them and contact us if you have any question.

### Bulletins

{% assign files = site.static_files | where: "file", true %}
{% for myfile in files reversed %}

- [{{ myfile.basename }}](/{{ site.repo_name  }}{{ myfile.path  }}) ([QR](https://api.qrserver.com/v1/create-qr-code/?size=300x300&data={{ site.url }}/{{ site.repo_name  }}{{ myfile.path  }}))
  {% endfor %}

### Resources

{% assign files = site.static_files | where: "resource", true %}
{% for my_resource in files reversed %}

- [{{ my_resource.basename }}](/{{ site.repo_name  }}{{ my_resource.path  }}) ([QR](https://api.qrserver.com/v1/create-qr-code/?size=300x300&data={{ site.url }}/{{ site.repo_name  }}{{ my_resource.path  }}))
  {% endfor %}

### Contact

You can contact us on [facebook](https://www.facebook.com/TaipeiToastmastets/).
Or you can know more about us on [toastmasters site](https://www.toastmasters.org.tw/page.php?page_type=club&id=1890&ver=en).
