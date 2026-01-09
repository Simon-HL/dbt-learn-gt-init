{% docs payment_status %}
    
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| success        | Payment went through successfully                |
| fail           | Payment failed                                   |


{% enddocs %}


{% docs payment_method %}
    
One of the following values: 

| status         | definition                                       |
|----------------|--------------------------------------------------|
| credit_card    | Payed with credit card on card terminal          |
| bank_transfer  | Payed by invoice and bank trasnfer               |
| gift_card      | Payed by using a gift card of some sort          |
| coupon         | Cashed in coupon                                 |

{% enddocs %}