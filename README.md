# cpu-benchmarking-project
The CPU Benchmark Tool is a simple Python application that measures CPU performance using a mathematical workload. The application runs a computationally intensive task and provides a benchmark score based on execution time. The tool is implemented using Tkinter for the graphical user interface (GUI).

Features

Set the number of iterations for the benchmark (20-200).

Measures the time taken to execute the benchmark in milliseconds.

Calculates a performance score based on execution time.

Displays results in a user-friendly GUI.

Implements input validation to ensure valid iteration values.

Uses multithreading to keep the UI responsive during benchmarking.

Installation

Prerequisites

Ensure that you have Python installed on your system.

Required Libraries

This project requires the Tkinter module, which is included in standard Python installations.

Usage

Run the application by executing:

python cpu_benchmark.py

Enter the desired number of iterations (between 20 and 200).

Click the Run Benchmark button.

View the performance score and execution time.

How It Works

The benchmark involves computing the square root of numbers in a loop to stress the CPU.

Execution time is measured and converted to milliseconds.

A score is calculated based on execution time (lower time results in a higher score).

Code Structure

CPUBenchmarkApp Class: Manages the GUI and benchmark execution.

create_widgets(): Sets up UI components.

validate_iterations(): Ensures valid user input for iterations.

run_benchmark(): Starts the benchmark in a separate thread.

benchmark_task(): Executes the mathematical workload and computes results.

main(): Initializes the application.

Contributing

Feel free to contribute to the project by improving performance calculations, adding new features, or enhancing the UI.
