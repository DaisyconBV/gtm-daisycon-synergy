# Daisycon Synergy Tag for Google Tag Manager

This official Daisycon Google Tag Manager (GTM) template is a crucial client-side component for advertisers implementing server-side or hybrid conversion tracking. It enhances the accuracy of your affiliate marketing attribution by creating a robust link between user clicks and server-to-server conversion events.

## Purpose and Functionality

The Daisycon Synergy Tag works in tandem with your server-side GTM setup to enable reliable hybrid tracking. Its primary purpose is to ensure accurate click data matching and provide a fallback mechanism if the primary server-side tracking encounters issues.

* **Hybrid Tracking Enablement**: Fires a lightweight tracking pixel from the user's browser, sending a unique `Synergy Reference` to Daisycon. This signal is used to accurately match a more detailed conversion event sent from your server.
* **Accurate Attribution**: Guarantees that server-side conversions are correctly matched to the original affiliate click, preventing data loss and ensuring publishers are credited correctly.
* **Reliable Fallback**: Acts as a safety net. In cases where a server-to-server event might fail, this client-side signal helps secure the attribution.

By bridging the gap between client-side user actions and server-side data, this tag is an essential tool for a complete and accurate conversion tracking strategy with Daisycon.

## Setup and Configuration

For detailed setup instructions and guidance on how to integrate this tag with your server-side setup, please refer to our comprehensive knowledge base article:

[How to set up Hybrid Tracking with the Daisycon Synergy Tag](https://www.daisycon.com/en/support/knowledge-base/hybrid-tracking-gtm/)