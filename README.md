# H&amp;E-Reading
**Multimodal algorithms for H&amp;E comprehension**

We developed an algorithm for classifying and segmenting H&E stained images and tested its capabilities on a simple breast cancer dataset. The algorithm incorporates textual content as an aid, showing commendable performance in the classification tasks. After achieving more precise classifications, the algorithm also excels in segmentation tasks. In the future, we will focus on incorporating more semantic information into the segmentation tasks. It is worth noting that more detailed textual content is not necessarily better; we have observed that providing only the core information in the text significantly enhances the classification tasks. As for how to define the core information in the text, we are still exploring this aspect. We completed the initial trial of this multimodal algorithm in January this year. 

Coincidentally, mahmoodlab is also experimenting with multimodal algorithms(**https://github.com/mahmoodlab/hest**). **Their algorithm achieves feature fusion through concatenation, while our algorithm employs a multi-head attention fusion mechanism to integrate features.**

![image](https://github.com/FZKChange/HE-Reading/assets/78149508/7cedb83c-8935-4500-9b01-78415f593390)



We perform classification identification on four subcategories of breast cancer, and the algorithm's classification performance is shown in the figure below. This is already a commendable result. Subsequently, we will improve the textual content quality and optimize the multimodal model to achieve better results.
![image](https://github.com/FZKChange/HE-Reading/assets/78149508/3361a7e4-cea3-4765-b507-08eb29d24ff1)
