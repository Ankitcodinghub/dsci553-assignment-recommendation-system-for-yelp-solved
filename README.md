# dsci553-assignment-recommendation-system-for-yelp-solved
**TO GET THIS SOLUTION VISIT:** [DSCI553 Assignment Recommendation System-for-Yelp Solved](https://www.ankitcodinghub.com/product/dsci553-assignment-recommendation-system-for-yelp-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92306&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DSCI553 Assignment Recommendation System-for-Yelp Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. Overview of the Assignment

In Assignment 3, you will complete three tasks. You will first implement Min-Hash and Locality Sensitive Hashing (LSH) to find similar businesses efficiently. Then you will implement various types of recommendation systems.

2. Requirements

2.1 Programming Requirements

<ol>
<li>You must use Python &amp; Spark to implement all tasks. You can only use the standard Python libraries (i.e., external libraries like numpy or pandas are not allowed).</li>
<li>You are required to only use Spark RDD, i.e. no point if using Spark DataFrame or DataSet.</li>
<li>There will be 10% bonus for Scala implementation in each task. You can get the bonus only when bothPython and Scala implementations are correct.</li>
</ol>
2.2 Programming Environment

Python 3.6, Scala 2.11, and Spark 2.3.0

We will use Vocareum to automatically run and grade your submission. You must test your scripts on your

local machine and the Vocareum terminal before submission.

2.3 Write your own code

Do not share code with other students!!

For this assignment to be an effective learning experience, you must write your own code! We emphasize this point because you may find Python implementations of some of the required functions on the Web. Please do not look for or at any such code!

Plagiarism detection will combine all the code we can find from the Web (e.g., Github) as well as other students’ code from this and other (previous) sections. We will report all detected plagiarism to the university.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3. Yelp Data

For this assignment, we have generated sample review data from the original Yelp review dataset using some filters, such as the condition: “state” == “CA”. We randomly took 80% of sampled reviews for training, 10% for testing, and 10% as the blind dataset. (We do not share the blind dataset.) You can access

</div>
</div>
<div class="layoutArea">
<div class="column">
and download the following JSON files either under the directory on the resource/asnlib/publicdata/ or on Google Drive (USC email only):

<ol>
<li>train_review.json</li>
<li>test_review.json – containing only the target user and business pairs for prediction tasks</li>
<li>test_review_ratings.json – containing the ground truth rating for the testing pairs</li>
<li>user_avg.json – containing the average stars for the users in the train dataset</li>
<li>business_avg.json – containing the average stars for the businesses in the train dataset</li>
<li>stopwords</li>
<li>We do not share the blind dataset.</li>
</ol>
4. Tasks

You need to submit the following files on Vocareum: (all in lowercase)

<ol>
<li>Python scripts: task1.py, task2train.py, task2predict.py, task3train.py, task3predict.py</li>
<li>Model files: task2.model, task3item.model, task3user.model</li>
<li>Result files: task1.res, task2.predict, task3item.predict, task3user.predict</li>
</ol>
</div>
<div class="column">
V ocareum:

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol start="4">
<li>Scala scripts: task1.scala, task2train.scala, task2predict.scala, task3train.scala, task3predict.scala; one jar package: hw3.jar</li>
<li>Model files: task2.scala.model, task3item.scala.model, task3user.scala.model</li>
<li>Result files: task1.scala.res, task2.scala.predict</li>
<li>[OPTIONAL] You can include other scripts to support your programs (e.g., callable functions).</li>
</ol>
4.1 Task1: Min-Hash + LSH (2pts)

4.1.1 Task description

In this task, you will implement the Min-Hash and Locality Sensitive Hashing algorithms with Jaccard similarity to find similar business pairs in the train_review.json file. We focus on 0/1 ratings rather than the actual rating values in the reviews. In other words, if a user has rated a business, the user’s contribution in the characteristic matrix is 1; otherwise, the contribution is 0 (Table 1). Your task is to identify business pairs whose Jaccard similarity is &gt;= 0.05.

Table 1: The left table shows the original ratings; the right table shows the converted 0 and 1 ratings.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
You can define any collection of hash functions to permutate the row entries of the characteristic matrix to generate Min-Hash signatures. Some potential hash functions are:

𝑓(𝑥) = (𝑎𝑥 + 𝑏) % 𝑚

𝑓(𝑥) = ,(𝑎𝑥 + 𝑏) % 𝑝. % 𝑚

where 𝑝 is any prime number; 𝑚 is the number of bins. You can define any combination for the parameters (𝑎, 𝑏, 𝑝, or 𝑚) in your implementation.

After you have defined all hash functions, you will build the signature matrix using Min-Hash. Then you will divide the matrix into 𝒃 bands with 𝒓 rows each, where 𝒃 × 𝒓 = 𝒏 (𝒏 is the number of hash functions). You need to set 𝒃 and 𝒓 properly to balance the number of candidates and the computational cost. Two businesses become a candidate pair if their signatures are identical in at least one band.

Lastly, you need to verify the candidate pairs using their original Jaccard similarity. Table 1 shows an example of calculating the Jaccard similarity between two businesses. Your final outputs will be the business pairs whose Jaccard similarity is &gt;= 0.05.

business2 0 1 0 0

Table 2: Jaccard similarity (business1, business2) = #intersection / #union = 1/3

4.1.2 Execution commands

Python $ spark-submit task1.py &lt;input_file&gt; &lt;output_file&gt;

Scala $ spark-submit –class task1 hw3.jar &lt;input_file&gt; &lt;output_file&gt;

&lt;input_file&gt;: the train review set

&lt;output_file&gt;: the similar business pairs and their similarities

4.1.3 Output format

You must write a business pair and its similarity in the JSON format using exactly the same tags like the example in Figure 1. Each line represents a business pair, e.g., “b1” and “b2”. For each business pair “b1” and “b2”, you do not need to generate the output for “b2” and “b1” since the similarity value is the same as “b1” and “b2”. You do not need to truncate decimals for the ‘sim’ values.

Figure 1: An example output for Task 1 in the JSON format

4.1.4 Grading

Your task 1 outputs (1pt) will be graded by precision and recall metrics defined below.

Precision = # true positives / # output pairs, Recall = # true positives / # ground truth pairs

Your precision should be &gt;= 0.95 (0.5pt), and recall should be &gt;= 0.5 (0.5pt). The execution time on Vocareum should be less than 200 seconds. To evaluate the implementation, you can generate the ground

</div>
</div>
<table>
<tbody>
<tr>
<td colspan="4" rowspan="1">
<div class="layoutArea">
<div class="column">
user1 user2 user3 user4

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
business1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
01

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
truth that contains all the business pairs in the train_review.json file whose Jaccard similarity is &gt;=0.05 and calculate precision and recall by yourself.

4.2 Task2: Content-based Recommendation System (2pts)

4.2.1 Task description

In this task, you will build a content-based recommendation system by generating profiles from review texts for users and businesses in the train_review.json file. Then you will use the model to predict if a user prefers to review a given business by computing the cosine similarity between the user and item profile vectors.

During the training process, you will construct the business and user profiles as follows:

<ol>
<li>Concatenating all reviews for a business as one document and parsing the document, such as removing the punctuations, numbers, and stopwords. Also, you can remove extremely rare words to reduce the vocabulary size. Rare words could be the ones whose frequency is less than 0.0001% of the total number of words.</li>
<li>Measuring word importance using TF-IDF, i.e., term frequency multiply inverse doc frequency</li>
<li>Using top 200 words with the highest TF-IDF scores to describe the document</li>
<li>Creating a Boolean vector with these significant words as the business profile</li>
<li>Creating a Boolean vector for representing the user profile by aggregating the profiles of the items that the user has reviewed</li>
</ol>
During the prediction process, you will estimate if a user would prefer to review a business by computing the cosine distance between the profile vectors. The (user, business) pair is valid if their cosine similarity is &gt;= 0.01. You should only output these valid pairs.

4.2.2 Execution commands Training commands:

Python $ spark-submit task2train.py &lt;train_file&gt; &lt;model_file&gt; &lt;stopwords&gt;

Scala $ spark-submit –class task2train hw3.jar &lt; train_file&gt; &lt;model_file&gt; &lt;stopwords&gt;

&lt;train_file&gt;: the train review set

&lt;model_file&gt;: the output model

&lt;stopwords&gt;: containing the stopwords that can be removed

Predicting commands:

Python $ spark-submit task2predict.py &lt;test_file&gt; &lt;model_file&gt; &lt;output_file&gt;

Scala $ spark-submit –class task2predict hw3.jar &lt;test_file&gt; &lt;model_file&gt; &lt;output_file&gt;

&lt;test_file&gt;: the test review set (only target pairs) &lt;model_file&gt;: the model generated during the training process &lt;output_file&gt;: the output results

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
4.2.3 Output format:

Model format: There is no strict format requirement for the content-based model.

Prediction format:

You must write the results in JSON format using exactly the same tags like the example in Figure 2. Each line represents a predicted pair of (“user_id”, “business_id”). You do not need to truncate decimals for ‘sim’ values.

Figure 2: An example prediction output for Task 2 in JSON format

4.2.4 Grading

You need to generate the content-based model and the prediction results (1pt). We will grade your prediction results by calculating precision and recall using the ground truth (i.e., the blind reviews). The definitions of precision and recall are the same as the ones in task 1. Your precision should be &gt;= 0.8 (0.5pt) and recall should be &gt;= 0.7 (0.5pt) for the blind datasets. The execution time of the training process on Vocareum should be less than 600 seconds. The execution time of the predicting process on Vocareum should be less than 300 seconds.

4.3 Task3: Collaborative Filtering Recommendation System (4pts)

4.3.1 Task description

In this task, you will build collaborative filtering (CF) recommendation systems using the train_review.json file. After building the systems, you will use the systems to predict the ratings for a user and business pair. You are required to implement 2 cases:

• Case 1: Item-based CF recommendation system (2pts)

During the training process, you will build a recommendation system by computing the Pearson correlation for the business pairs with at least three co-rated users. During the predicting process, you will use the system to predict the rating for a given pair of user and business. You must use at most N business neighbors who are the top N most similar to the target business for prediction (you can try various N, e.g., 3 or 5).

• Case 2: User-based CF recommendation system with Min-Hash LSH (2pts)

During the training process, you should combine the Min-Hash and LSH algorithms in your user-based CF recommendation system since the number of potential user pairs might be too large to compute. You need to (1) identify user pairs’ similarity using their co-rated businesses without considering their rating scores (similar to Task 1). This process reduces the number of user pairs you need to compare for the final Pearson correlation score. (2) compute the Pearson correlation for the user pair candidates with Jaccard similarity &gt;= 0.01 and at least three co-rated businesses. The predicting process is similar to Case 1.

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
4.3.2 Execution commands Training commands:

Python $ spark-submit task3train.py &lt;train_file&gt; &lt;model _file&gt; &lt;cf_type&gt;

Scala $ spark-submit –class task3train hw3.jar &lt; train_file&gt; &lt;model _file&gt; &lt;cf_type&gt;

&lt;train_file&gt;: the train review set

&lt;model_file&gt;: the output model

&lt;cf_type&gt;: either “item_based” or “user_based”

Predicting commands:

</div>
</div>
<div class="layoutArea">
<div class="column">
Python Scala

</div>
<div class="column">
$ spark-submit task3predict.py &lt;train_file&gt; &lt;test_file&gt; &lt;model_file&gt; &lt;output_file&gt; &lt;cf_type&gt;

$ spark-submit –class task3predict hw3.jar &lt;train_file&gt; &lt;test_file&gt; &lt;model_file&gt; &lt;output_file&gt; &lt;cf_type&gt;

&lt;train_file&gt;: the train review set

&lt;test_file&gt;: the test review set (only target pairs) &lt;model_file&gt;: the model generated during the training process &lt;output_file&gt;: the output results

&lt;cf_type&gt;: either “item_based” or “user_based”

</div>
</div>
<div class="layoutArea">
<div class="column">
4.3.3 Output format: Model format:

You must write the model in JSON format using exactly the same tags like the example in Figure 3. Each line represents a business pair (“b1”, “b2”) for the item-based model (Figure 3a) or a user pair (“u1”, “u2”) the for user-based model (Figure 3b). There is no need to have (“b2”, “b1”) or (“u2”, “u1”). You do not need to truncate decimals for ‘sim’ values.

(a)

(b)

Figure 3: (a) is an example of item-based model and (b) is an example of user-based model

Prediction format:

You must write a target pair and its prediction in the JSON format using exactly the same tags like the example in Figure 4. Each line represents a predicted pair of (“user_id”, “business_id”). You do not need to truncate decimals for ‘stars’ values.

Figure 4: An example output for task3 in JSON format

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
4.3.4 Grading

You need to generate the item-based and user-based CF models. We will grade your model using precision and recall defined in task 1. For your item-based model, precision should be &gt;= 0.9 (0.25pt) and recall should be &gt;=0.9 (0.25pt). For your user-based model should, precision should be &gt;= 0.4 (0.25pt) and recall should be &gt;=0.5 (0.25pt).

Besides, we will compare your prediction results against the ground truth in both test and blind datasets. You should output the predictions ONLY generated from the model. Then we use RMSE (Root Mean Squared Error) defined in the equation below to evaluate the performance. For those pairs that your model cannot predict (e.g., due to cold start problem or too few co-rated users), we will predict them with the business average stars for the item-based model and the user average stars for the user-based model. We provide two files contain the average stars for users and businesses in the training dataset, respectively. The value of “UNK” tag, which can be used for predicting those new businesses and users, is the average stars for the whole reviews.

𝑅𝑀𝑆𝐸 = 71 :(𝑃𝑟𝑒𝑑! − 𝑅𝑎𝑡𝑒! )” 𝑛!

Where 𝑃𝑟𝑒𝑑! is the prediction for business 𝑖 and 𝑅𝑎𝑡𝑒! is the true rating for business 𝑖. 𝑛 is the total number of the user and business.

The execution time of the training process on Vocareum should be less than 600 seconds. The execution time of the predicting process on Vocareum should be less than 100 seconds. RMSE for the item-based model in both test and blind datasets should be &lt;=0.91 (1.5pt), and for the user-based model in both datasets should be &lt;=1.01 (1.5pt). If the performance of only either one dataset reaches the threshold, you will obtain 1pt.

5. About Vocareum

<ol>
<li>You can use the provided datasets under the directory resource: /asnlib/publicdata/</li>
<li>You should upload the required files under your workspace: work/</li>
<li>You must test your scripts on both the local machine and the Vocareum terminal before submission.</li>
<li>During the submission period, the Vocareum will directly evaluate the following result files: task1.res, task2.predict, task3item.model, and task3user.model. The Vocareum will also run task3predict scripts and evaluate the prediction results for both test and blind datasets.</li>
<li>During the grading period, the Vocareum will run both train and predict scripts. If the training or predicting process fails to run, you can get 50% of the score only if the submission report shows that your submitted models or results are correct (regrading).</li>
<li>Here are the commands that you can use to run Python scripts on Vocareum:</li>
<li>You will receive a submission report after Vocareum finishes executing your scripts. The submission report should show precision and recall for each task. We do not test the Scala implementation during the submission period.</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
<ol start="8">
<li>Vocareum will automatically run both Python and Scala implementations during the grading period.</li>
<li>The total execution time of the submission period should be less than 600 seconds. The execution timeof grading period needs to be less than 3000 seconds.</li>
<li>Please start your assignment early! You can resubmit any script on Vocareum. We will only grade onyour last submission.</li>
</ol>
<ol>
<li></li>
</ol>
</div>
</div>
</div>
