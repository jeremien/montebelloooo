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


# variables

{% for product in collections.all.products %}
 {{ product.price | money_without_trailing_zeros }} 
{% endfor %}

# api
https://shopify.dev/api/liquid/objects/product

#
shaole

