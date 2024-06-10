## Exercise 5: Navigate to the search bar and search CloudFront

1. In the search bar at the top, Search for **CloudFront**.
2. Click on **CloudFront** in the dropdown as shown.

![](./Screenshots/22.png)

3. Select **Create a CloudFront distribution**.

![](./Screenshots/23.png)

4. In Origin domain select the name of the S3 bucket you stored.

![](./Screenshots/24.png)

5. Scroll down and Choose **Origin access control settings**
Click on **Create new OAC**

![](./Screenshots/25.png)

7. Scroll down and in (WAF) Click on **Do not create security protections**

![](./Screenshots/26.png)

7. Scroll down and in **Default root object** write **"index.html"**

![](./Screenshots/27.png)

8. Click on **Create Distribution**

![](./Screenshots/28.png)

9. In The S3 bucket policy needs to be updated banner click on **Copy policy**

![](./Screenshots/29.png)

10. In the same banner, choose the link to **Go to S3 bucket permissions to update policy**. (This takes you to your bucket detail page in the Amazon S3 console.)

![](./Screenshots/30.png)