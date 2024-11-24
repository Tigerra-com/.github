# Tigerra SDK Libraries for API Integration

Welcome to the Tigerra SDK repositories! Our SDK libraries allow developers to easily integrate and interact with the File Conversion API provided by [Tigerra.com](https://tigerra.com). The API offers support for over 100 different file conversions, including audio, video, images, documents, and fonts.

### Features

- **Multi-Format Conversions**: Convert files across various formats, including audio, video, images, documents, and fonts.
- **Pay-As-You-Go**: Only pay for the conversions you actually use. No upfront costs!
- **Token-Based Authorization**: Secure and personalized API access using token-based authentication.
- **File Privacy**: Files are automatically deleted after conversion, and you can delete them instantly via the API.
- **Usage & Billing Analytics**: Access detailed usage statistics and billing insights for financial transparency.
- **Comprehensive Documentation**: Detailed API documentation, including integration guides and example requests.

### Getting Started

To integrate the Tigerra File Conversion API, follow the steps below to set up your SDK and start making API calls:

1. **Install the SDK**  
   Install the SDK for your preferred programming language from the corresponding repository.

2. **Get Your API Key**  
   Sign up on [Tigerra.com](https://tigerra.com) and get your unique API token for secure access to the API.

3. **Make Your First API Call**  
   Start making API requests to convert files! Below are some examples using `curl`:

### Example API Requests

#### Convert Audio File
```bash
curl -X POST "https://convert.tigerra.com/do-convert/mp3-to-wav" \
-H "Authorization: Bearer your-token" \
-F "file=@/path/file.mp3"
```

Once the conversion is complete, download the converted file using the hash:

```bash
https://convert.tigerra.com/download/hash-of-the-file
```

