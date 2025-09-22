## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:
<img width="899" height="536" alt="Screenshot 2025-09-12 161729" src="https://github.com/user-attachments/assets/59c743f2-01b1-45f8-925e-65ea08c9a877" />
<img width="1000" height="665" alt="Screenshot 2025-09-12 161736" src="https://github.com/user-attachments/assets/bb5101d7-824a-4313-8abf-206692c3ba31" />
<img width="1165" height="656" alt="Screenshot 2025-09-12 161744" src="https://github.com/user-attachments/assets/1f0609ef-f34f-48bf-ab28-31a857912f42" />
<img width="881" height="619" alt="Screenshot 2025-09-12 161751" src="https://github.com/user-attachments/assets/e4c458a3-7fa4-4ac8-ac5f-2e7abb3c2630" />
<img width="1202" height="501" alt="Screenshot 2025-09-12 161802" src="https://github.com/user-attachments/assets/6969c616-3352-4201-9479-8eb66e603897" />
<img width="583" height="51" alt="Screenshot 2025-09-12 161819" src="https://github.com/user-attachments/assets/d745a2ae-94a3-4623-9209-3ffa4d1df248" />
<img width="1079" height="626" alt="Screenshot 2025-09-12 161826" src="https://github.com/user-attachments/assets/4a7501bb-4f67-4eba-83b4-8e0f80ffd21e" />
<img width="994" height="601" alt="Screenshot 2025-09-12 161832" src="https://github.com/user-attachments/assets/29b083cb-c6c5-4285-b894-5f38b465ba62" />
<img width="1275" height="221" alt="Screenshot 2025-09-12 181929" src="https://github.com/user-attachments/assets/fc4bcc34-95cf-4263-ada4-4708bfdf0d0c" />
<img width="973" height="550" alt="Screenshot 2025-09-19 160720" src="https://github.com/user-attachments/assets/9d97a91c-2bf7-47aa-bf5b-33a98c61c967" />
<img width="568" height="188" alt="Screenshot 2025-09-19 160731" src="https://github.com/user-attachments/assets/05a6de45-9e84-48c9-adb8-660a618afebe" />
<img width="973" height="712" alt="Screenshot 2025-09-19 160739" src="https://github.com/user-attachments/assets/99772514-1ecc-4aff-b2d7-9472a06a5347" />
<img width="940" height="638" alt="Screenshot 2025-09-19 160745" src="https://github.com/user-attachments/assets/95c065bb-656c-48de-b3c6-1ae3162fddb5" />
<img width="978" height="617" alt="Screenshot 2025-09-19 160751" src="https://github.com/user-attachments/assets/93971f7c-1f60-437c-8687-b45acc3889b3" />
<img width="965" height="627" alt="Screenshot 2025-09-19 160756" src="https://github.com/user-attachments/assets/86d2b68a-60c6-4f32-9aca-1cfa744a5375" />
<img width="1056" height="555" alt="Screenshot 2025-09-19 160802" src="https://github.com/user-attachments/assets/07e096ee-ab34-479b-b472-e7b8ad8e542f" />
<img width="1011" height="624" alt="Screenshot 2025-09-19 160807" src="https://github.com/user-attachments/assets/707742f7-da8e-440d-b704-c626fa22f60d" />
<img width="1108" height="566" alt="Screenshot 2025-09-19 160813" src="https://github.com/user-attachments/assets/0f928305-e04b-4905-953f-cbd199269b75" />
<img width="977" height="617" alt="Screenshot 2025-09-19 160819" src="https://github.com/user-attachments/assets/b50bfc6b-82fa-4c7b-8cd0-3de1c607cd12" />
<img width="1127" height="555" alt="Screenshot 2025-09-19 160824" src="https://github.com/user-attachments/assets/09fb5081-d186-4b78-b025-d8d5db8549b2" />
<img width="985" height="622" alt="Screenshot 2025-09-19 160832" src="https://github.com/user-attachments/assets/b66f45c0-522f-4f3f-a540-7233afe0adc3" />
<img width="1162" height="520" alt="Screenshot 2025-09-19 160842" src="https://github.com/user-attachments/assets/9f8fee4b-4ba0-456f-9d01-316eabc44e86" />
<img width="1066" height="611" alt="Screenshot 2025-09-19 160849" src="https://github.com/user-attachments/assets/643b230e-5ac2-4164-bc8a-759b3e9bbca2" />
<img width="1149" height="569" alt="Screenshot 2025-09-19 160854" src="https://github.com/user-attachments/assets/1f044444-5c4d-4f81-91f0-83b3f3c3ebff" />
<img width="1078" height="554" alt="Screenshot 2025-09-19 160904" src="https://github.com/user-attachments/assets/36149a8e-6c63-4387-bb49-06036fa26fc1" />
<img width="1122" height="608" alt="Screenshot 2025-09-19 160913" src="https://github.com/user-attachments/assets/98132745-fd3e-4899-b34f-8f49d982a7ae" />
<img width="989" height="633" alt="Screenshot 2025-09-19 160908" src="https://github.com/user-attachments/assets/6f48c84d-4c5c-4694-80bd-dce64bf92de9" />
<img width="1122" height="608" alt="Screenshot 2025-09-19 160913" src="https://github.com/user-attachments/assets/53a54ff2-35f7-4d86-ba37-33814eb1d4d9" />
<img width="948" height="606" alt="Screenshot 2025-09-19 160918" src="https://github.com/user-attachments/assets/d0779594-b982-4eca-8448-6eaf80f342af" />

# RESULT:
Thus the given data, Feature Encoding, Transformation process and save the data to a file was performed successfully.

       
