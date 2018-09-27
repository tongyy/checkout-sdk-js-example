# Checkout JS SDK Example

This repository features a React example that uses [Bigcommerce's Checkout JS SDK](https://github.com/bigcommerce/checkout-sdk-js) to illustrate how to build custom checkout solution for a BigCommerce store.

Please note that this checkout is a good starting and reference point, but is not production ready. You should not use this custom checkout in production as it stands.

## Getting Started

### Installation

To pull in this example checkout for quick demos, grab the latest build via the CDN:

```
<script src="https://cdn8.bigcommerce.com/s-65xv2m9zph/content/20180927.js"></script>
```


### Usage

Add a `<div>` element above the `<script>` tag with the id of `checkout-app` in the page where you want the checkout to be render:

```
<div id="checkout-app"></div>
```

## Development

To run this example locally, simply run the following:

```
npm install && npm run dev
```

To build:

```
npm run build
```


## See Also

* [Checkout JS SDK](https://github.com/bigcommerce/checkout-sdk-js)
* [Storefront APIs](https://developer.bigcommerce.com/api/v3/storefront.html)
* [React](https://reactjs.org/)

## License

This repository is [MIT Licensed](LICENSE.md).
