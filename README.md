# buynowbutton
“Buy now” button

You can create custom "Buy now" button for a single item that works with Monetha payment gateway.

Setup guide is available on our website - https://www.monetha.io/en/mvp/buynowbutton

Contact email for your questions: team@monetha.io

# Button code
You can generate "Buy now" button on our website - https://www.monetha.io/en/mvp/monethabutton

Here is sample of "Buy now" button code that you need to place on your website:
```html
<html>
  
  <div id='monetha-buy-button-6466597970633728'></div>
  
  <script>(function(){var now = new Date();var warrantyValue = (new Date(now.getFullYear()+2,now.getMonth(), now.getDay())).toISOString();var div = document.getElementById('monetha-buy-button-6466597970633728');var btn = document.createElement('a');btn.href='http://payment.monetha.io/orders/add?pid=1233123&secret=12313123&oid=Order_ID&amount=1&currency=EUR&return=www.website.return.url&cancel=&callback=http://payment.monetha.io/monethabutton/callback&i_firstname=button-purchase&i_lastname=button-purchase&i_email=merchants@monetha.io&i_items=[{ "name": "Your_item", "quantity": 1, "warranty":"'+warrantyValue+'", "price": "1", "subtotal": "1", "total_tax": "0", "total": "1"}]&i_delivery=post';btn.innerText='Custom button text';btn.setAttribute('style','border-radius: 5px;font-weight:400;line-height:1.42857143;text-align:center;touch-action:manipulation;cursor:pointer;border: 1px solid transparent;background-color:#094da0;border-color:#094da0;color:#fff;text-decoration:none;font-size: 15px;padding: 6px 25px;border-radius: 5px;font-weight:400;line-height:1.42857143;text-align:center;touch-action:manipulation;cursor:pointer;border: 1px solid transparent;background-color:#094da0;border-color:#094da0;color:#fff;text-decoration:none;');div.appendChild(btn);})();</script>
  
</html>
```
