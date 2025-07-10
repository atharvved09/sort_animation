# Sorting Algorithm Visualizer

An interactive web-based visualization tool that demonstrates how different sorting algorithms work in real-time with animated bar charts.

## Features

- **Multiple Sorting Algorithms**: Choose from 4 different sorting algorithms to visualize:
  - **Bubble Sort**: Compares adjacent elements and swaps them if they're in the wrong order
  - **Selection Sort**: Finds the minimum element and places it in the correct position
  - **Quick Sort**: Uses a pivot-based divide-and-conquer approach
  - **Merge Sort**: Divides the array in half and merges sorted subarrays

- **Interactive Controls**:
  - Generate a new random array with a single click
  - Choose any sorting algorithm from the dropdown menu
  - Adjust animation speed with the slider (Slow to Fast)
  - Start the sorting animation with the button

- **Color-Coded Animation**:
  - **Blue**: Unsorted elements
  - **Orange**: Elements being compared
  - **Red**: Elements being scanned
  - **Green**: Elements in their final sorted position
  - **Teal**: Pivot element (in Quick Sort)

## How It Works

1. Click "Generate New Array" to create a random array of 10 numbers (between 10-100)
2. Select a sorting algorithm from the dropdown menu
3. Adjust the animation speed using the slider (lower value = slower animation)
4. Click "Start Sorting" to watch the algorithm in action
5. The bars will animate as elements are compared and swapped
6. Once sorted, all bars turn green to indicate completion

## Visual Elements

- **Container**: White box displaying the 10 bars representing array elements
- **Bar Height**: Proportional to the numeric value
- **Bar Color Changes**: Indicate different operations happening during the sort
- **Smooth Transitions**: CSS transitions make the movement and color changes fluid

## Technical Details

- Built with vanilla HTML5, CSS, and JavaScript (no external dependencies)
- Uses async/await for animation timing and delays
- DOM elements are directly manipulated to show visual progress
- Array indices are tracked alongside DOM elements for accurate sorting visualization

## Perfect For

- Learning how different sorting algorithms work
- Understanding time complexity visually
- Teaching computer science concepts
- Interactive demonstrations in educational settings 
