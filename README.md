# WhatsApp API Home Assistant Add-on

This add-on wraps the chrishubert/whatsapp-api Docker image so it can run on Home Assistant OS.

## Installation

1. Copy this folder into `/addons/whatsapp-api/` on your Home Assistant OS.
2. Go to **Settings → Add-ons → Add-on Store**.
3. Click the three dots (⋮) in the top right → **Reload**.
4. You should now see **WhatsApp API** in the local add-ons section.
5. Install it, start it, and open the Web UI to scan the QR code.

## Usage

Once running, the API will be available on port 3000.  
You can send messages using Home Assistant's `rest_command` integration or via the `wapi-custom-notifier` HACS component.
