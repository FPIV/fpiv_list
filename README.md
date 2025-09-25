# 🎯 `fpiv_list`: The Core Algorithm Arsenal

A high-performance, production-ready library of list-based algorithms, forged by **FPIV**. This is the foundational component of our digital arsenal, providing the essential, battle-tested tools for achieving algorithmic supremacy in Dart.

---
## Why `fpiv_list`?

This library was built not just to provide functions, but to provide a competitive edge.

* **⚔️ Comprehensive Arsenal:** An extensive collection of over 40 algorithms, covering everything from fundamental sorting and searching to highly specialized and advanced list manipulation techniques.
* **🚀 Performance-Driven:** Every algorithm is implemented with a focus on efficiency. Our detailed benchmarks demonstrate superior performance, allowing you to build fast and responsive applications.
* **🛡️ Production-Ready & Robust:** With over 140+ unit tests, thorough documentation, and robust error handling for edge cases, `fpiv_list` is built for reliable use in production environments.
* **🧬 Modern & Type-Safe:** Written in modern Dart, leveraging generics (`<T extends Comparable<T>>`) to provide a clean, type-safe, and predictable API.

## Algorithms Included

This library is a complete toolkit for list manipulation, including (but not limited to):

* **Advanced & Basic Sorting:**
    * Quick Sort, Merge Sort, Heap Sort, Comb Sort, Radix Sort, Bucket Sort, and **over 20 more** powerful sorting algorithms.
* **Efficient Searching:**
    * Binary Search (for sorted lists), Linear Search.
* **Subarray & Subsequence Problems:**
    * Kadane's Algorithm, Max Product Subarray, Longest Increasing Subsequence, Two Sum, and more.
* **Core List Utilities:**
    * Find Max/Min, Reverse, Rotate, Find Duplicates, Remove Duplicates, Prefix Sum, and more.

> For a complete list of all available functions, please refer to the API documentation.

## Installation


Add `fpiv_list` to your `pubspec.yaml` dependencies:

```yaml
dependencies:
  fpiv_list: ^0.1.0 # Check pub.dev for the latest version
```

Then, import the library in your Dart code:

```dart
import 'package:fpiv_list/fpiv_list.dart';
```

## Quick Start
```dart
import 'package:fpiv_list/fpiv_list.dart';

void main() {
  var numbers = [10, 7, 8, 9, 1, 5];
  print('Original List: $numbers');

  // Use a high-performance sort from the arsenal
  quickSort(numbers, 0, numbers.length - 1);
  print('Sorted with Quick Sort: $numbers');

  // Find an element efficiently
  final index = binarySearch(numbers, 8);
  print('Found 8 at index: $index'); // Output: Found 8 at index: 2
}
```
## Performance ⚡

Performance is a core feature. Our benchmarks show a clear distinction between efficient and inefficient algorithms.

**Sample Benchmark: 10,000 Elements**

| Algorithm | List Size | Time (ms) |
| --- | --- | --- |
| Bubble Sort | 1,000 | 11 ms  |
| Insertion Sort | 1,000 | 5 ms  |
| Selection Sort | 1,000 | 7 ms  |
| Gnome Sort | 1,000 | 9 ms  |
| Odd-Even Sort | 1,000 | 11 ms  |
| Pancake Sort | 1,000 | 10 ms  |
| Cycle Sort | 1,000 | 20 ms  |
| Comb Sort | 1,000 | 2 ms  |
| Stooge Sort (slow!) | 1,000 | 1241 ms  |
| Quick Sort | 1,000 | 1 ms  |
| Merge Sort | 1,000 | 5 ms  |
| Heap Sort | 1,000 | 1 ms  |
| Shell Sort | 1,000 | 2 ms  |
| Counting Sort | 1,000 | 1 ms  |
| Radix Sort | 1,000 | 4 ms  |
| Pigeonhole Sort | 1,000 | 1 ms  |
| Bitonic Sort | 1,000 | 2 ms  |
| Linear Search | 1,000 | 0 ms  |
| Binary Search | 1,000 | 0 ms  |
| Find Max | 1,000 | 0 ms  |
| Find Min | 1,000 | 0 ms  |
| Reverse List | 1,000 | 0 ms  |
| Find Duplicates | 1,000 | 2 ms  |
| Remove Duplicates | 1,000 | 2 ms  |
| Rotate Array Right | 1,000 | 0 ms  |
| Quickselect (k=size/2) | 1,000 | 0 ms  |
| Kadane's Algorithm | 1,000 | 0 ms  |
| Max Product Subarray | 1,000 | 2 ms  |
| Max Sum (k=10) | 1,000 | 0 ms  |
| Min Sum (k=10) | 1,000 | 0 ms  |
| Average (k=10) | 1,000 | 0 ms  |
| LIS Binary Search | 1,000 | 0 ms  |
| Two Sum Sorted | 1,000 | 0 ms  |
| Prefix Sum Calculation | 1,000 | 0 ms  |

### **List Size: 10,000 Elements**

| Algorithm | List Size | Time (ms) |
| --- | --- | --- |
| Bubble Sort | 10,000 | 938 ms  |
| Insertion Sort | 10,000 | 258 ms  |
| Selection Sort | 10,000 | 412 ms  |
| Gnome Sort | 10,000 | 559 ms  |
| Odd-Even Sort | 10,000 | 631 ms  |
| Pancake Sort | 10,000 | 645 ms  |
| Cycle Sort | 10,000 | 1312 ms  |
| Comb Sort | 10,000 | 5 ms  |

---


For complete results and instructions on how to run the benchmarks on your own machine, see the BENCHMARK.md file.

## Contributing

Contributions are welcome. We aim to build the most powerful algorithmic arsenal in the Dart ecosystem. Please open an issue on GitHub to discuss any changes or new features.

## License

This project is licensed under the MIT License - see the LICENSE file for details.