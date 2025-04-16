
# Particle Swarm Optimization for Thermal Detection

## Overview
This project utilizes **Particle Swarm Optimization (PSO)** to optimize the parameters of thermal detection systems. The goal is to enhance the detection of thermal patterns, improving the accuracy of temperature-related measurements in various applications.

## Installation
To set up the project, follow these steps:

### Clone the Repository
```bash
git clone https://github.com/your-username/Particle-Swarm-Optimization-Thermal-Detection.git
```

### Install Dependencies
Ensure you have the necessary Python packages. You can install them via `pip` by running:
```bash
pip install -r requirements.txt
```

## Project Structure
The project is organized into the following main parts:

```
/Particle-Swarm-Optimization-Thermal-Detection
    |-- swarm.py                    # PSO algorithm implementation
    |-- utils.py                    # Helper functions
    |-- detection.py                # Thermal detection logic
    |-- model3.png                  # Sample thermal image used in detection
    |-- target3.png                 # Result image
    |-- requirements.txt            # Python dependencies file
    |-- README.md                   # Project documentation (this file)
    |-- .gitignore                  # Gitignore file for ignored files (e.g., venv, cache)
```

## Usage
1. **Run the Detection Script:**
   After setting up, run the thermal detection script:
   ```bash
   python detection.py
   ```

2. **Explanation of the Scripts:**
   - `swarm.py`: Implements the Particle Swarm Optimization (PSO) algorithm for parameter optimization.
   - `utils.py`: Contains helper functions used throughout the project.
   - `detection.py`: Main script for performing thermal detection and applying PSO.

## Example Output
The thermal detection will generate results based on the input images (`model3.png` and `target3.png`), optimizing the parameters to improve detection accuracy.

## Contributing
Feel free to fork the project and submit pull requests if you'd like to contribute to the codebase. Please open issues if you encounter bugs or have feature requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
