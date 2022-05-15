# CMPE 172 - Lab #10 Notes

**Create Java with Gradle Workflow**

<img width="1440" alt="Choose Java with Gradle Workflow" src="https://user-images.githubusercontent.com/73107239/168466493-e4fc9f7e-cdfc-4386-8260-b13c86a146c4.png">

**Gradle.yaml File 1**

<img width="1440" alt="Gradle yml" src="https://user-images.githubusercontent.com/73107239/168467488-080e61e0-a744-43c8-a655-b8daf03b479b.png">

**Gradle.yaml File 2**

<img width="1440" alt="Gradle yml 2" src="https://user-images.githubusercontent.com/73107239/168467506-6633ce6f-515e-4e00-83c8-748009703294.png">


**Build.yaml Build Successful First Pic**

<img width="1440" alt="Grade yaml Build Succesful 1" src="https://user-images.githubusercontent.com/73107239/168466531-ae265d1f-4eee-4e03-a4d6-54ec699d93df.png">

**Build.yaml Build Successful Second Pic**

<img width="1440" alt="Grade yaml Build Succesful 2" src="https://user-images.githubusercontent.com/73107239/168466562-3b5207df-35dd-4410-a82e-0f07ee9268d4.png">

**Build.yaml Build Successful Third Pic**

<img width="1440" alt="Build yaml Build Successful First Pic 3" src="https://user-images.githubusercontent.com/73107239/168466578-18a2e55d-92a2-4f3d-a700-33b4760e2b09.png">

**Create Build and Deploy to GKE Workflow**

<img width="1440" alt="Choose Build and Deploy to GKE workflow" src="https://user-images.githubusercontent.com/73107239/168466692-12643c73-8f52-4200-ad49-de17af8e0ee3.png">

**Service Accounts**

<img width="1440" alt="Service Accounts" src="https://user-images.githubusercontent.com/73107239/168466736-d30dc7f3-87ba-4389-aa05-23a878a11f0f.png">

**Service Account Keys**

<img width="1440" alt="Service Account Keys" src="https://user-images.githubusercontent.com/73107239/168466768-836bd1d5-50ec-4280-828f-d7bab669c817.png">

**Action Secrets**

<img width="1440" alt="Action Secrets" src="https://user-images.githubusercontent.com/73107239/168466803-3a40ee84-4df0-45a4-a64d-641c1185fc05.png">

**Creating Google.yml**

<img width="1440" alt="Screen Shot 2022-05-15 at 1 21 53 AM" src="https://user-images.githubusercontent.com/73107239/168466877-b03a7fe7-8cee-4f71-84fd-d11775f115c3.png">

**Google.yml File 1**

<img width="1440" alt="Google yml 1" src="https://user-images.githubusercontent.com/73107239/168467591-9ad514a7-0b69-43e4-a844-677f7cb40e91.png">

**Google.yml File 2**

<img width="1440" alt="Google yml 2" src="https://user-images.githubusercontent.com/73107239/168467599-a5df9444-33d5-4e1f-be3f-d94d99b70b8d.png">

**Successfully Created Google.yml**

<img width="1440" alt="Successfully Created Google yml" src="https://user-images.githubusercontent.com/73107239/168466941-32414633-6c84-4400-85fe-fb17298162b5.png">

**CMPE172 Cluster Built**

<img width="1440" alt="cmpe172 cluster built" src="https://user-images.githubusercontent.com/73107239/168466972-6463cb7a-1089-4e66-8aa8-3a9bad20468d.png">

**Draft a New Release**

I already created one, so it says that the name is a duplicate.

<img width="1440" alt="Draft a New Release" src="https://user-images.githubusercontent.com/73107239/168467098-4dd5819f-2bb8-4077-9288-26f7f7a3b64c.png">

**New Release Loading**

<img width="1440" alt="Screen Shot 2022-05-15 at 1 25 17 AM" src="https://user-images.githubusercontent.com/73107239/168467134-a6f2dc9f-1498-47ef-9a9d-4ac395b63701.png">

**Error That I First Encountered**

<img width="1440" alt="Screen Shot 2022-05-15 at 1 30 03 AM" src="https://user-images.githubusercontent.com/73107239/168467173-9dca27a6-fd2a-4fe8-af90-400aed15ed03.png">

Looked at this link, but it didn't help.

https://github.com/google-github-actions/setup-gcloud/issues/253

The change that I made was redoing the GKE_PROJECT file so that it contained the project ID which I found in the next picture

**Project ID**

<img width="1440" alt="Project ID" src="https://user-images.githubusercontent.com/73107239/168467220-6f40b2ae-6a4a-4d92-8333-ca92ed6ce24f.png">

**Next Error That I Encountered**

<img width="1440" alt="Next Error That I Encountered" src="https://user-images.githubusercontent.com/73107239/168467281-bdeedeee-6e21-4889-9fce-113664c2cf44.png">

I fixed this error by remaking my service and giving myself the owner role. After that, the Draft Release was successfully able to be made.

**Draft Successfully Made**

<img width="1440" alt="Draft Successfully Made" src="https://user-images.githubusercontent.com/73107239/168467359-d312d609-be3f-45c3-8884-0de39c347338.png">

**Draft Successfully Made 2**

<img width="1440" alt="Draft Successfully Made 2" src="https://user-images.githubusercontent.com/73107239/168467384-4e7daf27-549e-4c0b-a708-e9b8b93ee622.png">

**Draft Successfully Made 3**

<img width="1440" alt="Draft Successfully Made 3" src="https://user-images.githubusercontent.com/73107239/168467417-7db264a4-081e-4ada-9082-b2893a5c59dc.png">

**Draft Successfully Made 4**

<img width="1440" alt="Draft Successfully Made 4" src="https://user-images.githubusercontent.com/73107239/168467440-eb116c6a-603b-4380-a1cd-cdbf7b2a0a01.png">

**Spring Gumball Deployment on GKE**

<img width="1440" alt="Spring Gumball Deployment 3" src="https://user-images.githubusercontent.com/73107239/168467742-0e55b6a6-5dcf-414d-9bf5-28ba3f7f0534.png">

<img width="1440" alt="Spring Gumball Deployment on GKE" src="https://user-images.githubusercontent.com/73107239/168467639-9c2ca9f3-c3cd-4a67-b4fb-cbf1afda445c.png">

<img width="1440" alt="Spring Gumball Deployment on GKE 2" src="https://user-images.githubusercontent.com/73107239/168467646-d49a45b0-bd8e-4602-ad53-b67d23bad687.png">

**Spring Gumball Service**

<img width="1440" alt="Spring Gumball Service 1" src="https://user-images.githubusercontent.com/73107239/168467768-e0aa29b2-005d-48a3-be64-93f7ba05e605.png">

<img width="1440" alt="Spring Gumball Service 2" src="https://user-images.githubusercontent.com/73107239/168467775-7bcca08d-4a06-413b-8bf5-e31d7287792c.png">

<img width="1440" alt="Spring Gumball Service 3" src="https://user-images.githubusercontent.com/73107239/168467776-8246e314-c412-4fca-9eca-7a94db71de94.png">

**Creating Ingress**

<img width="1440" alt="Screen Shot 2022-05-15 at 2 26 21 AM" src="https://user-images.githubusercontent.com/73107239/168467795-32208ebf-d821-4f81-a233-1e700513e2fb.png">

<img width="1440" alt="Creating Ingress 2" src="https://user-images.githubusercontent.com/73107239/168467816-0f611914-7fc6-4cc2-a7ee-bc3a5f391cf2.png">

**Spring Gumball Loadbalancer Successfully Made**

<img width="1440" alt="Spring Gumball LB Success 1" src="https://user-images.githubusercontent.com/73107239/168467851-30c1d35b-1325-4c3a-8b55-49aa88896e74.png">

<img width="1440" alt="Spring Gumball LB Success 2" src="https://user-images.githubusercontent.com/73107239/168467870-febb62b4-59c5-4caf-9b81-103c96526953.png">

<img width="1440" alt="Spring Gumball LB Success 3" src="https://user-images.githubusercontent.com/73107239/168467884-990a63f0-6f27-404a-afea-69c559ba7716.png">

**Spring Gumball Webpage Succesfully Loaded**

<img width="1440" alt="Spring Gumball Successfully Loaded 1" src="https://user-images.githubusercontent.com/73107239/168467908-0522e6d5-83bc-4dd8-bd73-a90c93024c11.png">

<img width="1440" alt="Spring Gumball Successfully Loaded 2" src="https://user-images.githubusercontent.com/73107239/168467921-f7b16a70-ed66-4a94-91d3-4eb249c989c1.png">




