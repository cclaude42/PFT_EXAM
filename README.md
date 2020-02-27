## Important

### SEE ALSO : **[PFT_2019](https://github.com/cclaude42/PFT_2019)** TO TEST YOUR FT_PRINTF.

This is an edit of ft_printf tester PFT made by **[Gavin Fielder](https://github.com/gavinfielder)** to fit with exam rules.
This PFT only includes the 208 test combinations of the exam flags (%sdx with precision and width).
Tests were added to cover stars and null pointers.

**Your printf doesn't need to pass all the tests, some cover undefined behaviour (but it's better if it does).**

Original PFT : https://github.com/gavinfielder/pft

This update was made by **[cclaude](https://github.com/cclaude42)**

## Installation
**In the root of your ft_printf repo**, run :

```
git clone https://github.com/gavinfielder/pft.git pft_exam && echo "pft_exam/" >> .gitignore && cd pft_exam && rm unit_tests.c && rm options-config.ini && git clone https://github.com/YulonSil/PFT_EXAM.git temp && cp temp/unit_tests.c . && cp temp/options-config.ini . && rm -rf temp
```

## Usage

**Warning : everytime you change your printf, you need to** ```make re``` **in PFT again.**

**In the PFT_EXAM repo**, run ```make re```

You can now run all the tests using ```./test``` 

To run only %s tests for example, you can use ```./test s```

To run tests #42 to #84, you can use ```./test 42 84```

## Credit
The code was written by [Gavin Fielder](https://github.com/gavinfielder). This is an update of the test file by [cclaude](https://github.com/cclaude42), with some tests removed and some added, for easier use with the 2019 printf subject.

Thanks to [lnezonde](https://github.com/leo125) and [macrespo](https://github.com/macrespo42) for their help debugging and their suggestions.
