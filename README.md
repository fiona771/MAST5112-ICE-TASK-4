# ICE Task 4 – Weather Dashboard & UI Debugging

## 1. Introduction

This project involves debugging and testing a React Native weather dashboard developed with Expo and TypeScript. The dashboard displays weather information for Johannesburg, Cape Town, and Durban using hardcoded data.

The application includes current weather conditions, a 24-hour forecast, a five-day forecast, Sun & Moon information, and additional weather details.

## 2. Development Environment

- **Framework:** React Native
- **Development tool:** Expo
- **Programming language:** TypeScript
- **Code editor:** Visual Studio Code
- **Testing environment:** Institutional virtual machine
- **Android emulator:** BlueStacks 5
- **Testing application:** Expo Go

## 3. Error Log

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

## 4. Testing

Complete this section after testing the application in BlueStacks 5 with Expo Go.

| Test | Expected result | Actual result |
|---|---|---|
| Launch application | Dashboard opens without errors. | [Enter your actual result] |
| Johannesburg selection | Johannesburg weather data displays. | [Enter your actual result] |
| Cape Town selection | Cape Town weather data displays. | [Enter your actual result] |
| Durban selection | Durban weather data displays. | [Enter your actual result] |
| Hourly forecast | Hourly cards scroll horizontally and show their own temperatures. | [Enter your actual result] |
| Five-day forecast | Five daily forecast cards display correct highs and lows. | [Enter your actual result] |
| Sun & Moon | Sunrise, sunset, moonrise, moonset, and moon phase display. | [Enter your actual result] |
| Additional weather details | Humidity, wind, UV, visibility, pressure, and feels-like temperature display. | [Enter your actual result] |
| Full dashboard scrolling | All sections can be reached by scrolling. | [Enter your actual result] |

## 5. Screenshot

Insert a screenshot of the working application running in BlueStacks 5 with Expo Go. Ensure the screenshot clearly shows the weather dashboard.

**Screenshot:** [Insert actual screenshot here before submission.]

## 6. Conclusion

This task involved identifying and correcting issues in the weather dashboard's React Native and TypeScript code. The corrections addressed city selection, image rendering, forecast data, temperature displays, and weather detail values.

The application was tested using Expo Go in BlueStacks 5. The final testing results and screenshot document the application's actual behaviour after debugging.