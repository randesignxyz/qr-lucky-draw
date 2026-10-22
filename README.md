# Vital Scan & Win — modern editable prototype

Run `npm run dev` to start the local development server (or open index.html directly in a browser).

## UXUI versions

- `index.html` opens UXUI V2 with primary color `#00B6F1`.
- `v1.html` preserves the current UXUI V1 design. Its styles are frozen in `uxui-v1/`.
- `v2.html` is UXUI V2, with separate cyan styles in `uxui-v2/`.
- Use the version links above the prototype to compare both designs. Both versions retain the same interactive flow.

## Customize

- Brand colors: search for --blue and --red in the CSS.
- Layout and styling: search for #vital-flow.
- Screen text and sample prizes: search for function render(screen).
- Wheel: search for .wheel and data-spin.
- Sample manual code: VT7K 8M2P (spaces and lowercase are accepted).
- Logo: embedded as a PNG data URL in the header image. Replace the image src with your own file path if preferred.
- Interactive flow: Navigate using the in-screen action buttons (e.g., scan simulation, code entry, spin, claim). The spin screen includes a selector for win/no-prize outcomes.

## Included flow

QR scan preview → spin → win or no prize → winner name and phone → claim confirmation.
Manual entry is available from the scan screen. A bottle QR would open the spin screen directly in the finished promotion.

## Prize catalog

The prototype includes the updated Apple Tech, Foldable device, and Cash reward prizes:
- **Foldable Smartphone** (`prize-foldable.png`) — Grand Prize (Hero)
- **iPhone 16 Pro** (`prize-iphone16pro.png`)
- **Apple AirPods Max** (`prize-airpods-max.png`)
- **Apple Watch Series** (`prize-apple-watch.png`)
- **$5 Cash Voucher** (`prize-cash5.png`)
- **$1 Cash Voucher** (`prize-cash1.png`)
- **1 Case of Vital Water (24x500ml)** (`prize-watercase.jpg`)
- **Vital Premium Gift Pack** (`prize-giftpack.jpg`)
- **Vital Stainless Tumbler** (`prize-tumbler.jpg`)
- **Try Again / No Prize** (`prize-tryagain.jpg`)

## Prototype limits

Camera scanning, code checking, prize selection and claim submission are simulated. No form information is sent or saved. Campaign prizes and redemption details are samples. The wheel segments do not represent winning probabilities.

Internet access may be needed for preview icons/fonts supplied by the standalone renderer. This is a design prototype, not a connected prize service.

Modern styling is the final CSS section. Blue remains dominant; red highlights the spin and win actions.

# qr-lucky-draw
