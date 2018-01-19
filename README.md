# buynowbutton
“Buy now” button

You can create custom "Buy now" button for a single item that works with Monetha payment gateway.

Setup guide is available on our website - https://ico.monetha.io/en/mvp/buynowbutton

Contact email for your questions: team@monetha.io

# Button code
You can generate "Buy now" button on our website - https://ico.monetha.io/en/mvp/monethabutton

Here is sample of "Buy now" button code that you need to place on your website:
```html
<html>
  
  <div id='monetha-buy-button-324462580484302'></div>
  
  <script>function buy324462580484302(){var i=new XMLHttpRequest;i.open('GET','https://api-sandbox.monetha.io/api/v1/deals/execute?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJvcmRlciI6eyJjcmVhdGVkX2F0IjoiMDAwMS0wMS0wMVQwMDowMDowMFoiLCJ1cGRhdGVkX2F0IjoiMDAwMS0wMS0wMVQwMDowMDowMFoiLCJkZWFsIjp7ImNyZWF0ZWRfYXQiOiIwMDAxLTAxLTAxVDAwOjAwOjAwWiIsInVwZGF0ZWRfYXQiOiIwMDAxLTAxLTAxVDAwOjAwOjAwWiIsIm1lcmNoYW50X2lkIjoxLCJtZXJjaGFudCI6eyJjcmVhdGVkX2F0IjoiMDAwMS0wMS0wMVQwMDowMDowMFoiLCJ1cGRhdGVkX2F0IjoiMDAwMS0wMS0wMVQwMDowMDowMFoiLCJjb21wYW55X2NvZGUiOiIiLCJjb21wYW55X25hbWUiOiIiLCJjb21wYW55X3JlZ2lzdHJhdGlvbl9hZGRyZXNzIjoiIiwid2FsbGV0X2FkZHJlc3MiOiIiLCJjbGllbnQiOnsiY3JlYXRlZF9hdCI6IjAwMDEtMDEtMDFUMDA6MDA6MDBaIiwidXBkYXRlZF9hdCI6IjAwMDEtMDEtMDFUMDA6MDA6MDBaIn19LCJkZWFsXNOWAY1cyI6e30sImFtb3VudF9maWF0IjoxOTkuOTksImN1cnJlbmN5X2ZpYXQiOiJVU0QiLCJsaW5lX2l0ZW1zIjpbeyJjcmVhdGVkX2F0IjoiMDAwMS0wMS0wMVQwMDowMDowMFoiLCJ1cGRhdGVkX2F0IjoiMDAwMS0wMS0wMVQwMDowMDowMFoiLCJuYW1lIjoiTXUgVW5pcXVlIGFuZCBwcmljZWxlc3MgaXRlbSIsImFtb3VudF9maWF0IjoxOTkuOTksInF1YW50aXR5IjoxfV19LCJleHRlcm5hbF9vcmRlcl9pZCI6IjEiLCJvcmRlcl9zdGF0dXNfaWQiOjAsInJldHVybl91cmwiOiJ3d3cuZ29vZ2xlLmNvbSIsImNhbGxiYWNrX3VybCI6Imh0dHBzOi8vcGF5bWVudC5tb25ldGhhLmlvL21vbmV0aGFidXR0b24vY2FsbGJhY2siLCJvcmRlcl9zdGF0dXMiOnt9fX0.XOzz_IqQuB5schE8Xh7ZxzyAgC7huhpnJmzS_Z45eGw',!0),i.onreadystatechange=function(){4==this.readyState&&201==this.status?(res=JSON.parse(this.responseText),window.location.href=res.order.payment_url):console.error('MONETHA: '+this.responseText)},i.send()}!function(){var i=document.getElementById('monetha-buy-button-324462580484302'),o=document.createElement('a');o.href='javascript:buy324462580484302();',o.innerText='Buy Now',o.setAttribute('style','border-radius: 5px;font-weight:400;line-height:1.42857143;text-align:center;touch-action:manipulation;cursor:pointer;border: 1px solid transparent;background-color:#094da0;border-color:#094da0;color:#fff;text-decoration:none;font-size: 15px;padding: 6px 25px;border-radius: 5px;font-weight:400;line-height:1.42857143;text-align:center;touch-action:manipulation;cursor:pointer;border: 1px solid transparent;background-color:#094da0;border-color:#094da0;color:#fff;text-decoration:none;'),i.appendChild(o)}();</script>
  
</html>
```
