# Install Widget on Your Website

## Widget builder

For ease of use, please use our [widget builder](https://reviewdrop.io/embed) from your dashboard.

![](../.gitbook/assets/widget-graphic.png)

| Option | Values |
| :--- | :--- |
| **Button Position** - Either bottom left or right if using chat widget. | Left/Right |
| **Display Message** - Ability to hide button message completely. | Yes/No |
| **Message on mobile?** - Ability to hide button message on mobile. | Yes/No |
| **Branding Color** - \(Experimental: Changes top header area on widget.\) | HEX |
| **Delay Pop-Up Time** - Change duration before button appears on site. | Normal/Fast/Long |

After you have selected your desired customizations, click "Create Widget" and copy the code to your clipboard.

## Standard

The Reviewdrop widget has been designed to work virtually anywhere. Just paste in the script code just before the **&lt;/head&gt;** closing tag on your site. Many website builders/cms tools have header script management built in. 

## WordPress

To install the widget with WordPress, please navigate to your admin dashboard

1. Login to your WordPress admin dashboard.

![](../.gitbook/assets/screenshot-2018-12-08-at-14.02.59.png)

2. Head to **Plugins -&gt; Add new**

3. Search for Reviewdrop or download the plugin [here](https://wordpress.org/plugins/reviewdrop/).

4. Install and activate the plugin and head to the settings page to configure.

5. If you are on a paid plan, you can also add automatic email invites once a customer has ordered on Woocommerce. For more information, visit our conversion section.

## Squarespace

{% hint style="info" %}
The install method below requires a Squarespace Business or Commerce plan.
{% endhint %}

1. Navigate to your Squarespace admin page and click **Settings -&gt; Advanced -&gt; Code Injection**
2. On the **Footer** section, paste in the Reviewdrop embed code and hit save.

![](../.gitbook/assets/squarespace.gif)

#### What about personal Squarespace plans?

Unfortunately it seems Squarespace require you to be on a Business or Commerce plan to add external scripts or edit theme code now. Please get in touch with Squarespace support to find out more.

## BigCommerce

We are working on adding an app to the BigCommerce store. In the meantime you can navigate to:

{% hint style="info" %}
Bigcommerce Dashboard -&gt; Storefront -&gt; Footer Scripts
{% endhint %}

Paste in the embed code from the [builder](customise-widget-looks.md) and hit save.

![](../.gitbook/assets/bc.gif)

## Shopify

To install the widget on Shopify we need to add the script to the footer. We will look at making this process easier through their app store in the future.

1. Navigate to your Shopify dashboard and click **Online Store -&gt; Themes**
2. Copy the embed code from Reviewdrop and head back to Shopify.

![](../.gitbook/assets/screenshot-2018-12-22-at-12.57.31.png)

3. Click **Actions -&gt; Edit code** 

![](../.gitbook/assets/screenshot-2018-12-22-at-13.00.02.png)

4. Search for **footer.liquid** on the editor sidebar. Please note: this may vary depending on the theme installed. Click on footer.liquid to open the file.

![](../.gitbook/assets/screenshot-2018-12-22-at-13.01.28.png)

5. Search for the closing **&lt;/footer&gt;** tag and paste in the Reviewdrop embed code directly below it.

6. Hit save at the top right and you should be good to go!

![](../.gitbook/assets/shopify.gif)

## Wix

To install Reviewdrop on a Wix powered site, please refer to their documentation: [https://support.wix.com/en/article/embedding-custom-code-to-your-site](https://support.wix.com/en/article/embedding-custom-code-to-your-site)

1. Use **Custom Code** on the **Tracking & Analytics** section under **Advanced Settings**.
2. Click **New Tool -&gt; Custom Code.**
3. Paste the Reviewdrop embed code into the **Body -** **end** input field box.
4. Hit save, and you should be good to go!

