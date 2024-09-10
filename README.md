# LiqPay for FOSSBilling
[LiqPay](https://www.liqpay.ua) payment gateway module for [FOSSBilling](https://fossbilling.org)

## Installation

### Automated installation (TODO)
```bash
git clone https://github.com/getnamingo/fossbilling-liqpay
mv fossbilling-liqpay/Liqpay /var/www/library/Payment/Adapter/
chown -R www-data:www-data /var/www/library/Payment/Adapter/Liqpay
```

Now, continue with steps 4-5 from the manual installation section.

### Manual installation
1. Download the latest release from [GitHub](https://github.com/getnamingo/fossbilling-liqpay).
2. In your FOSSBilling installation, navigate to `/library/Payment/Adapter` and create a new folder named `Liqpay`.
3. Extract the contents of the downloaded archive into the `Liqpay` folder.
4. In the FOSSBilling admin panel, go to the "Payment gateways" page, which is located under the "System" menu.
5. Find Liqpay under the "New payment gateway" tab and click the gear (cog) icon to install and configure it.

## Licensing
This extension is licensed under the Apache 2.0 license. See the [LICENSE](LICENSE) file for more information.

## Disclaimer
This extension is not affiliated with LiqPay in any way.