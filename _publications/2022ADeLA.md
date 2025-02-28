---
title: "ADeLA: Automatic Dense Labeling With Attention for Viewpoint Shift"
collection: publications
category: conferences
excerpt: 'Hanxiang Ren, Yanchao Yang, He Wang, Bokui Shen, Qingnan Fan, Youyi Zheng, C. Karen Liu, Leonidas J. Guibas.'
date: 2022-06-01
permalink: /publication/2022ADeLA
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2022/html/Ren_ADeLA_Automatic_Dense_Labeling_With_Attention_for_Viewpoint_Shift_in_CVPR_2022_paper.html'
# citation: 'Hanxiang Ren, Yanchao Yang, He Wang, Bokui Shen, Qingnan Fan, Youyi Zheng, C. Karen Liu, Leonidas J. Guibas. (2022). &quot;ADeLA: Automatic Dense Labeling With Attention for Viewpoint Shift.&quot; <i>Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)</i>. pp. 8079-8089.'
---

We describe a method to deal with performance drop in semantic segmentation caused by viewpoint changes within multi-camera systems, where temporally paired images are readily available, but the annotations may only be abundant for a few typical views. Existing methods alleviate performance drop via domain alignment in a shared space and assume that the mapping from the aligned space to the output is transferable. However, the novel content induced by viewpoint changes may nullify such a space for effective alignments, thus resulting in negative adaptation. Our method works without aligning any statistics of the images between the two domains. Instead, it utilizes a novel attention-based view transformation network trained only on color images to hallucinate the semantic images for the target. Despite the lack of supervision, the view transformation network can still generalize to semantic images thanks to the induced "information transport" bias. Furthermore, to resolve ambiguities in converting the semantic images to semantic labels, we treat the view transformation network as a functional representation of an unknown mapping implied by the color images and propose functional label hallucination to generate pseudo-labels with uncertainties in the target domains. Our method surpasses baselines built on state-of-the-art correspondence estimation and view synthesis methods. Moreover, it outperforms the state-of-the-art unsupervised domain adaptation methods that utilize self-training and adversarial domain alignments. Our code and dataset will be made publicly available.


The full paper can be accessed at the IEEE/CVF Open Access repository:
[ADeLA: Automatic Dense Labeling With Attention for Viewpoint Shift in CVPR 2022](https://openaccess.thecvf.com/content/CVPR2022/html/Ren_ADeLA_Automatic_Dense_Labeling_With_Attention_for_Viewpoint_Shift_in_CVPR_2022_paper.html)