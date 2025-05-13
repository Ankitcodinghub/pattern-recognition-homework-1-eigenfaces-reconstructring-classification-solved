# pattern-recognition-homework-1-eigenfaces-reconstructring-classification-solved
**TO GET THIS SOLUTION VISIT:** [Pattern-Recognition Homework 1-Eigenfaces Reconstructring Classification Solved](https://www.ankitcodinghub.com/product/pattern-recognition-homework-1-eigenfaces-reconstructring-classification-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93927&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Pattern-Recognition Homework 1-Eigenfaces Reconstructring Classification Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1 Face Recognition System

In this project, you will implement a face recognition system using the Prin- cipal Component Analysis (PCA) algorithm. Automatic face recognition sys- tems try to find the identity of a given face image according to their memory. The memory of a face recognizer is generally simulated by a training set. In this project, our training set consists of the features extracted from known face images of different persons. Thus, the task of the face recognizer is to find the most similar feature vector among the training set to the feature vector of a given test image. Here, we want to recognize the identity of a person where an image of that person (test image) is given to the system. You will use PCA as a feature extraction algorithm in this project.

In the training phase, you should extract feature vectors for each image in the training set. Let ΩA be a training image of person A which has a pixel resolution of M £ N (M rows, N columns). In order to extract PCA features of ΩA, you will first convert the image into a pixel vector ¡A by concatenating each of the M rows into a single vector. The length (or, dimensionality) of the vector ¡A will be M £N. In this project, you will use the PCA algorithm as a dimensionality reduction technique which transforms the vector ¡A to a vector !A which has a dimensionality d where d ø M £ N . For each training image Ωi, you should calculate and store these feature vectors !i.

In the recognition phase (or, testing phase), you will be given a test image Ωj of a known person. Let Æj be the identity (name) of this person. As in the training phase, you should compute the feature vector of this person using PCA and obtain !j. In order to identify Ωj, you should compute the similarities between !j and all of the feature vectors !i’s in the training set. The similarity between feature vectors can be computed using Euclidean distance. The identity of the most similar !i will be the output of our face recognizer. If i = j, it means that we have correctly identified the person j, otherwise if i 6= j, it means that we have misclassified the person j. Schematic diagram of the face recognition system that will be implemented is shown in Figure 1.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Fig. 1. Schematic diagram of a face recognizer.

2 How to use PCA?

In this section, the use of PCA as a feature extractor is explained. Assume that we have p training images: Ωi,i = 1,2,…,p. For each training image, you should form pixel vectors ¡i where ¡i 2 &lt;k,(k = M £N). Our aim is to compute feature vectors !i where !i 2 &lt;d,(d ø k). In order to apply PCA to the training set, you should first form a training data matrix A which contains p rows: at each row ¡i’s are stored. Thus the dimensionality of A is p £ k. First, you should compute the covariance matrix of A: CA. Then the eigenvalues and their corresponding eigenvectors of CA should be computed. There will be k eigenvalue and eigenvector pairs where each eigenvector ei is of dimensionality k. Sort the eigenvalues in decreasing order, and select the biggest d eigenvalue and eigenvector pairs. Form the transformation matrix Ψ by simply putting the selected eigenvectors as columns of Ψ. You will use Ψ to compute !i’s from ¡i’s. The computation of !i is simply by:

! i = Ψ T ¡ Ti ( 1 )

where ΨT and ¡Ti are the transposes of Ψ and ¡i, respectively. Note that each column of Ψ corresponds to an eigenvector which is of length k. This is equal to M £ N which is the dimensionality (resolution) of input images. Thus, you can convert each eigenvector to an image by reversing the concatenation operation. These converted eigenvector images are called eigenfaces since they are similar to human faces. Figure 2 shows 20 eigenfaces that correspond to

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
the largest 20 eigenvalues of the ORL face database.

</div>
</div>
<div class="layoutArea">
<div class="column">
Fig. 2. First 20 eigenfaces of the ORL face database

Once you obtain !i’s using the largest d eigenvectors, you can reconstruct the image of person i. If you use all k eigenvectors instead of d when forming Ψ, the reconstructed image will the same as image Ωi. However, since our aim is dimensionality reduction and d ø k, reconstructed image Ωˆi will be an approximation of the actual Ωi. You can reconstruct Ωˆi by converting the pixel vector: ¡ˆi = (Ψ!i)T to an image of resolution M £N. Figure 3 shows the reconstructed images of two persons using different number of eigenvectors. Notice that if you use more eigenvectors, then the reconstructed image is more similar to the original face image.

3 Implementation Details

In this project, you will use the ORL face database which contains 10 different images of each of the 40 subjects. For each subject five images (instances) will be put into training set, and the rest of the images will be put into the test set. Training and test set images will be under \train_images and \test_images directories, respectively. A sample MATLAB code will be provided to you which

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Fig. 3. PCA reconstructions of the two subjects. Starting from the first row, the most important 5, 10, 100, 150, 700, and 1584 eigenvectors are used to reconstruct a face image. The resolution of the original face images is 44 £ 36 = 1584.

automatically reads the images under these directories. The pseudo-code of the sample MATLAB code is as follows:

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
<pre>---------------------------------------------------------------
1. Set image resolution parameter (im_res)
2. Set PCA dimensionality parameter (PCA_DIM)
</pre>
<pre>3. Read training images
4. Form training data matrix (M_train_data)
5. Form training class labels matrix (M_train_labels)
</pre>
<pre>6. Calculate PCA transformation matrix (tmatrix)
7. Calculate feature vectors of all training images using tmatrix
8. Store training feature vectors in a matrix
</pre>
<pre>9. Read test faces
10. For each test face do
</pre>
<ol start="11">
<li>
<pre>11. &nbsp;   Calculate the feature vector of a test face using tmatrix
</pre>
</li>
<li>
<pre>12. &nbsp;   Compute the distances between test feature vector and
</pre>
<pre>       all training vectors
</pre>
</li>
</ol>
<pre>14.    Store the distances together with the training class labels
</pre>
<pre>15. Initialize error count to zero.
16. For each test face do
</pre>
<ol start="17">
<li>
<pre>17. &nbsp;   Using the distance data, determine the person ID of the
</pre>
<pre>       most similar training vector
</pre>
</li>
<li>
<pre>18. &nbsp;   If the found ID is not equal to the ID of the test image
</pre>
<pre>       increment error count
</pre>
</li>
</ol>
<pre>19. Output the correct recognition accuracy :
   (1 - (error count/ total test image count))*100
</pre>
<pre>---------------------------------------------------------------
</pre>
4 What to submit?

You should submit a report containing the followings:

<ol>
<li>(1) &nbsp;Eigenfaces: In your report, show the first 10 eigenfaces that you have found.</li>
<li>(2) &nbsp;Reconstructed Faces : Reconstruct the face of one subject using different number of eigenvectors. Show that increasing the amount of eigenvectors used, also increases the quality of the reconstructed face image.</li>
<li>(3) &nbsp;Recognition Accuracy Plots : Plot a recognition accuracy versus PCA dimensionality graph. See Figure 4 as an example.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>100
 90
 80
 70
 60
 50
 40
 30
 20
 10
  0
</pre>
</div>
<div class="column">
10 20 30 40 50 60 70 80 90 100

PCA dimensionality

Fig. 4. Recognition accuracy plot

</div>
</div>
<div class="layoutArea">
<div class="column">
5 MATLAB Help

</div>
</div>
<div class="layoutArea">
<div class="column">
Recognition Accuracies for different PCA dimensionalities

</div>
</div>
<div class="layoutArea">
<div class="column">
(1) To read and resize *.bmp files, you need to install Matlab – Image Processing Toolbox. Specifically, you may use imread, imresize, and imwrite functions.

<ol start="2">
<li>(2) &nbsp;You can use eig and cov commands to calculate eigenvectors and covari- ance matrices, respectively. The use of any other PCA-related MATLAB functions is strictly forbidden.</li>
<li>(3) &nbsp;Contact Berk G ̈okberk (gokberk@boun.edu.tr) if you need any assistance.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
</div>
