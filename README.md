# cop-3530-programming-assignment--3-simplified-page-rank-algorithm
**TO GET THIS SOLUTION VISIT:** [COP 3530 Programming Assignment -3: Simplified Page Rank Algorithm](https://www.ankitcodinghub.com/product/cop-3530-programming-assignment-3-simplified-page-rank-algorithm/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;12847&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP 3530 Programming Assignment -3: Simplified Page Rank Algorithm&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (2 votes)    </div>
    </div>
In late 90’s as the number of webpages on the internet were growing exponentially different search engines were trying different approaches to rank the webpages.&nbsp; At Stanford, two computer science PhD students, Sergey Brin and Larry Page were working on the following questions: How can we trust information? Why are some web pages more important than others? Their research led to the formation of the Google search engine. In this programming assignment, you are required to implement a simplified version of the original PageRank algorithm on which Google was built.

<strong>Representing the Web as a Graph </strong>

<strong>&nbsp;</strong>The idea that the entire internet can be represented as a graph. Each node represents a webpage and each edge represents a link between two webpages. This graph can be implemented as an Adjacency Matrix or an Adjacency List.&nbsp; <strong>Feel free to use any data structure. </strong>

&nbsp;

Now for the sake of simplicity, we are explaining the assignment in the form of an Adjacency Matrix.&nbsp; We represent the graph in the form of |V|x|V| matrix where |V| is the total number of vertices in the graph. This is mapped to the webpages in the entire internet. Thus, if there is an edge from V<sub>i</sub> to V<sub>j </sub>(the from_page points to_page), we have the value in our adjacency matrix M<sub>ij </sub>= 1 and 0 otherwise.

<strong>&nbsp;</strong>

<table width="0">
<tbody>
<tr>
<td width="24"><strong>1 </strong></td>
<td width="24">0</td>
<td width="24">1</td>
<td width="24">0</td>
<td width="24">1</td>
<td width="24">0</td>
</tr>
<tr>
<td rowspan="2" width="24"><strong>2 </strong>

<strong>3 </strong>
</td>
<td width="24">0</td>
<td width="24">0</td>
<td width="24">0</td>
<td width="24">1</td>
<td width="24">0</td>
</tr>
<tr>
<td width="24">0</td>
<td width="24">0</td>
<td width="24">0</td>
<td width="24">0</td>
<td width="24">1</td>
</tr>
<tr>
<td width="24"><strong>4 </strong></td>
<td width="24">0</td>
<td width="24">0</td>
<td width="24">1</td>
<td width="24">0</td>
<td width="24">0</td>
</tr>
<tr>
<td width="24"><strong>5 </strong></td>
<td width="24">1</td>
<td width="24">1</td>
<td width="24">0</td>
<td width="24">0</td>
<td width="24">0</td>
</tr>
</tbody>
</table>
<strong><em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>1 &nbsp;&nbsp;&nbsp;&nbsp; 2 &nbsp;&nbsp;&nbsp;&nbsp; 3 &nbsp;&nbsp;&nbsp;&nbsp; 4 &nbsp;&nbsp;&nbsp;&nbsp; 5 </strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; M= </strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Core Idea of PageRank </strong>

<strong>&nbsp;</strong>

<ol>
<li>Important web pages will point to other important webpages.</li>
<li>Each page will have a score and the results of the search will be based on the page score (called page rank).</li>
</ol>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Rank(i) = j/out_degree(j) + k/out_degree(k)

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Each webpage is thus a node in the directed graph and has incoming edges and outgoing edges. Each node has a rank. According to PageRank, this rank is equally split among the node’s outgoing links and this rank is equal to the sum of the incoming ranks. The rank is based on the indegree (the number of nodes pointing to it) and the importance of incoming node. This is important considering let’s say you create your personal website and have a million links to other pages of importance. If this was not the case and rank used out links, we can easily dupe the algorithm. Therefore, the rank is based on in-links.

<strong>Goal </strong>

In this assignment, you need to compute the rank of the webpages using a Simplified Algorithm explained in the example below.

&nbsp;

<strong>Input </strong>

Line 1 contains the number of lines (n) that will follow and the number of power iterations you need to perform. Each line from

2 to n will contain two URL’s –&nbsp; <em>from_page&nbsp;&nbsp;&nbsp; to_page</em>&nbsp;&nbsp;&nbsp; separated by a space. This means from_page points to the URL to_page.

&nbsp;

<strong>Output </strong>

Print the PageRank of all pages after n powerIterations in ascending alphabetical order of webpage. Also, round off the rank of the page to two decimal places.

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<h1>Explanation through a Core Example</h1>
<table width="0">
<tbody>
<tr>
<td width="48"><strong>&nbsp;</strong>

<strong>Input: </strong>
</td>
<td width="96">7 2</td>
<td width="53"></td>
</tr>
<tr>
<td width="48"></td>
<td width="96">google.com</td>
<td width="53">gmail.com</td>
</tr>
</tbody>
</table>
google.com &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; maps.com facebook.com &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ufl.edu ufl.edu &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; google.com ufl.edu &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; gmail.com maps.com &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; facebook.com gmail.com &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; maps.com

<sup>(2)</sup>

<strong>Output </strong>facebook.com 0.20 gmail.com 0.20 google.com 0.10 maps.com 0.30

ufl.edu 0.20

&nbsp;

<strong>Step 1: Mapping for Simplicity (Optional but you will need a mechanism to store unique vertices) </strong>Use a map/array to map the URL’s with a unique id

<strong><em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>Data Structure 1 </strong>

<table width="0">
<tbody>
<tr>
<td rowspan="2" width="31"><strong>1 </strong>

<strong>2 </strong>
</td>
<td width="106">google.com</td>
</tr>
<tr>
<td width="106">gmail.com</td>
</tr>
<tr>
<td width="31"><strong>3 </strong></td>
<td width="106">facebook.com</td>
</tr>
<tr>
<td width="31"><strong>4 </strong></td>
<td width="106">maps.com</td>
</tr>
<tr>
<td width="31"><strong>5 </strong></td>
<td width="106">ufl.edu</td>
</tr>
</tbody>
</table>
<ul>
<li>com</li>
<li>com</li>
<li>com</li>
<li>com</li>
<li>edu</li>
</ul>
&nbsp;

<strong>Step 2: Graph Representation and Page Rank </strong>

In page rank, the equation for your graph is given as follows:-

<strong>Rank of a Page, r= M.r&nbsp;&nbsp;&nbsp; where, </strong>

M is the matrix with values given by the following:

M<sub>ij </sub>= 1/d<sub>j</sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; if there is an edge from V<sub>j</sub> to V<sub>i </sub>(d<sub>j </sub>is the outdegree of node j)

&nbsp;

<ul>
<li>otherwise</li>
</ul>
&nbsp;

For our graph, the adjacency matrix, M will look like:

&nbsp;

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

&nbsp;

<ul>
<li><strong>2 3 4 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 5 </strong></li>
</ul>
<table width="0">
<tbody>
<tr>
<td rowspan="5" width="24"><strong>1 </strong>

<strong>2 </strong>

<strong>3 </strong>

<strong>4 </strong>

<strong>5 </strong>
</td>
<td width="35">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="35">1/d<sub>5</sub></td>
</tr>
<tr>
<td width="35">1/d<sub>1</sub></td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="35">1/d<sub>5</sub></td>
</tr>
<tr>
<td width="35">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">1/d<sub>4</sub></td>
<td width="35">0</td>
</tr>
<tr>
<td width="35">1/d<sub>1</sub></td>
<td width="36">1/d<sub>2</sub></td>
<td width="36">0</td>
<td width="36">0</td>
<td width="35">0</td>
</tr>
<tr>
<td width="35">0</td>
<td width="36">0</td>
<td width="36">1/d<sub>3</sub></td>
<td width="36">0</td>
<td width="35">0</td>
</tr>
</tbody>
</table>
<strong>Step 3: Power iteration, r(t+1)=M.r(t) </strong>

This means that a rank of the webpage at time t+1 is equal to the rank of that page at time t multiplied by matrix, M. To achieve this, we create our matrix M based on input. Next, we initialize r(t) which is a matrix of size |V|x1 and consists of the ranks of every webpage. We initialize r(t) to 1/|V|. Next we compute power_iterations based on our input.

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;r(0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; M&nbsp;&nbsp; </strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>

<strong><em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 4 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 5 </strong>

<strong>&nbsp;</strong>

<table width="0">
<tbody>
<tr>
<td width="60">&nbsp;

<table width="0">
<tbody>
<tr>
<td width="24"><strong>1 </strong></td>
<td width="35">1/5</td>
</tr>
<tr>
<td width="24"><strong>2 </strong></td>
<td width="35">1/5</td>
</tr>
<tr>
<td rowspan="2" width="24"><strong>3 </strong>

<strong>4 </strong>
</td>
<td width="35">1/5</td>
</tr>
<tr>
<td width="35">1/5</td>
</tr>
<tr>
<td width="24"><strong>5 </strong></td>
<td width="35">1/5</td>
</tr>
</tbody>
</table>
</td>
<td width="545">&nbsp;

<table width="0">
<tbody>
<tr>
<td width="24"><strong>1 </strong></td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="35">1/d<sub>5</sub></td>
</tr>
<tr>
<td width="24"><strong>2 </strong></td>
<td width="36">1/d<sub>1</sub></td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="35">1/d<sub>5</sub></td>
</tr>
<tr>
<td rowspan="2" width="24"><strong>3 </strong>

<strong>4 </strong>
</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">1/d<sub>4</sub></td>
<td width="35">0</td>
</tr>
<tr>
<td width="36">1/d<sub>1</sub></td>
<td width="36">1/d<sub>2</sub></td>
<td width="36">0</td>
<td width="36">0</td>
<td width="35">0</td>
</tr>
<tr>
<td width="24"><strong>5 </strong></td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">1/d<sub>3</sub></td>
<td width="36">0</td>
<td width="35">0</td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>
<strong>&nbsp;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>&nbsp;&nbsp; </em>1&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 4 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 5 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>1 </strong>

<strong>&nbsp;</strong>

<strong>1 </strong>

<table width="0">
<tbody>
<tr>
<td width="24"><strong>1 </strong></td>
<td width="37">1/10</td>
</tr>
<tr>
<td width="24"><strong>2 </strong></td>
<td width="37">1/5</td>
</tr>
<tr>
<td rowspan="2" width="24"><strong>3 </strong>

<strong>4 </strong>
</td>
<td width="37">1/5</td>
</tr>
<tr>
<td width="37">3/10</td>
</tr>
<tr>
<td width="24"><strong>5 </strong></td>
<td width="37">1/5</td>
</tr>
</tbody>
</table>
<table width="0">
<tbody>
<tr>
<td width="35">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">1/2</td>
<td width="38"><strong>1 </strong></td>
<td width="35">1/5</td>
</tr>
<tr>
<td width="35">1/2</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">1/2</td>
<td width="38"><strong>2 </strong></td>
<td width="35">1/5</td>
</tr>
<tr>
<td width="35">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">1</td>
<td width="36">0</td>
<td rowspan="2" width="38">x <strong>&nbsp;3 </strong>

<strong>4 </strong>
</td>
<td width="35">1/5</td>
</tr>
<tr>
<td width="35">1/2</td>
<td width="36">1</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="35">1/5</td>
</tr>
<tr>
<td width="35">0</td>
<td width="36">0</td>
<td width="36">1</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="38"><strong>5 </strong></td>
<td width="35">1/5</td>
</tr>
</tbody>
</table>
r(t+1)=r(0+1)=r(1) =M.r(0)=&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>2 </strong>=

<sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup><strong>3 </strong>

<strong><sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup>4 </strong>

<strong><sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup>5 </strong>

<strong>&nbsp;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; M&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; r(0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; =&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; r(1) </strong>

<strong>&nbsp;</strong>

In this input case, the number of power_iterations is 2, if it is 1 then return the initializing rank matrix or r(0). If iterations&gt;2, the process repeats where you multiply the matrix, M with the new rank matrix r(t+1) at the next iteration.

&nbsp;

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Stepik Test Case Two Explanation:- (Power_iteration=3) </strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>&nbsp;&nbsp; </em>1&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 4 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 5 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </em>1 </strong>

<strong>&nbsp;</strong>

<strong>1 </strong>

<table width="0">
<tbody>
<tr>
<td width="24"><strong>1 </strong></td>
<td width="37">1/10</td>
</tr>
<tr>
<td width="24"><strong>2 </strong></td>
<td width="37">3/20</td>
</tr>
<tr>
<td width="24"><strong>3 </strong></td>
<td width="37">3/10</td>
</tr>
<tr>
<td width="24"><strong>4 </strong></td>
<td width="37">1/4</td>
</tr>
<tr>
<td width="24"><strong>5 </strong></td>
<td width="37">1/5</td>
</tr>
</tbody>
</table>
<table width="0">
<tbody>
<tr>
<td width="35">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="35">1/2</td>
<td rowspan="2" width="38"><strong>1 </strong>

<strong>2 </strong>
</td>
<td width="37">1/10</td>
</tr>
<tr>
<td width="35">1/2</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="35">1/2</td>
<td width="37">1/5</td>
</tr>
<tr>
<td width="35">0</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="36">1</td>
<td width="35">0</td>
<td width="38">x <strong>&nbsp;3 </strong></td>
<td width="37">1/5</td>
</tr>
<tr>
<td width="35">1/2</td>
<td width="36">1</td>
<td width="36">0</td>
<td width="36">0</td>
<td width="35">0</td>
<td width="38"><strong>4 </strong></td>
<td width="37">3/10</td>
</tr>
<tr>
<td width="35">0</td>
<td width="36">0</td>
<td width="36">1</td>
<td width="36">0</td>
<td width="35">0</td>
<td width="38"><strong>5 </strong></td>
<td width="37">1/5</td>
</tr>
</tbody>
</table>
r(t+1)=r(1+1)=r(2) =M.r(1)=&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <strong>2 </strong>=

<sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup><strong>3 </strong>

<strong><sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup>4 </strong>

<strong><sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup>5 </strong>

<strong>&nbsp;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; M&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; x&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; r(1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; =&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; r(2) </strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Template </strong>

You are allowed to use your own template but make sure your code passes the sample test cases. An example template to think about the problem is :

&nbsp;

Class AdjacencyListorMatrix {&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; private:

//Think about what member variables you need to initialize&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; public:

//Think about what helper functions you will need in the algorithm

};

&nbsp;

void AdjacencyListorMatrix::PageRank(int n){&nbsp; } &nbsp;&nbsp; // prints the PageRank of all pages after n powerIterations in ascending alphabetical order of webpage and rounding rank to two decimal places]

&nbsp;

// This class and method are optional. To accept input, you can use this method:

&nbsp;

&nbsp;

int main()

{

int no_of_lines, power_iterations;

std::string from, to;&nbsp;&nbsp;&nbsp;&nbsp; std::cin &gt;&gt; no_of_lines;&nbsp;&nbsp;&nbsp;&nbsp; std::cin &gt;&gt; power_iterations;

for(int i=0;i&lt; no_of_lines;i++)

{&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; std::cin&gt;&gt;from;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; std::cin&gt;&gt;to;

// Do Something

}

//Create a graph

Created_Graph.PageRank(power_iterations);

}
