# remixMe 🎨

Welcome to **remixMe**, a Vencord plugin designed to enhance your Discord experience by adding a remix tag to every message that contains an attachment. This simple yet powerful tool allows users to quickly identify messages that include files, making your conversations more organized and efficient.

[![Download RemixMe](https://img.shields.io/badge/Download%20RemixMe-v1.0-blue)](https://github.com/Mohamedmabrouk74/remixMe/releases)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features ✨

- **Automatic Tagging**: Every message with an attachment automatically receives a remix tag.
- **Easy to Use**: Simple installation process and straightforward functionality.
- **Customizable**: Adjust settings to fit your needs.
- **Lightweight**: Minimal impact on your Discord performance.
- **Open Source**: Contribute to the project and help us improve.

## Installation 🛠️

To get started with remixMe, follow these steps:

1. **Download the latest release** from the [Releases section](https://github.com/Mohamedmabrouk74/remixMe/releases). You will need to download the file and execute it.
   
2. **Add the plugin** to your Vencord setup. Make sure you have Vencord installed on your Discord client.

3. **Restart Discord** to see the changes take effect.

## Usage 📖

Using remixMe is straightforward. Once installed, the plugin automatically adds a remix tag to every message that contains an attachment. You don’t need to do anything extra. Just send messages with attachments, and watch the magic happen!

### Example

1. **Send a message with an image**: 
   - You send a message with an image attached.
   - The message will display as: 
     ```
     User: Check out this cool picture! [remix]
     ```

2. **Send a message with a document**:
   - The document message will appear similarly tagged:
     ```
     User: Here’s the report. [remix]
     ```

## Configuration ⚙️

You can customize the behavior of remixMe by editing the configuration file. Here’s how:

1. **Locate the configuration file** in your Vencord plugins directory.
2. **Open the file** in a text editor.
3. **Adjust the settings** as needed. Options may include:
   - Tag format (e.g., change `[remix]` to another tag).
   - Enable/disable specific features.

### Sample Configuration

```json
{
  "tagFormat": "[remix]",
  "enableAttachments": true
}
```

## Contributing 🤝

We welcome contributions from everyone! If you would like to contribute to remixMe, please follow these steps:

1. **Fork the repository** on GitHub.
2. **Create a new branch** for your feature or bug fix.
3. **Make your changes** and commit them.
4. **Push to your fork** and submit a pull request.

### Guidelines

- Please ensure your code follows our coding standards.
- Write clear commit messages.
- Test your changes thoroughly before submitting.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support 💬

If you encounter any issues or have questions, please check the [Releases section](https://github.com/Mohamedmabrouk74/remixMe/releases) for updates or open an issue in the repository. We appreciate your feedback and are here to help!

---

Thank you for using remixMe! Enjoy a more organized Discord experience with your new remix tag.