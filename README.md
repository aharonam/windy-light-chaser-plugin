# Windy Landscape Photography Assistant Plugin

A Windy.com plugin that helps landscape photographers assess optimal conditions for sunrise and sunset photography by analyzing cloud coverage and weather conditions.

## Features

- **Cloud Analysis**: Analyzes low, mid, and high cloud coverage using Windy's weather models
- **Two Analysis Modes**:
  - **Red Clouds Mode**: Optimized for high clouds with clear skies beneath, ideal for vivid sunrise/sunset colors
  - **Dramatic Clouds Mode**: Focuses on low or mid-level clouds for moody, dramatic lighting conditions
- **Time of Day Selection**: Toggle between sunrise and sunset analysis
- **Photography Score**: Provides a percentage-based score indicating optimal conditions
- **Location-Based Analysis**: Uses your current location or allows manual location selection

## Installation

1. Visit [Windy.com](https://www.windy.com)
2. Go to the plugins section
3. Search for "Landscape Photography Assistant"
4. Click "Install"

## Usage

1. Open the plugin from the Windy.com sidebar
2. Allow location access when prompted
3. Select your preferred mode:
   - "Red Clouds Mode" for classic sunrise/sunset conditions
   - "Dramatic Clouds Mode" for moody, overcast conditions
4. Toggle between sunrise and sunset analysis
5. View the photography conditions score and recommendations

## How It Works

The plugin analyzes three key factors:
- High cloud coverage (crucial for red cloud effects)
- Mid-level cloud coverage (affects overall lighting)
- Low cloud coverage (impacts visibility and mood)

The score is calculated using weighted factors based on your selected mode:
- Red Clouds Mode: 60% high clouds, 20% mid clouds, 20% low clouds
- Dramatic Clouds Mode: 20% high clouds, 40% mid clouds, 40% low clouds

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This plugin is licensed under the MIT License - see the LICENSE file for details.
