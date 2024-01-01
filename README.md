<a name="readme-top"></a>

![GitHub contributors](https://img.shields.io/github/contributors/jbarciv/DrowsyDrive-Alert)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
<br />
<div align="center">
  
  <h3 align="center">DrowsyDrive-Alert</h3>

  <p align="center">
    A Drowsiness Driving Alert implementation with the use of MediaPipe
    <br />
    <a href="https://github.com/jbarciv/DrowsyDrive-Alert/tree/main/reports"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="#usage">View Demo</a>
    ·
    <a href="#installation">Installation</a>
    ·
    <a href="#contact">Contact</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


Blablabla about the project

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

List of major frameworks/libraries used for this project. 

* [![MediaPipe][mediapipe.png]][mediapipe-url]
* [![Jupyter Notebook][jupyter.png]][jupyter-url]
* [![Google Colab][colab.png]][colab-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

In order to reproduce the Drowsiness System Detection you can clone this repo:
```
git clone https://github.com/jbarciv/DrowsyDrive-Alert.git
```
or just download the [Notebook for the alarm system](src/DrowsyDrive-Alert.ipynb) along with the [MediaPipe face landmarker](src/face_landmarker_v2_with_blendshapes.task).

### Prerequisites

All the system has been develop on `Ubuntu 20.04`. Although it has not been tested, the following process should be practically the same for Windows except for minor details. We do not assure compatibility with Windows but we believe it is easily achievable.

We recommend to create a virtual environment in which to run the Notebook.
* **Create the venv**:
```
python3 -m venv myvenv
```
* **Activate your venv**:
```
source myvenv/bin/activate
```
we recommend you to create and *alias* in your `.bashrc` file: 
```
alias myvenv='source ~/the_path_to_venv_folder/myvenv/bin/activate'
```

### Installation
Only the `Jupyter Notebook` and some basic libraries are needed, you can install them easily in your `venv` using `pip`:
* **Install Jupyter Notebook**:
```
pip install notebook
```
* **Install the libraries**:
```
pip install opencv-python mediapipe
```

<!-- USAGE EXAMPLES -->
## Usage

With the use of MediaPipe we have implemented a *driving drowsiness detection system*. It relies only on visual perception from a camera (potencially the use of the front phone camera). The systems expects to have a close vision of the driver and a daylight conditions. The systems has not been tested with IR cameras for a robust light conditions.

[![Drowsiness Deteccion 1](./figs/1.gif)](https://preview.webflow.com/preview/drivers-d11799?utm_medium=preview_link&utm_source=designer&utm_content=drivers-d11799&preview=d27283e719e19a8e38ec335c9f8b4f5e&workflow=preview) [![Drowsiness Deteccion 1](./figs/2.gif)](https://preview.webflow.com/preview/drivers-d11799?utm_medium=preview_link&utm_source=designer&utm_content=drivers-d11799&preview=d27283e719e19a8e38ec335c9f8b4f5e&workflow=preview)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the BSD 3-Clause License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Ivonne Dayanna Quishpe Villagomez - [@yourtwietter](https://github.com/jbarciv) - username@gmail.com\
Juan Gustavo Maldonado Quispe - gustavo.maldonado@alumnos.upm.es\
Micaela Cabrera Guerrero - [@yourtwietter](https://github.com/jbarciv) - username@gmail.com\
Jorge Guijarro Tolon - [JTlotus](https://github.com/JTlotus) - jorgeguijarro10@gmail.com\
Josep Mª Barberá Civera - [jbarciv](https://github.com/jbarciv) - chemabc@gmail.com

Visit our project website for more info: [https://webflow.com/driving_drowsiness_detection](https://preview.webflow.com/preview/drivers-d11799?utm_medium=preview_link&utm_source=designer&utm_content=drivers-d11799&preview=d27283e719e19a8e38ec335c9f8b4f5e&workflow=preview)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Here we list resources we find helpful and would like to give credit to.

* [MediaPipe Face Landmark Detection](https://developers.google.com/mediapipe/solutions/vision/face_landmarker)
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[mediapipe.png]: https://miro.medium.com/v2/resize:fit:120/1*Hgg6bLceoIjubE2hBiJK4g.png
[mediapipe-url]: https://developers.google.com/mediapipe/solutions/vision/face_landmarker
[jupyter.png]: https://miro.medium.com/v2/resize:fit:120/format:webp/1*D95BB0ei7PVSu_51JhUY2w.png
[jupyter-url]: https://jupyter.org/
[colab.png]: https://cdn-images-1.medium.com/v2/resize:fit:140/1*sIcDb3d42i-AdsZJXL34kw@2x.png
[colab-url]: https://colab.google/
