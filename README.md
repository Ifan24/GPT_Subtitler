# GPT Subtitler

[GPT Subtitler](https://gptsubtitler.com) is a web application designed to translate subtitles into any language using powerful Large Language Models (LLMs) like OpenAI's GPT, Claude, or Gemini. This serverless application, built with AWS Serverless Stack (SST), provides a seamless, efficient, and scalable solution for subtitle translation.

## Features

- **Multi-Language Support**: Translate subtitles into any language supported by the integrated LLMs.
- **Customizable Settings**: Adjust translation settings such as language, model selection, temperature, prompt customization, and few-shot examples.
- **Batch Processing**: Translate multiple subtitle files at once for increased efficiency.
- **Real-Time Progress Tracking**: Monitor the translation process in real-time.
- **Token-Based Pricing**: Use tokens for translations, eliminating the need for an API key.
- **Stripe Integration**: Secure and seamless payment processing with Stripe.
  
✨ Supports high-quality subtitle translation using various models such as Anthropic Claude, GPT-3.5, and GPT-4. Currently, the Claude-Haiku model is recommended.

Additionally, the Gemini-1.5-flash and Gemini-1.5-pro models are available for free users to try, although they may not be as accurate as the Claude-Haiku model.

## Technology Stack

- **Frontend**: React.js
- **Backend**: AWS Lambda, DynamoDB, Cognito, S3
- **Framework**: AWS Serverless Stack (SST)
- **Payments**: Stripe
- **LLMs**: OpenAI, Claude, Gemini

## How It Works

1. **Upload Subtitle Files**: Users can upload their subtitle files in various formats.
2. **Customize Settings**: Configure translation settings according to your preferences and needs.
3. **Translate**: Start the translation process and monitor progress in real-time.
4. **Download**: Once the translation is complete, download the translated subtitles.

## Benefits

- **Efficiency**: Reduces the typical subtitle translation workflow from hours to minutes.
- **Cost-Effective**: Offers various pricing options based on the model used, ensuring affordability.
- **Scalability**: Built using a serverless architecture, allowing seamless scaling as user demand grows.
- **User-Friendly**: Intuitive interface for easy navigation and use.

## Future Plans

We are continuously working to improve GPT Subtitler. Future updates will include more language support (with few-shot examples and UI localization), enhanced translation quality, and additional customization options.

## Promo

Thanks for your support and for reading this far! 🙏

Here is a redemption code for 100,000 tokens: `GPTSubtitler_github_repo`

You can use it at [Settings](https://gptsubtitler.com/settings)


## Contact

For more information or support, please contact us at [ifan.web24@gmail.com](mailto:ifan.web24@gmail.com).
