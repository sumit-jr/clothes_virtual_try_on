# 👗 Clothes Virtual Try-On

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sumit-jr/clothes_virtual_try_on/blob/main/setup_gradio.ipynb)

A deep learning–based virtual try-on system that allows users to upload images and visualize how different clothes fit them.  
This project leverages **OpenPose, U²-Net, ResNet-101**, and a **Geometric Matching Module (GMM)** to provide realistic 2D garment fitting without requiring complex 3D modeling.

This work is based on the published IEEE paper:  
📄 *Advancement in Virtual Fitting Rooms: Integrating AI for Enhanced Online Shopping Experiences*  
(*15th ICCCNT, IEEE, November 2024*)  

---

## 📑 Table of Contents
- [Demo](#-demo)
- [Block Diagram](#-block-diagram)
- [Methodology](#-methodology)
- [Usage](#-usage)
- [Research Publication](#-research-publication)
- [Citation](#-citation)
- [License](#-license)
- [Author](#-author)

---

## 🎥 Demo

https://github.com/sumit-jr/clothes_virtual_try_on/assets/81641001/a9848479-cc53-42f8-8ac1-fec3f566af89

---

## 📊 Block Diagram

![Block Diagram](https://github.com/sumit-jr/clothes_virtual_try_on/assets/81641001/c28869dd-2c8a-4ece-b71f-21e50a2fed59)

---

## 🔬 Methodology

![Methodology Diagram](https://github.com/sumit-jr/clothes_virtual_try_on/assets/81641001/1d962cef-4457-4f7d-8bca-d42d6a21601d)

---

## 🚀 Usage

- Click the **"Open in Colab"** button at the top of this README.  
- Run the notebook `setup_gradio.ipynb` to launch the demo using **Gradio**.  
- Alternatively, run locally:

```bash
# Clone repository
git clone https://github.com/sumit-jr/clothes_virtual_try_on.git
cd clothes_virtual_try_on

# Install dependencies
pip install -r requirements.txt

# Run demo
python run.py
```
## 📰 Research Publication

- **Title:** Advancement in Virtual Fitting Rooms: Integrating AI for Enhanced Online Shopping Experiences  
- **Conference:** 15th International Conference on Computing, Communication and Networking Technologies (ICCCNT 2024)  
- **Publisher:** IEEE  
- **Date of Conference:** November 2024  
- **DOI:** [10.1109/ICCCNT61001.2024.10724276](https://doi.org/10.1109/ICCCNT61001.2024.10724276)  

---

## 📖 Citation

If you use this work in your research, please cite:

```bibtex
@INPROCEEDINGS{10724276,
  author={Sah, Sumit Prasad and Khadka, Roshan and Nayak, Soumili and Pati, Subhashree and Mishra, Monalisa},
  booktitle={2024 15th International Conference on Computing, Communication and Networking Technologies (ICCCNT)}, 
  title={Advancement in Virtual Fitting Rooms: Integrating AI for Enhanced Online Shopping Experiences}, 
  year={2024},
  pages={1-6},
  publisher={IEEE},
  doi={10.1109/ICCCNT61001.2024.10724276},
  address={Odisha, India}
}
```

## 📜 License

This project is licensed under the **MIT License**.
