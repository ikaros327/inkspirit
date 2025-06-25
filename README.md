# InkSpirit
Datasets of expert-annotated  TCP(Triditional Chinese Painting) data including the Blank Space Standard and PostScript corpus.  
The pre-trained T2I model will be uploaded in the subsequent steps  
  

About InkSpirit：  
We proposes a Traditional Chinese Painting (TCP) generation system, InkSpirit.   
The key idea is to employ an expert knowledge-driven strategy to address the TCP problem. Specifically, a TCP dataset, an artistic conception-inscription corpus, and a generation framework based on ComfyUI workflow for precise element control have been developed. Extensive experiments have been conducted to demonstrate the effectiveness of the proposed system.

**We will improve the form of this open source project in the future. At present, we first provide the following data sets：**

# <font style="color:rgb(28, 31, 35);">1.Full-image paintings</font>
<font style="color:rgb(28, 31, 35);">From 1,834 annotated Song Dynasty TCPs, we selected the full-image paintings, excluding factors related to the mounting of calligraphy and paintings, and manually cropped the central part of the images.</font>

<font style="color:rgb(28, 31, 35);">Link: </font>[https://pan.baidu.com/s/1FD8kPpo_Tzkq2yWgc1vzsw](https://pan.baidu.com/s/1FD8kPpo_Tzkq2yWgc1vzsw)<font style="color:rgb(28, 31, 35);"> </font>

<font style="color:rgb(28, 31, 35);">Extract Code: 1q2w</font>

<font style="color:rgb(28, 31, 35);"></font>

# <font style="color:rgb(28, 31, 35);">2.Blank Space Statistics  </font>
<font style="color:rgb(28, 31, 35);">Using Inpainting Anything to complete the processing of the blank space regions in 957 TCP painting heart images.</font>

<font style="color:rgb(28, 31, 35);"> Write scripts to process and obtain the overall blank space ratio, cropped small image combinations, and local blank space ratio, and upload the corresponding dataset.</font>

<font style="color:rgb(28, 31, 35);">Contains the following data：</font>

1. <font style="color:rgb(28, 31, 35);">957 full TCP blank space images</font>
2. <font style="color:rgb(28, 31, 35);">Blank space region statistics of full TCP blank space images</font>
3. <font style="color:rgb(28, 31, 35);">Blank space images cut by the Rule of Thirds (Nine-grid)</font>
4. <font style="color:rgb(28, 31, 35);">Blank space region statistics of sub-blocks in Rule of Thirds blank space images</font>

<font style="color:rgb(28, 31, 35);">Link: </font>[https://pan.baidu.com/s/1FH1JL469Mxk5KSvPcUrJfw?pwd=1q2w](https://pan.baidu.com/s/1FH1JL469Mxk5KSvPcUrJfw?pwd=1q2w)<font style="color:rgb(28, 31, 35);"> </font>

<font style="color:rgb(28, 31, 35);">Extract Code: 1q2w</font>

<font style="color:rgb(28, 31, 35);"></font>

# <font style="color:rgb(28, 31, 35);"> 3.Inscription Corpus  </font>
PostScript data processing objectives and steps:

1. Screen the parts of the PostScript that contain poems.
2. Correlate the PostScript data with the Artistic conception dimension of TCP in the original annotation information.
3. Split the poems into characters and words to obtain a common PostScript character and word corpus based on Artistic conception.
4. Create a word cloud based on the corpus as a reference for generating poems in the T2I process.
5. Regarding the related words and associated words of the 24 Artistic conception vocabulary, and categorizing them by part of speech, saved as JSON format files.



Link: [https://pan.baidu.com/s/12Zq-_Rv1K5hoZCmmyP58WQ](https://pan.baidu.com/s/12Zq-_Rv1K5hoZCmmyP58WQ) 

<font style="color:rgb(28, 31, 35);">Extract Code: 1q2w</font>

<font style="color:rgb(28, 31, 35);"></font>

# 4.TCP T2I Training Set + Annotation Data + pre-trained models
1. English annotation files corresponding to all TCP images
2. all dimension categories - all corresponding images included under the specific annotation category.
3. cutting image with the same size.



**This part of data will be open source after sorting**

