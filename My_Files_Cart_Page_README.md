 

### The “My Files” cart page 

The Integrated Canine Data Commons (ICDC) is a repository that enables cohort building and discovery through the interactive “Explore” Dashboard. Once cases and samples of interest have been identified, the files can be added to the “My Files” Cart Page. This page is intended to compile data files of interest and facilitate downstream analysis using publicly available or custom cloud-based bioinformatic workflows, pipelines, or applications within the [Cancer Research Data Commons (CRDC)](https://datacommons.cancer.gov/). 
 

### The Concept of a File Manifest in the CRDC 

 
The CRDC is a cloud-based ecosystem that provides secure access to cancer research data and seamless integration with analytics platforms and tools to empower scientific discovery. The CRDC is comprised of repositories, infrastructure, and cloud resources. The repositories host case and subject-level data and cohort building tools. The infrastructure provides interoperability tools that can interrogate data across repositories and the mechanisms to support authentication, authorization, and permanent digital object identifiers for files. The cloud resources provide web-based applications and analysis tools that can be used at scale to support downstream computational research using the data discovered through the repositories and infrastructure. Data is most commonly transferred from the repositories to the cloud resources using a **file manifest**.  A file manifest is simply a comma separated value (CSV) file that contains certain elements of metadata unique to a particular file that is required for a downstream cloud resource, such as the [Seven Bridges Cancer Genomics Cloud (SBG CGC)](https://www.cancergenomicscloud.org/), to access and stream selected files directly from cloud storage. This negates the need for a user to download any files locally, which ensures a safe and efficient transfer of data within the CRDC ecosystem. 
 

###The ICDC File Manifest 

 
In the ICDC, a user can easily generate a file manifest using the Dashboard Explorer page. Data can be filtered by various attributes using a robust menu of facet filters. Cases, samples, and files matching selected filter criteria are displayed in a table and represented by color-coded widgets. After the desired level of filtering has been completed, files associated with cases and samples can be added to a user’s “My Files” cart page. Once files have been added to the cart, clicking on the “Download File Manifest” button will generate a file manifest compatible with any of the CRDC Cloud Resources. The ICDC file manifest is ascribed a timestamp at the time of download and includes the study code, case ID, file name, file ID, and MD5sum pertaining to each file. 

 

### Exporting the ICDC File Manifest to SBG-CGC  

 

After downloading the file manifest from the ICDC, there is no need to download any of the ICDC files locally, instead the file manifest provides all of the instructions needed for the Cloud Resources to access these files on demand directly from cloud storage.  
 
In order to export the ICDC file manifest to the Seven Bridges’ Cancer Genomics Cloud follow the steps listed below: 
 

1. Create an account or login at this URL: [https://www.cancergenomicscloud.org/](https://www.cancergenomicscloud.org/)

2. Create a project or select an existing project appropriate for digital access to the files in the file manifest.  

3. From the CGC dashboard navigation bar select “Files” and then click on the “+ Add files” button dropdown menu.  

4. From the “Import files from” dropdown menu select “Integrated Canine Data Commons (ICDC)”.  

5. Upload the local copy of the ICDC file manifest generated from the ICDC by dragging the file to drop zone or clicking on the “Browse files” button. 

6. Use the free text search text box to add applicable tags or comments associated with the batch of files being imported and click on the “Import” button. 

7. There will now be DRS identifiers displayed for each file from the file manifest imported within the selected CGC project. 

8. These files can now be viewed in the CGC Genome Browser or selected as inputs for downstream analysis. 

 

### The Export to CGC button 

This button enables a simple and immediate transfer of a file manifest generated in the ICDC to the Seven Bridges’ Cancer Genomics Cloud. Once a cohort of interest has been derived from the ICDC Explore Dashboard and files have been added to the “My Files” Cart Page, clicking on the “Export to CGC” button available from the top menu will trigger the transfer of necessary file metadata such that once a user is authenticated with the CGC these files can be digitally accessed from ICDC Cloud Storage from within a CGC project. 

 

 

 