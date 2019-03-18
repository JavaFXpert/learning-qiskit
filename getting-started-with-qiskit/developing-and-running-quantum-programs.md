# Developing and running quantum programs

The Qiskit framework leverages Python, and one way to run Python programs is to use Jupyter notebooks. This _Learning Qiskit_ guide contains many such notebooks, which may be run in the cloud or downloaded and run locally. 

* **To run in Google Colaboratory \(in the cloud\):** Ensure that you have a Google account, and are using a Chromium-based browser such as Chrome or Brave. If there is a link presented to open a notebook in Google Colaboratory, or this icon![](../.gitbook/assets/open-in-colab.png)appears at the top of the notebook itself, click it. If not, then open [Google Colaboratory](https://colab.research.google.com) and use its **File** \| **Open notebook** menu followed by the **GitHub** tab, paste the GitHub URL of the desired notebook, and click the search icon.
  * **Note:** Inserting `!pip install qiskit` in the first cell of a notebook \(or uncommenting if it is already there\) installs Qiskit into the user's Colaboratory environment for that notebook, so there is a bit of a delay and lots of output during this process.
* **To run locally:** Install the Qiskit foundational libraries in a Python environment using the instructions on the [Qiskit Terra site](https://qiskit.org/terra). Clone or download the desired notebooks, running them as a Jupyter notebook.

