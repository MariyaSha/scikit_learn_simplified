# scikit_learn_simplified
simple machine learning coding workflows with scikit-learn
<br>
<br>
<img src="https://github.com/user-attachments/assets/a8222d95-a9c1-459e-8233-e8693768fdfa" style="width:600px;" alt="Simple Machine Learning with Sklearn Cover">

## 🔍 Instructions 🔍
The repo includes several workflows designed for running Sklearn both on CPU, and on GPU with NVIDIA cuML.

### 🌄 CPU Workflow Instructions 🌄
1. Please use a WSL terminal with Anaconda installed, and enter the following commands:
```
conda create -n ml_env python=3.12
conda activate ml_env
pip install scikit-learn
pip install jupyter
```
2. Clone the scikit_learn_simplified Repository to your computer:
```
git clone https://github.com/MariyaSha/scikit_learn_simplified.git
```
3. Run Jupyter Notebook:
```
cd scikit_learn_simplified
jupyter lab
```
4. Type in your browser:
```
localhost:8888
```
5. Open Notebook: `ml_with_california_housing.ipynb`

### 🌅 GPU Environment Workflow Instructions 🌅
1. Please use a WSL terminal with Anaconda installed, as described in the RAPIDS Installation Guide: https://docs.rapids.ai/install
2. Make sure your GPU driver is up to date and make a note of the CUDA version you have, shown by:
```
nvidia-smi
```
3. Pick your version of CUDA in the RAPIDS Instalation Guide, and "Choose a Specific Pakcage" of cuML (and jupyter). The resulting generated command should look similar to this:
```
conda create -n cuml_env -c rapidsai -c conda-forge -c nvidia  \
    cuml=25.04 python=3.12 'cuda-version>=12.0,<=12.8' \
    jupyterlab
```
4. Activate newly created environment, and install Scikit-Learn in it:
```
activate cuml_env
pip install scikit-learn
```
5. Clone the scikit_learn_simplified Repository to your computer (if you haven't done that already):
```
git clone https://github.com/MariyaSha/scikit_learn_simplified.git
```
6. Run Jupyter Notebook:
```
cd scikit_learn_simplified
jupyter lab
```
7. Navigate to speedtest/YOUR_SYSTEM/GPU_CPU_Speedtest.ipynb and follow the instructions within the notebook to perform a speedtest on your hardware.
8. Once you obtain the results of your speedtest, you can visualize them in speedtest/speedtest_results_analysis.ipynb.

### 🧠 Workflow Options 🧠
- **Simple Scikit-Learn Machine Learning Code Demo for Beginners**: ml_with_california_housing.ipynb
- **CPU vs GPU Speed Test for Scikit-Learn**: speedtest/YOUR_SYSTEM/GPU_CPU_Speedtest.ipynb
- **CPU vs GPU Speed Test Results Analysis**: speedtest/speedtest_results_analysis.ipynb

## 📺 Video Tutorials 📺
This repository is designed to support the following YouTube tutorials:
<br>
<br>
<a href="https://youtu.be/-IvNzmrcyUM">
<img src="https://github.com/user-attachments/assets/a8222d95-a9c1-459e-8233-e8693768fdfa" style="width:300px;" alt="Simple Machine Learning with Sklearn Thumbnail">
</a>
<a href="">
<img src="https://github.com/user-attachments/assets/a799694f-b6bd-4c2f-853d-9ea26da0767a" style="width:300px;" alt="Simple Machine Learning with Sklearn Thumbnail">
</a>

## 📚 Further Learning 📚
If at any point, you find yourself stuck or wondering "what on Earth is she writing about??"
<br>
Please check out some of my video tutorials below for detailed explanations:

- What's "features", "samples", and "targets"? Detailed explanation with real-life examples:
   <br>
   ⭐ Machine Learning FOR BEGINNERS - Supervised, Unsupervised and Reinforcement Learning:
   <br>
       https://youtu.be/mMc_PIemSnU
- What's Linear Regression?
  <br>
  ⭐ Linear Regression Algorithm with Code Examples:
  <br>
      https://youtu.be/MkLBNUMc26Y

## 🤝 Connect with me 🤝
<b>📎 YouTube</b>
<br>
     https://youtube.com/@pythonsimplified
<br>
<b>📎 Discord</b>
<br>
     https://discord.com/invite/wgTTmsWmXA
<br>
<b>📎 LinkedIn</b>
<br>
     https://ca.linkedin.com/in/mariyasha888
<br>
<b>📎 X</b>
<br>
     https://x.com/mariyasha888
<br>
<b>📎 Blog</b>
<br>
     https://www.pythonsimplified.org

