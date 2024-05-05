# LLM lecture
* **[AI lecture](https://rkuo2000.github.io/AI-course/)**
* **[GenAI sample codes](https://github.com/rkuo2000/GenAI)**
* **[EdgeAI-MCU lecture](https://rkuo2000.github.io/EdgeAI-course/)**
* **[生成式AI導論 2024 - 李宏毅](https://www.youtube.com/playlist?list=PLJV_el3uVTsPz6CTopeRp2L2t4aL_KgiI)**
  
## 1. Introduction
### [AI 簡介](https://rkuo2000.github.io/AI-course/lecture/2023/12/01/AI-Brief.html)
### [Kaggle 使用介紹](https://rkuo2000.github.io/AI-course/lecture/2023/12/01/Kaggle-Intro.html)
### [Google Colab 教學](https://medium.com/python4u/google-colab-%E6%95%99%E5%AD%B8-1-python-%E9%9B%B2%E7%AB%AF%E9%96%8B%E7%99%BC%E7%92%B0%E5%A2%83%E5%AE%89%E8%A3%9D%E8%88%87%E5%BF%AB%E9%80%9F%E5%B0%8E%E8%A6%BD-78942200525f)

---
## 2. LLM

### [Large Language Models](https://rkuo2000.github.io/AI-course/lecture/2024/03/21/LLM.html) 

### [Prompt Engineering](https://rkuo2000.github.io/AI-course/lecture/2024/03/21/Prompt-Engineering.html)

### [LLM Example Codes](https://github.com/rkuo2000/GenAI/tree/main/Text-to-Text)

### LLM prompting
* `python LLM_prompting.py` (on PC with GPU)
* [colab_LLM_prompting.ipynb](https://github.com/rkuo2000/GenAI/blob/main/Text-to-Text/colab_LLM_prompting.ipynb) (on Colab T4)

### LLM Server & Client
* `python llm_server.py` (on PC with GPU)
* `python post_text.py`  (on PC with CPU)

### Colab's LLM Server & Client
* [colab_pyNgrok_LLM_server](https://github.com/rkuo2000/GenAI/blob/main/Text-to-Text/colab_pyNgrok_LLM_Server.ipynb) (on Colab T4)<br>
![](https://github.com/rkuo2000/GenAI/blob/main/assets/pyngrok_LLM_Server_fastapi.png?raw=true)
* [post-text client](https://github.com/rkuo2000/GenAI/blob/main/Text-to-Text/post_text.py) (on your PC)<br>
![](https://github.com/rkuo2000/GenAI/blob/main/assets/pyngrok_post_text.png?raw=true)

---
## 3. VLM / MLLM

### [Vision Language Models](https://rkuo2000.github.io/AI-course/lecture/2024/04/04/VLM.html)

### [VLM sample codes](https://github.com/rkuo2000/GenAI/tree/main/Image-to-Text)

### Running VLM server
* `python whisper_llava_server.py` (server)<br>
<p><img width="50%" height="50%" src="https://github.com/rkuo2000/GenAI/blob/main/Image-to-Text/images/Tainan_BeefSoup.jpg?raw=true"></p>
* `python post_imgau.py` (client)<br>
![](https://github.com/rkuo2000/GenAI/blob/main/assets/post_imgau.png?raw=true)

---
## 4. [EdgeAI-MCU](https://rkuo2000.github.io/EdgeAI-course/lecture/2024/03/01/Edge-AI-MCU-Capstone-Projects.html)

### Edge-AI Development Boards（開發板）
<table>
<tr><th> AMB82-mini </th><th> Kneron KL520</th><th> Jetson Orin NX </th><th> RK3399-pro </th></tr>
<tr>
<td><img src="https://www.amebaiot.com/wp-content/uploads/2023/03/amb82_mini.png"></td>
<td><img src="https://www.everfocus.com/upload/catalog_m/b098f7b0f63a26477cd2cb5d08eb12c0.png"></td>
<td><img src="https://gcs.rimg.com.tw/g4/265/d35/playrobot-inc/d/4b/6e/22325013064558_792.png"></td>
<td><img src="https://gcs.rimg.com.tw/g1/1/26/cb/22025731591883_229.jpg"></td>
</tr>
</table>

### AMB82-mini
`Audio recording & Video capturing + NN engine + WiFi & BLE/BT`<br>
![](https://www.amebaiot.com/wp-content/uploads/2023/03/amb82_mini.png)

---
## 5. [LLM FineTuning](https://rkuo2000.github.io/AI-course/lecture/2024/05/01/LLM-FineTuning.html)

---
## 6. [RAG](https://rkuo2000.github.io/AI-course/lecture/2024/05/04/RAG.html)

---
## 7. [AI Agents](https://rkuo2000.github.io/AI-course/lecture/2024/05/05/AI-Agents.html)
