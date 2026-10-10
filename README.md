# ICE Task 4 – Weather Dashboard & UI Debugging

# Introduction
This project involves debugging and testing a React Native weather dashboard developed with Expo and TypeScript. The dashboard displays weather information for Johannesburg, Cape Town, and Durban using hardcoded data.
The application includes current weather conditions, a 24-hour forecast, a five-day forecast, Sun & Moon information, and additional weather details.

# Development Environment
- Framework: React Native
- Development tool: Expo
- Programming language: TypeScript
- Code editor: Visual Studio Code
- Testing environment: Institutional virtual machine
- Android emulator:BlueStacks 5
- Testing application: Expo Go

# Error Log
| Location / feature | Problem identified | Correction made |
|---|---|---|
| Imports | `ImageBackground` was used without being imported. | Added `ImageBackground` to the React Native imports. |
| City selector | The selector compared the selected city with the country. | Updated the comparison to use the city name. |
| City selection | Selecting a city stored its country instead of its city. | Updated the selected value to use the city name. |
| Background image | The background image source was not provided in the expected format. | Used the image URL in a `uri` object. |
| Humidity | The humidity field displayed the feels-like temperature. | Connected the humidity display to the humidity data. |
| Hourly forecast | The hourly forecast was configured for vertical scrolling. | Changed it to horizontal scrolling. |
| Hourly forecast | Every hourly card displayed the current temperature. | Connected each card to its hourly temperature. |
| Five-day forecast | The daily forecast mapping did not return the card elements. | Corrected the mapping so the cards render. |
| High and low temperatures | The daily high and low values were reversed. | Corrected the high and low temperature bindings. |
| Sun & Moon | The sunrise field displayed the sunset value. | Connected it to the sunrise data. |
| Weather details | The details component displayed the label instead of the value. | Updated it to display the supplied value. |

# Conclusion
This task involved identifying and correcting issues in the weather dashboard's React Native and TypeScript code. The corrections addressed city selection, image rendering, forecast data, temperature displays, and weather detail values.
The application was tested using Expo Go in BlueStacks 5. The final testing results and screenshot document the application's actual behaviour after debugging.
