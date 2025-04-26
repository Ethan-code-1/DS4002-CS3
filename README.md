# DS4002-CS3

## Getting Started
1. Consult the Hook Document
2. Consult the Rubric to understand case study goals and submission requirements
3. Review Articles found in ARTICLES folder
- Consider reading the files in this order: "AI and Art Classification" -> "What are Tensor Images?" -> "Exploring ResNet50" 
4. After completing the associated readings review the format of the data
5. Once familiar with the structure of the data consult the scripts section to begin. 

## FAQS

## Where to find the Data?
The data for this assignment can be found in the DATA folder. The data is called MetMuseumData.

## What is a high level overview of what I am doing?
You will be creating a image classification model. This model will build of the existing ResNet50 model found within the installed libraries. This pre-built model will help abstract away a lot of the complexity associated with building a machine learning model. 

## Where can I source the original data?
The original data can be found here: https://www.metmuseum.org/about-the-met/policies-and-documents/open-access
If you want more of a challenge, you are encouraged to pull your own art data from the url above but this is not required. All the data needed has already be sourced from the API and is stored in the data folder. This is done to do large processing times and pulling data from an API is not the focal point of this case study.

## How is the project structured?
/ (Main Directory) │ ├── README.md # Project overview and documentation ├── Hook_Document.md # Project motivation and introduction ├── Rubric.pdf # Grading criteria and project guidelines │ ├── data/ # Dataset and related files │ ├── Data_Appendix.pdf # Appendix with dataset details │ └── MetMuseumData.csv # Raw data file from the Met Museum API │ ├── scripts/ # Code and notebooks for model development │ └── model_creation.ipynb # Jupyter notebook with model building steps │ ├── articles/ # Related readings and reference materials │ ├── AI_and_Art_Classification.md # Article on AI in art classification │ ├── Exploring_ResNet50.md # Overview of ResNet50 architecture │ └── What_are_Tensor_Images.md # Explanation of tensor images │ └── OUTPUT/ # Results and visualizations ├── Model_Accuracy_over_Epochs.png # Accuracy graph from model training └── Model_Loss_over_Epochs.png # Loss graph from model training

## What libraries will I need installed to complete this case study?
Considering installing:
 <table>
  <tr>
    <th>Package</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td>numpy</td>
    <td>math operations, store data as an array</td>
  </tr>
  <tr>
    <td>pandas</td>
    <td>clean + process + explore data</td>
  </tr>
   <tr>
    <td>matplotlib</td>
    <td>create plots</td>
  </tr>
  <tr>
    <td>torchvision</td>
    <td>prepare image data to be used in convolutional neural network</td>
  </tr>
  <tr>
    <td>torch</td>
    <td>run convolutional neural networks</td>
  </tr>
  <tr>
    <td>tqdm</td>
    <td>have a progress meter for iterable functions</td>
  </tr>
  <tr>
    <td>sklearn</td>
    <td>create plots</td>
  </tr>
  <tr>
    <td>tensorflow</td>
    <td>plot and analyze image data</td>
  </tr>
</table> 