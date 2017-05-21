---
layout: page
title: Downloads
---

## Vessel segmentation

### Introduction

For several reasons, the segmentation of the vascular system is one of the most researched problems of retinal image analysis: on the one hand, it can be used for the detection of various other anatomical parts; on the other hand, the geometry of the vessels can be used to infer on various diseases, like hypertension. We have developed a novel technique for the accurate segmentation of the vasculature. The method is described in the paper {% cite j006 %}.

### Example

To have an impression on what the software does, see the following input and output images.

<table style="width:40%">
<thead>
<tr>
<th style="width:20%">Input</th>
<th style="width:20%">Output</th>
</tr>
</thead>
<tbody>
<tr>
<td><img src="{{site.url}}/images/vessel/03_test.png"></td>
<td><img src="{{site.url}}/images/vessel/03-release-inv.png"></td>
</tr>
</tbody>
</table>

### Files

The implementation of the method described in {% cite j006 %} is available in binary format compiled for Ubuntu 17.04 AMD64. The usage of the software is included in the README files:

* Ubuntu 17.04 AMD64: [vessel-2017.05.10-Linux.deb]({{site.url}}/downloads/vessel-2017.05.10-Linux.deb)
* Ubuntu 17.04 AMD64: [vessel-2017.05.10-Linux.tar.gz]({{site.url}}/downloads/vessel-2017.05.10-Linux.tar.gz)

### References

{% bibliography --cited %}

----

## Sample codes for books on parallel and OpenCL programming

Sample codes for the books {% cite b0 %}, {% cite b1 %}, {% cite b2 %} are available below:

* Párhuzamos programozási eszközök és összetett alkalmazásaik [Parallel programming and its complex applications]: [combined-sample-codes.tar.gz]({{site.url}}/downloads/combined-sample-codes.tar.gz)
* OpenCL: [opencl-sample-codes.tar.gz]({{site.url}}/downloads/opencl-sample-codes.tar.gz)

### References

{% bibliography --cited %}

