

## Overview
# Size Guide Application

## Deployed Link
You can view the live application here: [Size Guide App](https://test-ui-desigual.netlify.app/)

## Overview
The **Size Guide App** provides users with an intuitive interface to explore size measurements for various clothing items. It allows users to switch between international size standards and body measurement guidelines, ensuring they find the best fit.


## Features
- **Interactive Tabs**: Switch seamlessly between international sizes and body measurements.
- **Measurement Units**: Toggle between centimeters (CM) and inches (IN) for body measurements. (not implemented)
- **Responsive Design**: Fully optimized for desktop and mobile devices.



-----------------------------------------------------------------------------------

If this were a real-world application, the distribution of components would be designed to maximize reusability and scalability, allowing UI elements to be repurposed for other tasks and features.

### 1. Main Components
- **SizeGuide**: The parent component managing the layout and structure of the size guide.
- **Header**: Displays the title and subsections for categories like tops, pants, skirts, etc.
- **MenuSize**: Contains navigation tabs (International Sizes and Body Measures) and the unit toggle feature.
- **Content**: Dynamically displays the selected tab's content using active state management.
- **TableResponsive**: A reusable component for rendering tabular data in both sections.
- **ImageSection**: Displays body measurement visuals.

### 2. Reusable Utility Components
- **Tabs**: Handles navigation logic and visual states for active/inactive tabs.
- **MeasurementToggle**: Provides options to switch between CM and IN.
- **ResponsiveTable**: Renders data dynamically for both international and body measurement sections.
