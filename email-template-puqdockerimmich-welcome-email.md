# Email Template (puqDockerImmich Welcome Email)

### Docker Immich module **[WHMCS](https://puqcloud.com/link.php?id=77)** 

#####  [Order now](https://puqcloud.com/whmcs-module-docker-immich.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-Immich/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

##### Create an email template for customer notifications.

```
System Settings->Email Templates->Create New Email Template
```

- **Email Type:** Product/service
- **Unique Name:** puqDockerImmich Welcome Email

[![image-1742325411268.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1742325411268.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1742325411268.png)

**Subject:**

```
Immich Order Information
```

**Body:**

```
Dear {$client_name},

Your order has been accepted for implementation.

Product/Service: {$service_product_name}
Payment Method: {$service_payment_method}
Amount: {$service_recurring_amount}
Billing Cycle: {$service_billing_cycle}
Next Due Date: {$service_next_due_date}


The installation and setup of your Immich instance is in progress.
Within the next 4-5 minutes, you will be able to use your Immich instance.

Upon your first login, you will need to create an account.

Here is the link to your Immich server.

https://{$service_domain}/

Thank you for choosing us.

{$signature}
```

[![image-1742325563570.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1742325563570.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1742325563570.png)