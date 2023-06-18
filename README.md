# Diet Plan

This project provides a code for generating meal plans. It aims to create balanced diets based on the nutritional contents of various ingredients. The project repository can be found at: [https://github.com/baghyeonji/Diet_Plan.git](https://github.com/baghyeonji/Diet_Plan.git)

## Data

- The `data` folder contains a data file named `빠른준비.csv`.
- The `Code` folder contains the `Meal_Plan.ipynb` file.

## Code Explanation

- The project involves four datasets: `carbon_data` for ingredients with high carbohydrate content, `protein_data` for ingredients with high protein content, `dairy_data` for ingredients with high fat content, and `vege_data` for vegetable ingredients. All datasets consist of six columns: `'Ingredient', 'Calories', 'Carbohydrates', 'Protein', 'Fat', 'g'`.

- The meal plans are designed to meet approximately a 5:3:2 or 4:4:2 ratio of carbohydrates to protein to fat.

- The code performs the following actions:
  1. Retrieves a data entry from `carbon_data`.
  2. Retrieves a data entry from `protein_data`.
  3. Determines whether to include data from `dairy_data` or `vege_data`.
  4. If 'granola', 'cereal', or 'oatmeal' are present in `carbon_data`, it requires selecting one data entry from `dairy_data`.

## Usage

1. Clone the repository:git clone https://github.com/baghyeonji/Diet_Plan.git

2. Place the data file in the `data` folder.

3. Open the `Meal_Plan.ipynb` file in the `Code` folder.

4. Install any necessary packages and run the code.

## Contributing

If you would like to contribute to this project, you can participate in the following ways:

- Bug Reporting: Report any bugs by opening an issue.
- Feature Requests: Suggest new features to be added to the project.
- Code Contributions: Propose code for implementing new features or resolving issues.

For more details on contributing, please refer to [CONTRIBUTING.md](CONTRIBUTING.md).
