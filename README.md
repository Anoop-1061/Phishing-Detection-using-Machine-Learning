# Phishing-Detection-using-Machine-Learning
This project presents a chrome browser extension which will be able to predict the site to be visited by the user is phishing or not using feature extraction. For the extension to make this decision we first train our dataset with three algorithm namely: Neural Network, Random Forest and Support Vector Machine (SVM). After knowing that SVM algorithm has the highest accuracy among the three algorithms we use the weights of the trained SVM algorithms in our browser extension as preference in predicting the result. Once the trained weights are supplied to the Javascript file which does all the calculations. This Javascript file collects the features from the site and using the weights predicts the result which is later shown to the user using the alert box in the browser.

## Steps to install the chrome extension:
1. Google Chrome -> More Tools -> Extensions
2. Click 'Load unpacked extension..'
3. Open the 'JavaScript' directory
4. Phishing Detection extension ready to monitor all the sites loaded on the Chrome browser

## GUI Design -
![image](https://user-images.githubusercontent.com/70109300/179913147-df2253da-e8fc-4e51-842f-6b2380ee6674.png)

## Alert box for Phishing Site Detected -
![image](https://user-images.githubusercontent.com/70109300/179913307-1e70e126-df4e-42b3-a981-e9716ddc5ea3.png)

## Outputs for Genuine or No phishing detected sites -
![image](https://user-images.githubusercontent.com/70109300/179913497-2f270733-7ffe-4fea-ba97-6f2ac1563d68.png)
![image](https://user-images.githubusercontent.com/70109300/179913537-006dd41e-3bc8-4da9-8442-db5717e91cd3.png)
![image](https://user-images.githubusercontent.com/70109300/179913574-5292eef7-5352-4a1c-85f6-820d071d1bac.png)

## Outputs for Phishing detected sites -
![image](https://user-images.githubusercontent.com/70109300/179913667-938d67ea-6d7a-45f3-83bf-64b3a1b78ef7.png)
![image](https://user-images.githubusercontent.com/70109300/179913699-cf7c781d-ecb6-4d97-b397-eb143567f85a.png)
![image](https://user-images.githubusercontent.com/70109300/179913728-04a43912-4896-45af-97c7-f78067682783.png)
