# Liquid language
<h1 class="product-single_title">{{product.title}}</h1>

<div class="product-single__description rte">
    {{product.description}}
</div>

{# for variant in product.variants %}
    <option value="{{variant.id}}">
```
    {{variant.title}}

    {%- if variant.available == false %}
    {{ 'products.product.sold_out' | t}}
    {% endif %}
```
    </option>
{% endfor %}
![](/assets/images/스크린샷%202023-08-11%20오전%201.12.40.png)



![]()