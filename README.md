# ManiyaTech Hyvä Homepage-Banner-Slider module for Magento 2

The **ManiyaTech\_HyvaHomepageBannerSlider** module enables Magento 2 store owners to display a fully responsive, lightweight, and customizable homepage banner slider, built specifically for **Hyvä Themes** using **Splide.js**.

It supports separate images for desktop and mobile, customizable titles and buttons, lazy loading, preload, and multi-store views. The slider is designed with performance, accessibility, and Magento coding standards in mind.

## ✨ Features

* 📱 Responsive design for mobile and desktop
* 🎞️ Built with [Splide.js](https://splidejs.com/)
* 🖼️ Separate desktop/mobile image support
* 🧠 Configurable options (autoplay, arrows, dots, slide count)
* 🧩 Multi-store view compatible
* ⚙️ Admin grid and backend configuration
* ⚡ Lazy loading and image preload support
* 🧼 Follows Magento and Hyvä coding standards

## How to install ManiyaTech_HyvaHomepageBannerSlider module

### Composer Installation

Run the following command in Magento 2 root directory to install ManiyaTech_HyvaHomepageBannerSlider module via composer.

#### Install

```
composer require maniyatech/magento2-hyva-homepage-banner-slider
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
```
Let Hyvä recognize the module: 

```
php bin/magento hyva:config:generate
```

Generate Tailwind CSS:

```
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind run build-prod
```

If you're using a custom theme:

```
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run build-prod
```

#### Update

```
composer update maniyatech/magento2-hyva-homepage-banner-slider
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
```

Run below command if your store is in the production mode:

```
php bin/magento setup:di:compile
```

### Manual Installation

If you prefer to install this module manually, kindly follow the steps described below - 

- Download the latest version [here](https://github.com/maniyatech/magento2-hyva-homepage-banner-slider/archive/refs/heads/main.zip) 
- Create a folder path like this `app/code/ManiyaTech/HyvaHomepageBannerSlider` and extract the `main.zip` file into it.
- Navigate to Magento root directory and execute the below commands.

```
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
```

Let Hyvä recognize the module: 

```
php bin/magento hyva:config:generate
```

Generate Tailwind CSS:

```
npm --prefix vendor/hyva-themes/magento2-default-theme/web/tailwind run build-prod
```

If you're using a custom theme:

```
npm --prefix app/design/frontend/<Vendor>/<Theme>/web/tailwind run build-prod
```