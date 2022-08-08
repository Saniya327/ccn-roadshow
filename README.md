# ccn-roadshow
These are the deployment files extracted after deploying the coolstore app in the rhpds environment. 
1. The 'image' values need to be changed to valid images, as the rhpds environment is not longer available. 
2. The metadata such as 'uid', 'creationtime', 'resourceVersion', 'clusterIPs' etc need to be deleted so that it they can be deployed on any cluster.

To deploy:
Ensure the operators mentioned in the [this](https://docs.google.com/document/d/1EVkpTNgUjsVa6XBPS9AWzVTV7P6yM3G-wrwQguEbRV8/edit#heading=h.aghcg68r65mh) document are installed on the cluster


Use ACM and create a new application.
Provide the url and branch and click on save. 

Final topology of coolstore should look like this:

![image](https://user-images.githubusercontent.com/18498274/183521417-5652bc7a-f565-4fb6-86b6-8f512f14ee8e.png)
