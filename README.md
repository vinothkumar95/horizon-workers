# Horizon CPU Processing Calculator

![Horizon CPU Processing Calculator](https://img.shields.io/badge/Horizon-CPU%20Calculator-blue)
![Version](https://img.shields.io/badge/version-1.0.0-green)
![License](https://img.shields.io/badge/license-MIT-orange)

A web-based interactive tool for calculating and visualizing CPU processing performance with multiple workers. This calculator helps you understand the relationship between CPU cores, worker processes, and API rate limits to optimize your processing workflows.

## 🌐 Live Demo

Access the live demo at: [Horizon CPU Calculator](https://vinothkumar95.github.io/horizon-workers/horizon_cpu_calculator.html)

## 📋 Features

- **Interactive Configuration Panel**: Set total records, processing time, API rate limits, and worker count
- **CPU Architecture Visualization**: Visual representation of CPU cores and their utilization
- **Real-time Simulation**: Watch workers process records in a simulated environment
- **Performance Metrics**: View key metrics like processing time, throughput, and speedup factor
- **Smart Optimization Tips**: Get intelligent suggestions to improve your processing efficiency
- **Responsive Design**: Works on desktop and mobile devices

## 🧮 Key Calculations

The calculator provides insights on:

- **Processing Time**: Total time required to process all records with parallel workers
- **Throughput**: Records processed per second
- **Speedup Factor**: Performance improvement compared to sequential processing
- **CPU Efficiency**: How effectively your configuration utilizes available CPU cores
- **Bottleneck Analysis**: Identifies whether workers or API rate limits are the bottleneck

## 🔍 Understanding Workers vs. Cores

This tool helps clarify common misconceptions about workers and CPU cores:

- **CPU-bound tasks**: Optimal worker count equals available CPU cores
- **I/O-bound tasks**: Worker count can exceed CPU cores (typically 2x cores)
- **Mixed workloads**: Start with 2x cores and tune based on performance metrics

## 🚀 Usage Guide

1. Set the **Total Records** to process
2. Adjust the **Processing Time per Record** range
3. Configure the **API Rate Limit** (requests per second)
4. Set the **Number of Horizon Workers** to utilize
5. Specify available **CPU Cores** for your system
6. Click **Calculate & Simulate** to see the results
7. Review the metrics and optimization tips

## 💻 Technical Implementation

The calculator is built using:

- **HTML5**: Structure and content
- **CSS3**: Styling with modern features like flexbox, grid, and animations
- **JavaScript**: Dynamic calculations and interactive simulations
- **Responsive Design**: Adapts to different screen sizes

No external libraries or frameworks are required - it's a pure vanilla JavaScript implementation.

## 🔧 Local Development

To run this project locally:

1. Clone the repository:
   ```
   git clone https://github.com/vinothkumar95/horizon-workers.git
   ```

2. Navigate to the project directory:
   ```
   cd horizon-workers
   ```

3. Open `horizon_cpu_calculator.html` in your web browser

## 📚 Educational Value

This tool serves as an educational resource to understand:

- Parallel processing concepts
- CPU core utilization
- Worker allocation strategies
- API rate limiting effects
- Performance optimization techniques

## 📝 License

This project is available under the MIT License.

## 👨‍💻 Author

Created by [Vinoth Kumar](https://github.com/vinothkumar95)