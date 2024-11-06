# Counterfactual-ultrasoundAI

![image](https://github.com/user-attachments/assets/02a086aa-d0e3-4e20-b554-7f83ad8d58f9)


**Overview of our framework.** **Grid Dropout (GD):** Dropout is applied to specific pixels in a grid-like fashion. **Center Dropout (CD):**
A large contiguous area is specified for pixel dropout. **Center Filter (CF):** After selecting the central region, basic mean filtering is applied.
**Random Shuffle (RS):** Regions are randomly selected for shuffling pixel combinations in blocks.

![image](https://github.com/user-attachments/assets/8510aedd-46d1-4f6b-9ab2-d64e2d9a70c3)

![image](https://github.com/user-attachments/assets/76fa9168-ac68-4f4c-9df1-95b257d43337)


**Details**
![image](https://github.com/user-attachments/assets/c444a4af-1c0f-4981-a302-a640b3376b38)


**Typical sample performance in our method ablation study.** **Original** is the direct output of the backbone network; **+SSL** adds self
supervised pre training; **+RS&GD** adds specific data augmentation based on **+SSL**.
![1-Result](https://github.com/inexhaustible419/Counterfactual-ultrasoundAI/assets/145007561/b4467053-a197-41e9-9830-e3e5839dbeca)


**Supported by the Open Fund of Science and Technology on Parallel and Distributed Processing Laboratory ( PDL )**
