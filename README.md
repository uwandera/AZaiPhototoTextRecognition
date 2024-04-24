# Desafios da Plataforma DIO de AI de Imagem para Texto
Olá galera, esse tutorial será o mesmo da plataforma pois ainda não consegui usar python para API REST.
Setar as variaveis de ambiente de saber separar o codigo certinho necessitam de um curso extra que não é o objetivo aqui!

Create an Azure AI services resource
You can use Azure AI Vision’s OCR capabilities with an Azure AI services multi-service resource. If you haven’t already done so, create an Azure AI services resource in your Azure subscription.

In another browser tab, open the Azure portal at https://portal.azure.com, signing in with the Microsoft account associated with your Azure subscription.

Click the ＋Create a resource button and search for Azure AI services. Select create an Azure AI services plan. You will be taken to a page to create an Azure AI services resource. Configure it with the following settings:
Subscription: Your Azure subscription.
Resource group: Select or create a resource group with a unique name.
Region: East US.
Name: Enter a unique name.
Pricing tier: Standard S0.
By checking this box I acknowledge that I have read and understood all the terms below: Selected.
Select Review + create then Create and wait for deployment to complete.
Connect your Azure AI service resource to Vision Studio
Next, connect the Azure AI services resource you provisioned above to Vision Studio.

In another browser tab, navigate to Vision Studio at https://portal.vision.cognitive.azure.com.

Sign in with your account and making sure you are using the same directory as the one where you have created your Azure AI services resource.

On the Vision Studio home page, select View all resources under the Getting started with Vision heading.

On the Select a resource to work with page, hover your mouse cursor over the resource you created above in the list and then check the box to the left of the resource name, then select Select as default resource.

Close the settings page by selecting the “x” at the top right of the screen.

Extract text from images in the Vision Studio
In a web browser, navigate to Vision Studio at https://portal.vision.cognitive.azure.com.

On the Getting started with Vision landing page, select Optical character recognition, and then the Extract text from images tile.

Under the Try It Out subheading, acknowledge the resource usage policy by reading and checking the box.

Select https://aka.ms/mslearn-ocr-images to download ocr-images.zip. Then open the folder.

On the portal, select Browse for a file and navigate to the folder on your computer where you downloaded ocr-images.zip. Select advert.jpg and select Open.

Now review what is returned:
In Detected attributes, any text found in the image is organized into a hierarchical structure of regions, lines, and words.
On the image, the location of text is indicated by a bounding box, as shown here:

You can now try another image. Select Browse for a file and navigate to the folder where you saved the files from GitHub. Select letter.jpg.

Review the results of the second image. It should return the text and bounding boxes of the text. If you have time, try note.jpg and receipt.jpg.

Dont forget to clean up!!
