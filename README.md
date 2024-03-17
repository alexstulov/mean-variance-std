# Mean-Variance-Standard Deviation Calculator
Calculate mean, variance, standard deviation, maximal, minimal and sum of values in 3 x 3 matrix using NumPy. Project from ["Data Analysis with Python" course from FCC](https://www.freecodecamp.org/learn/data-analysis-with-python/).

## How to use
To run sample code and tests start `main.py` with `python` console command:
```bash
python main.py
```

Provide list of nine digits for `calculate` function:
```python
calculate([0,1,2,3,4,5,6,7,8])
```
Output dictionary will look like this:
```python
{
  'mean': [axis1, axis2, flattened],
  'variance': [axis1, axis2, flattened],
  'standard deviation': [axis1, axis2, flattened],
  'max': [axis1, axis2, flattened],
  'min': [axis1, axis2, flattened],
  'sum': [axis1, axis2, flattened]
}

```
where `axis1` - mean/variance/etc. for columns as an array of length 3,
`axis0` - mean for rows as an array of length 3,
`flattened` - mean value for the input list as a whole.