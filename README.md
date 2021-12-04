<p align="center">
  <a href="https://revealjs.com">
  <img src="pictures/microscope18.png" alt="reveal.js" width="250">
  </a>
</p>

Welcome to this _hands-on_ session on Machine Learning for Whole Slide Images. The main resource of this course is a presentation based on the amazing [reveal.js](https://revealjs.com/) framework by [Hakim El Hattab](https://github.com/hakimel).

# Get started

## Slides
Support for this course is served on [github-pages](https://arnaudabreu.github.io/MasterSDSC/).

## Practical sessions

### Create and train a model
Here, you are asked to create a Keras Image classification model and fit this model on the tensorflow _colorectal_histology_ dataset.

- You will find the dataset and sample code [here](https://www.tensorflow.org/datasets/catalog/colorectal_histology)
- You will find an empty notebook with further instructions [here](https://colab.research.google.com/drive/1H3fmWiIToqgP40hZX8By9exZo0-xwTPP?usp=sharing)

### Test your model
For this part, you are going to test your model on a real Whole Slide Image!

- You can find a real Whole Slide Image [here](https://drive.google.com/file/d/1pxlDcaeVCpND7SyFyhjHm0cCuL3m7M7x/view?usp=sharing), please put it on your google drive.
- To handle the WSI (access pixel information) you will need to install several tools to split it in tiles. Put the [following cells](https://colab.research.google.com/drive/17KZrYffclSXQe0kLAiL7P1lk92ffZ-kJ?usp=sharing) at the beginning of your colab notebook.
- You will be using some code from the [MicroMedIAn/PathAIA](https://github.com/MicroMedIAn/PathAIA) library to store tiles and coordinates.

## Q&A
Please, feel free to ask your questions by [creating an issue](https://github.com/ArnaudAbreu/MasterSDSC/issues/new) on this repo. This way, everyone can read and learn from that ;-)
