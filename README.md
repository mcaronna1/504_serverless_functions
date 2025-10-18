# 504_serverless_functions
Homework: Multi‑Cloud Serverless Function # Lab Rules 

There are several ways to diagnose diabetes. Each way usually needs to be repeated on a second day to diagnose diabetes.
Testing should be carried out in a health care setting (such as your doctor’s office or a lab). If your doctor determines that your blood glucose (blood sugar) level is very high, or if you have classic symptoms of high blood glucose in addition to one positive test, your doctor may not require a second test to diagnose diabetes. This test checks your fasting blood glucose levels. Fasting means after not having anything to eat or drink (except water) for at least 8 hours before the test. This test is usually done first thing in the morning, before breakfast.

Fasting Plasma Glucose (FPG) 
[create](Images/FPG.jpg)

<img width="480" height="480" alt="image" src="https://github.com/user-attachments/assets/c8f34bc4-99e8-41d8-aef1-3024402e64e1" />

# Citation
Diabetes diagnosis. Diabetes Diagnosis & Tests | ADA. (n.d.). https://diabetes.org/about-diabetes/diagnosis 

# Public endpoint URLs for each function

# GCP
(https://python-504-506850586260.europe-west1.run.app)

# AZURE
https://fpg-test-esbqeqfreyfjbvej.canadacentral-01.azurewebsites.net/api/fpg?code=D9UYbL2VNOOi-XPwCBCU7bgE4r-4OPMl2XJdZQXcM7JsAzFua48HXQ==

# Loom Recording

https://www.loom.com/share/57762ce065f04beb9343216d806f6b0c?sid=bc70ed7e-c16b-4276-a568-8b4d8445c8bc

# Deployment Commands

# GCP
1. Click Write a function
2. Fill in name/region/runtime/authentication/billling/services/ingress
3. Create
4. Source code edit from there
5. Colab and Deploy

# AZURE 
1. Create function app
2. Consumption
3. Function name
4. Operating system: lInux
5. Run time: Python 3.12
6. Region
7. Depoyment
8. Create function
9. Colab Deploy

# Comparison of the two clouds
 Google Cloud Functions                                            | Azure Functions                                    |
 ----------------------------------------------------------------- | -------------------------------------------------- |
 Python                                                            | Python                                          
 Trigger                                                           | Triggers function        
 Pay for how much you use,but can use little amount                | Same — pay for what you use                        |
 
I had a hard time working with Azure app functions because my code wouldn’t upload properly and kept showing error messages that were difficult to understand. It took me several tries to figure out what was wrong. On the other hand, working with GCP app functions was much easier. When I made changes to my code on GCP, the errors were explained in simpler terms, making it faster and less frustrating to fix problems. Because of this, if I had to choose between the two, I would prefer to work with GCP. I have also saved all of my failed attempts and error logs from working with Azure in a folder for reference.
 
