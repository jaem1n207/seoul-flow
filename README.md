# SeoulFlow

<p align="center">
  <a href="README.ko.md">한국어</a> | <a href="README.md">English</a>
</p>

<p align="center">
  <img src="src/assets/logo.png" alt="SeoulFlow Logo" width="200"/>
</p>

<p align="center">
  <b>Metro Tracker, Crowd Data, Best Visit Time</b>
</p>

<!-- <p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.seoulflow.app"><img src="assets/google-play-badge.png" alt="Get it on Google Play" height="40"></a>
  <a href="https://apps.apple.com/app/seoulflow/id1234567890"><img src="assets/app-store-badge.png" alt="Download on the App Store" height="40"></a>
  <a href="https://seoulflow.app"><img src="assets/web-badge.png" alt="Open Web App" height="40"></a>
</p> -->

## Introduction

SeoulFlow is an app that provides real-time location and congestion information for the Seoul metropolitan subway system, along with optimal visit times for major locations. Through subway car-specific congestion predictions and crowdedness information for shopping malls and tourist attractions, it helps users move and visit places more comfortably.

## Key Features

### Subway Information

- 📍 Real-time Seoul metro subway tracking
- 🔍 Station search and favorites
- ⏱️ Real-time arrival information
- 📊 Per-car congestion prediction

### Location Information

- 🏙️ Crowdedness info for shopping and leisure places
- 🕒 Optimal visit time recommendations
- 📈 Visitor trend analysis

### Upcoming Features

- 🗺️ Korean travel data information
- 🔄 Popular destinations and visit patterns by region

<!-- ## Screenshots

<p align="center">
  <img src="assets/screenshots/screenshot1.png" width="200" alt="Real-time subway location and congestion">
  <img src="assets/screenshots/screenshot2.png" width="200" alt="Place congestion and optimal visit times">
  <img src="assets/screenshots/screenshot3.png" width="200" alt="Favorites and search functions">
  <img src="assets/screenshots/screenshot4.png" width="200" alt="Visitor trend analysis">
</p> -->

## Technology Stack

- **Frontend**: [Lynx](https://lynxjs.org/) - Android, iOS, web cross-platform support
- **API Integration**:
  - Seoul Metro Open API
  - Korea Tourism Organization API
  - SK open API
  - Other congestion data sources

## Installation & Development

### Development Setup

```bash
# Clone the repository
git clone https://github.com/jaem1n207/seoul-flow.git
cd seoul-flow

# Install dependencies
pnpm install

# Run development server
pnpm run dev
```

Scan the QR code in the terminal with your LynxExplorer App to see the result.
You can start editing the page by modifying `src/App.tsx`. The page auto-updates as you edit the file.

## Contributing

If you'd like to contribute to SeoulFlow, please follow these steps:

1. Fork the repository.
2. Create a new feature branch (git checkout -b feature/amazing-feature).
3. Commit your changes (git commit -m 'Add some amazing feature').
4. Push to the branch (git push origin feature/amazing-feature).
5. Open a Pull Request.

For detailed contribution guidelines, please refer to [CONTRIBUTING.md](./CONTRIBUTING.md).

## License

This project is distributed under the MIT License. See the LICENSE file for more information.

## Contact

- Project Maintainer: [tech.jmtt@gmail.com](mailto:tech.jmtt@gmail.com)
- Website: [https://bendd.me/](https://bendd.me/)
- Issue Tracker: [GitHub Issues](https://github.com/jaem1n207/seoul-flow/issues)

<p align="center">
  SeoulFlow - Enjoy Seoul more comfortably!<br>
  ❤️
</p>
