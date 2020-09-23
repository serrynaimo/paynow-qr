# paynow-qr
Mobile friendly landing page to generate transaction specific Singapore PayNow QR codes.
See example at https://serrynaimo.github.io/paynow-qr/?amount=10.00&reference=Invoice%2020200923

## Setup
Clone this repo, change the following variables in the index.html to your company name and UEN and host on your own website for more customer trust.
```js
const uen = '201207337D' // CHANGE TO YOUR UEN
const entity = 'Nerdherd Pte Ltd' // CHANGE TO YOUR ENTITY NAME
```

## Connected Payment Service in Xero
You can configure this neatly as a [Custom URL](https://central.xero.com/s/article/Custom-URL) in your Xero settings for Connected Payment Services. Use e.g.:
`https://[yourdomain]/paynow-qr/?amount=[AMOUNTDUE]&reference=[INVOICENUMBER]`

## License
MIT
