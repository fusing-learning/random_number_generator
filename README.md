# Random Number Generator

A web-based random number generator with advanced features including duplication control, sorting options, and mobile-responsive design.

## Features

### Basic Generation
- Set custom lower and upper limits for number range
- Generate any number of random numbers
- Input validation to ensure valid integer ranges

### Duplication Control
- Choose whether to allow duplicate numbers in results
- When duplications are enabled, specify exact frequency for each number
- Auto-population feature: automatically fills remaining total when only one number has frequency 0
- Utility buttons: "Fill All" (random distribution) and "Clear All" for quick setup
- Range limit warning: alerts when range exceeds 200 numbers (soft limit)

### Sorting Options
- No sorting (random order)
- Ascending order
- Descending order

### User Interface
- Clean, intuitive design with radio button controls
- Mobile-responsive layout
- Real-time validation feedback
- Vertical results display for better readability
- Support light & dark themes

## How to Use

1. **Set Range**: Enter your desired lower and upper limits
2. **Set Count**: Specify how many numbers to generate
3. **Choose Duplication**: Select "Yes" or "No" for allowing duplicates
4. **Configure Frequencies** (if duplications enabled):
   - Manually set frequency for each number, or
   - Use "Fill All" for random distribution, or
   - Use "Clear All" to reset all frequencies
5. **Choose Sorting**: Select your preferred sorting option
6. **Generate**: Click "Generate Numbers" to see results

## Technical Details

- **File**: Single HTML file with embedded CSS and JavaScript
- **No Dependencies**: Runs in any modern web browser
- **Responsive Design**: Works on desktop and mobile devices
- **Client-Side**: All processing happens in the browser

## Input Validation

- Automatically converts decimal inputs to integers
- Prevents negative numbers
- Validates that lower limit is less than upper limit
- Ensures total frequencies equal the requested count (when duplications enabled)
- Provides clear error messages for invalid inputs

## Performance

- Optimized for ranges up to 200 numbers when duplications are enabled
- Warning displayed for larger ranges but generation still allowed
- Efficient algorithms for both unique and duplicate number generation

## Browser Compatibility

Compatible with all modern browsers including Chrome, Firefox, Safari, and Edge.