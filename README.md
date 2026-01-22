# Sorting Algorithm Visualizer

An interactive web-based visualization tool for learning and comparing sorting algorithms with real-time animations and performance metrics.

## Modes

### Individual Mode
Learn how each sorting algorithm works step-by-step with detailed explanations:
- **Bubble Sort**: Compares adjacent elements and swaps them if they're in wrong order. Largest element 'bubbles' to the end each pass.
- **Selection Sort**: Finds the smallest element and places it at the beginning. Repeats for remaining unsorted portion.
- **Quick Sort**: Picks a pivot, partitions into smaller and larger, then recursively sorts both partitions.
- **Merge Sort**: Divides array recursively until single elements, then merges back in sorted order.

Features:
- Watch step-by-step visualization with color-coded animations
- See real-time swap/operation counts
- Read algorithm explanations to understand what's happening
- Adjust animation speed for learning
- Regenerate arrays for practice

### Race Mode
Compare all four sorting algorithms side-by-side on the **same dataset**:
- Watch all algorithms sort the identical array simultaneously
- See real-time step counts for each algorithm
- Track the number of swaps performed
- Identify which algorithm is most efficient
- Winner is determined by total steps taken (fewer is better)

## How to Use

### Individual Mode:
1. Click "Individual Mode" tab
2. Select a sorting algorithm from the dropdown
3. Adjust speed with the slider (lower = slower animation)
4. Click "Start Sorting" to watch the visualization
5. Read the algorithm explanation below the visualization

### Race Mode:
1. Click "Race Mode" tab
2. Adjust animation speed if desired
3. Click "Start Race!" to begin
4. Watch all four algorithms compete on the same data
5. Results show the winner (🥇 1st place) with step counts and swap counts

## Visual Elements

**Colors:**
- **Blue**: Unsorted/default state
- **Orange**: Elements being compared
- **Red**: Elements being swapped
- **Green**: Pivot elements
- **Purple**: Elements that are fully sorted/fixed in position

**Metrics:**
- **Steps**: Total number of algorithm operations/comparisons
- **Swaps**: Number of times elements were exchanged

## Technical Details

- Built with vanilla HTML5, CSS, and JavaScript (no dependencies)
- Uses async/await for smooth animation timing
- All algorithms run in parallel during race mode
- DOM elements are directly manipulated for visual progress tracking
- Step counting provides accurate complexity comparison

## Learning Benefits

- **Visualize Algorithm Behavior**: See exactly how each algorithm makes decisions
- **Understand Complexity**: Compare step counts to learn about time complexity
- **Algorithm Selection**: Learn which algorithm works best for different scenarios
- **Interactive Learning**: Pause, replay, and adjust speed to understand deeply
- **Side-by-Side Comparison**: Race mode shows practical performance differences

## Perfect For

- Computer Science students learning sorting algorithms
- Algorithm study and interview preparation
- Teaching data structures and algorithms
- Understanding Big-O notation and algorithm complexity
- Interactive demonstrations in educational settings 
