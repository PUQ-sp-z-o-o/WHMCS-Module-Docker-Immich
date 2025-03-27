# Email Template (puqDockerImmich Update Email)

### Docker Immich module **[WHMCS](https://puqcloud.com/link.php?id=77)** 

#####  [Order now](https://puqcloud.com/whmcs-module-docker-immich.php) | [Download](https://download.puqcloud.com/WHMCS/servers/PUQ_WHMCS-Docker-Immich/) | [FAQ](https://faq.puqcloud.com/) | [n8n](https://puqcloud.com/link.php?id=117)

##### Create an email template for customer notifications.

```
System Settings->Email Templates->Create New Email Template
```

- **Email Type:** Product/service
- **Unique Name:** puqDockerImmich Update Email

[![image-1742326011602.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1742326011602.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1742326011602.png)

**Subject:**

```
Immich Update Information
```

**Body:**

```
Dear {$client_name},

Your instance is currently being updated.
You will be able to use your Immich server again within 3 minutes.

Here is the link to your Immich server.

https://{$service_domain}/
Thank you for choosing us.

{$signature}
```

[![image-1742326094269.png](https://doc.puq.info/uploads/images/gallery/2025-03/scaled-1680-/image-1742326094269.png)](https://doc.puq.info/uploads/images/gallery/2025-03/image-1742326094269.png)