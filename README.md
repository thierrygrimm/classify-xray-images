<a name="readme-top"></a>

![Header](Images/XRay_Images.png "Header")


# Classification of X-Ray images with ensemble CNNs [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=EFQXNQ7UYXYKW&source=url)

<div align='left'>

[![](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white 'Jupyter')](http://jupyter.org)
[![](https://img.shields.io/badge/PyTorch-EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white 'Pytorch')](https://pytorch.org)
[![](https://img.shields.io/badge/FastAPI-009688.svg?style=for-the-badge&logo=FastAPI&logoColor=white 'FastAPI')](https://fastapi.tiangolo.com)
[![](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=NumPy&logoColor=white 'Numpy')](https://numpy.org)


</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#project-description">Project description</a>
    </li>
    <li>
      <a href="#files-and-data-description">Files and data description</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#requirements">Requirements</a></li>
      </ul>
    </li>
    <li>
      <a href="#issues">Issues</a>
      <ul>
        <li><a href="#troubleshooting">Troubleshooting</a></li>
        <li><a href="#filing-an-issue">Filing an issue</a></li>
      </ul>
    </li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## Project description

This project was part of a competition for by the SCQM Foundation (Swiss Clinical Quality Management in Rheumatic
Diseases) and won for best performance. The task was to classify X-Ray images into one of 11 distinct location sites (
classes) as the labels for these images had been lost. 

This machine learning solution has prevented having to manually and individually label more than 10'000 X-ray images
which has saved time and costs to the organization. Furthermore, the algorithm can be deployed continuously to perform 
annotation of new images, freeing up time for practitioners.

:star2: Highlights:

1. Codebase follows PEP8 coding style guidelines, ensuring clean, readable, and maintainable code.
2. Current state-of-the-art model in computer vision algorithms for smaller datasets.
3. Ensemble combines two architectures, leveraging their complementary strengths and making the classification more
   robust.


## Files and data description

**File structure:**

```
...
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Getting started

### Requirements

Make sure to install the dependencies:

~~~bash
python -m pip install -r requirements.txt
~~~


<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Issues
### Troubleshooting

...


### Filing an issue
Found a bug? Want more features? Find something missing in the documentation? Let me know! Please don't hesitate
to [file an issue](https://github.com/thierrygrimm/classify-xray-images/issues/new) and make a recommendation.

## Acknowledgments

* The original dataset was received from the SCQM Foundation (Swiss Clinical Quality Management in Rheumatic Diseases).
* For compliance to healthcare-specific privacy regulation the dataset will not be disclosed publicly.
* All published models and artifacts have been evaluated to prevent inadvertent disclosure of confidential information.

## License

```
Classification of X-Ray images - an ensemble CNN approach

The MIT License (MIT)

Copyright (c) 2023 Thierry Grimm

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software ("Classification of X-Ray images") and associated documentation 
files (the "Software"), to deal in the Software without restriction, including 
without limitation the rights to use, copy, modify, merge, publish, distribute, 
sublicense, and/or sell copies of the Software, and to permit persons to whom 
the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
