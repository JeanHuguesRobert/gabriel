# Gabriel
A framework for web based personal AI assistants

Gabriel is a personal AI assistant designed to enhance critical thinking and protect users against content that may influence them against their interests and values. Gabriel operates as a browser extension and is initially focused on providing support for social networks, with X/Twitter being the first target.


## Core Features
Detects red flags in content on social networks, such as ad hominem attacks, straw man arguments, bandwagon appeals, emotional manipulation, and factually incorrect information.
Observes user behavior and preferences in a non-intrusive way to provide tailored advice and suggestions for actions.
Helps users craft thoughtful, respectful, and critical responses to content on social networks.

## Architecture
Gabriel consists of a browser extension that communicates with site-specific modules for different social networks. The extension is responsible for detecting when the user navigates to a supported social network and activating the appropriate module.


## Development
Gabriel is developed using an iterative, MVP-based approach, with an initial focus on supporting Twitter. The extension uses the following technologies:
Chrome Extension API and Firefox WebExtensions API for interacting with the user's browser.
Social network APIs, such as the Twitter REST API, for accessing and analyzing content.

## Conversational Agents
Gabriel will leverage existing general purpose technology such as OpenAI's API and other AI tools.

## Contributing
Contributions are welcome! Please follow the guidelines below:
Fork the repository and create a new branch for your changes.
Follow the existing code style and conventions.
Write tests for any new features or bug fixes.
Submit a pull request with a clear description of your changes.

## License
Gabriel is licensed under the MIT License. See the LICENSE file for details.
