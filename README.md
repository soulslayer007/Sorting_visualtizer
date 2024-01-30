## Sorting Visualizer

This project provides a web-based sorting visualizer that allows users to interactively visualize various sorting algorithms in action. The visualizer is implemented using HTML, CSS, and JavaScript, and it supports algorithms such as Selection Sort, Bubble Sort, Insertion Sort, Merge Sort, Quick Sort, and Heap Sort.

### Features

- **Interactive Interface**: Users can adjust the array size and sorting speed using sliders and select different sorting algorithms from a dropdown menu.
- **Real-time Visualization**: The sorting process is visually represented in real-time, with bars representing array elements being dynamically rearranged according to the chosen sorting algorithm.
- **Responsive Design**: The visualizer interface is responsive and adapts well to different screen sizes and devices.
- **Multiple Sorting Algorithms**: Users can choose from a variety of sorting algorithms to visualize their differences in performance and behavior.

### Usage

1. Open the `index.html` file in a web browser.
2. Adjust the array size and sorting speed using the sliders.
3. Choose a sorting algorithm from the dropdown menu.
4. Click on "Generate New Array" to create a new random array.
5. Click on the chosen sorting algorithm to start the visualization.

### File Structure

- **`index.html`**: The main HTML file containing the visualizer interface.
- **`index.css`**: The CSS file for styling the visualizer components.
- **`script.js`**: The JavaScript file containing the implementation of sorting algorithms and user interaction logic.

### Functions

1. **`setup()`**: Initializes the visualizer and generates a new array based on user input.
2. **`reset()`**: Resets the visualizer by reloading the page.
3. **`Disable_The_Input()`**: Disables user input during sorting and returns the chosen delay for visualization.
4. **`Finished_Sorting()`**: Marks the end of sorting by enabling user input and highlighting the sorted elements.
5. **`generateBars(n)`**: Generates a new random array with the specified number of elements.
6. **`Sleep(ms)`**: Asynchronously delays execution for the specified duration.
7. **`MapRange(value, in_min, in_max, out_min, out_max)`**: Maps a value from one range to another.

### Sorting Algorithms

- **Selection Sort**
- **Bubble Sort**
- **Insertion Sort**
- **Merge Sort**
- **Quick Sort**
- **Heap Sort**

Each sorting algorithm is implemented as an asynchronous function, allowing for real-time visualization of the sorting process.

### Future Enhancements

1. **Color Customization**: Allow users to customize the colors of the bars and background.
2. **Algorithm Analysis**: Provide visualizations of time complexity and comparisons between sorting algorithms.
3. **Additional Sorting Algorithms**: Implement more sorting algorithms for comparison and education.

Feel free to contribute to this project by submitting pull requests or reporting issues. Happy sorting!
