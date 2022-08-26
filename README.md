https://getshogun.com/learn/shopify-liquid-tutorial#basics

https://shopify.github.io/liquid-code-examples/

https://shopify.github.io/liquid/basics/introduction/

https://github.com/Shopify/dawn

# debug 
{{ product | json }}

'dump.liquid'
<script type="text/javascript">
 console.log("Dumping");
 console.log({{ dump | json }});
</script>

 {% include 'dump' with [OBJECT] %}

  'product.liquid' {% include 'dump' with product %} 

  {% comment %}
  {% endcomment %}


# variables

{% for product in collections.all.products %}
 {{ product.price | money_without_trailing_zeros }} 
{% endfor %}

# api
https://shopify.dev/api/liquid/objects/product

# mdp
shaole

# filtre

http://127.0.0.1:9292/search?q=peinture&sort_by=price-ascending

# cli
https://shopify.dev/themes/tools/cli/getting-started

shopify login
shopify theme serve
shopify theme check
shopify theme push
shopify theme publish

<ul>
  {%- for product_vendor in shop.vendors -%}
    <li>{{ product_vendor | link_to_vendor }}</li>
  {%- endfor -%}
</ul>