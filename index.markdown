---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
Title: Home
---

![image](/assets/campus-logo.png){: style="float: left"}{: width="260" }  
# Dataset Condensation Benchmark
### Benchmark and library for accelerating DC research  


***

 
<br> 
<br>   





Dataset Condensation is a newly emerging technique aiming at learning a tiny dataset that captures the rich information encoded in the original dataset. As the size of datasets contemporary machine learning models rely on becomes increasingly large, condensation methods become a prominent direction for accelerating network training and reducing data storage. 

Despite numerous methods have been proposed in this rapidly growing field, evaluating and comparing different condensation methods is non-trivial and still remains an open issue. 
The quality of condensed dataset are often shadowed by many critical contributing factors to the end performance, such as data augmentation and model architectures. The lack of a systematic way to evaluate and compare condensation methods not only hinders our understanding of existing techniques, but also discourages practical usage of the synthesized datasets. 

This work provides the first large-scale standardized benchmark on Dataset Condensation. It consists of a suite of evaluations to comprehensively reflect the generability and effectiveness of condensation methods through the lens of their generated dataset. Leveraging this benchmark, we conduct a large-scale study of current condensation methods, and report many insightful findings that open up new possibilities for future development. The benchmark library, including evaluators, baseline methods, and generated datasets, is open-sourced 

|![](/assets/random.png) | ![](/assets/synthetic.png)|
|:--:|:--:|
|*Real images* | *Synthetic images* |


***

|![](/assets/database.png) | ![](/assets/speed.png) | ![](/assets/search.png)|
|:--:|:-------:|:--:|
|<span style="color:rgb(0, 139, 139);">**Comprehensive Datasets**</span>|<span style="color:rgb(0, 139, 139);">**Automated Eval Library**</span>|<span style="color:rgb(0, 139, 139);">**NAS**</span>|
Different datasets are provide ranging from medium to large to **better evaluate** the condensation methods| We provide a **fully auotmated** condensation methods performance evaluation library to set the standard benchmark and accelerate the research|We follow the **standard** Neural Architecture Search proceduare and provide the insights on using condensed dataset for model design|


![image](/assets/code.png)

***
<style>
    .profile {
        width: 100px;
        height: 100px;
        object-fit: cover;
        border-radius: 50%;
    }
    td, th {
   border: none!important;
}
</style>


|![image](/assets/justin.jpeg){: class="profile" style="float: left"} <br>Justin Cui | ![image](/assets/ruochen.jpeg){: class="profile" style="float: left"} <br>Ruochen Wang|
|||
|![image](/assets/sisi.jpeg){: class="profile" style="float: left"} <br>Si Si|![image](/assets/cho.jpeg){: class="profile" style="float: left"} <br>Cho-Jui Hsieh |