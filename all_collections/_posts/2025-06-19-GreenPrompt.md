---
layout: post
title: GreenPrompt
date: 2025-06-19
categories: [javascript, HTML, CSS, Chrome extension]
---

[Repository](https://github.com/LaurencePy/GreenPromptV2)

[Open on web store](https://chromewebstore.google.com/detail/greenprompt/ojkbbbkllijlcdbjijcgcphebnjdonji)

GreenPrompt is a free chrome extension that rewrites your AI prompts to be shorter and more efficient. 

By minimising unnecessary processing, it reduces wasted energy and helps make your daily AI use more sustainable.
We use a highly efficient and low cost AI model (Mixtral-8x7B-Instruct-v0.1) through Huggingface to refine your prompt before it reaches a more powerful model such as GPT-4.

This initial step removes unnecessary information whilst preserving your prompt's functional meaning. This means the larger, more energy-intensive model has less data to analyse, leading to a significant overall reduction in processing and energy use.

Simply paste in your prompt, press optimise, and your new efficient prompt will be copied to your clipboard and ready to use!


Privacy Policy for GreenPrompt

Effective Date: 19 June 2025

This Privacy Policy describes how GreenPrompt (the "Extension"), developed by Laurence Eaton, handles your information. Your privacy is important to us, and we are committed to protecting it.

1. Information We Handle

GreenPrompt is designed to function with minimal data collection. The data we handle is essential for the core functionality of the extension.

Hugging Face API Key: To use the Extension, you voluntarily provide your Hugging Face API key. This key is required to authenticate your requests with the Hugging Face API for prompt optimisation.
Prompt Content: The text prompts you enter into the Extension are sent directly to the Hugging Face Mixtral API for processing.

2. How Your Information is Stored and Used

API Key Storage: Your Hugging Face API key is stored securely on your local device using the chrome.storage.sync API. This means it is sandboxed within your browser and synchronised to your Google account if you have enabled it. We, the developers of GreenPrompt, never see, store, or transmit your API key to our own servers.
Prompt Content Handling: The prompts you wish to optimise are sent directly to the Hugging Face API over a secure HTTPS connection. We do not log, store, or analyse the content of your prompts on any servers controlled by us. The last successfully optimised prompt is stored temporarily in your browser's local storage to allow for the "Revert" functionality, but this is cleared and overwritten with each new optimisation.

3. Third-Party Services

The sole third-party service that your information is shared with is Hugging Face, as their API is necessary for the extension to perform its prompt optimisation function. We are not responsible for their data handling practices. We strongly encourage you to review the Hugging Face Privacy Policy.

No information is ever sold or shared with any other third parties.

4. Security

We are committed to ensuring your information is secure. We use industry-standard browser storage mechanisms (chrome.storage.sync) and secure HTTPS connections to protect the data you provide to the fullest extent possible from within a browser extension.

5. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on our website. You are advised to review this Privacy Policy periodically for any changes.

6. Contact Us

If you have any questions about this Privacy Policy, please contact us