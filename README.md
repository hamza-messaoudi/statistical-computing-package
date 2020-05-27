# staistical-computing-package

Note: This package was developped as classroom project.
A Python package that does basic operations for Gaussian and Binomial distributions.

## Installing the package 

Run the following command to install the package
```
  pip install statcomp 
```   

## Using the package

This package can be used to do basic computations on Gaussian and Binomial distibutions.

Example: 

```
  gaussian_one = Gaussian()
  gaussian_one.read_data_file('filepath.txt')
  
  gaussian_one.mean  # Calculates the mean of the distribution
  gaussian_one.stdev # Calculates the standard deviation of the distribution
  
  # Overriding the __add__ method 
  
  gaussian_one = Gaussian(5,7)
  gaussian_two = Gaussian(6,3)
  
  gaussian_sum = gaussian_one + gaussian_two  # Sums the means and standard deviations of the two distributions
 

```

## License
[MIT License.](https://opensource.org/licenses/MIT) 







