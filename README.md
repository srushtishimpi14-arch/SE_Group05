# SE Group 05

# Smart Image Inpainting & Outpainting System

## Problem Statement  

Real-world images often contain missing regions, distortions, or unwanted objects that reduce visual quality and limit their usability. Current restoration methods are either manual, time-intensive, or restricted to specific scenarios. Therefore, there is a need for an automated and scalable AI-based system capable of accurately detecting and reconstructing damaged or unwanted regions while preserving natural image appearance and structural consistency.

### Tech Stack  

- **Frontend:** React.js (for building a dynamic, responsive, and interactive user interface that allows users to upload images, preview results, and compare before-and-after outputs) 
- **Backend:** Node.js with Express.js (for handling API requests, managing business logic, processing image data, and connecting the frontend with the AI model) 
- **Authentication:** Firebase Authentication (for secure user login, registration, and account management using email/password or Google authentication)  
- **Database:** MongoDB (for storing user information, image metadata, restoration history, and system logs if required) 
- **Cloud Storage:** Firebase Storage (for securely storing and managing uploaded images and restored outputs in the cloud)  
- **Deployment:** Frontend – Firebase Hosting / Vercel (for fast and scalable hosting of the React application)
Backend – AWS / Heroku (for deploying and managing the server-side application and AI processing services)  

### Expected Outcome  
The expected outcome of this project is the successful development of a fully functional, AI-based image restoration web application capable of automatically detecting and reconstructing damaged or unwanted regions in images with high accuracy and visual quality.

**The system is expected to:**
Accurately identify missing, distorted, or unwanted regions in uploaded images.
Reconstruct damaged areas while maintaining structural consistency and natural appearance.
Reduce manual editing time significantly compared to traditional restoration methods.
Provide high-quality restored images with minimal visual artifacts.
Offer a smooth, user-friendly interface for uploading, processing, and downloading images.
Ensure secure user authentication and safe cloud-based storage of images.
Deliver scalable performance capable of handling multiple users simultaneously.

**Performance Expectations:**
Improved image quality measured using metrics like PSNR and SSIM.
Faster processing time compared to manual editing tools.
High user satisfaction due to realistic restoration results.
Reliable and secure cloud-based system operation.

Overall, the system is expected to provide an automated, scalable, and efficient solution for image restoration while preserving the natural look and structural integrity of images. 


## Hypothesis  
The hypothesis of this project is that an AI-based deep learning model trained on a large, diverse, and well-annotated dataset can effectively detect damaged, distorted, or missing regions in images and accurately reconstruct them while preserving structural consistency, texture details, lighting, and overall visual realism. It is further hypothesized that integrating advanced image inpainting and outpainting techniques will allow the system not only to restore corrupted areas but also to intelligently extend image boundaries without generating noticeable artifacts. The system is expected to significantly reduce manual effort and processing time compared to traditional editing or rule-based restoration methods. Moreover, by leveraging scalable cloud infrastructure and modern web technologies, the proposed solution will provide efficient, secure, and high-quality image restoration services suitable for real-world applications such as old photo enhancement, digital media editing, and content creation.

## Technologies  


| **Frontend** | **Backend** | **Database** | **Authentication** | **Payment** |
|-------------|------------|-------------|--------------------|-------------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react) | ![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js) | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb) | ![Firebase Authentication](https://img.shields.io/badge/Firebase%20Auth-FFCA28?style=for-the-badge&logo=firebase) | ![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal) |

| **APIs & Services** | **Tools** |  
|--------------------|-----------|  
| ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase) | ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git) |  
| ![Firebase Auth](https://img.shields.io/badge/Firebase%20Auth-FFCA28?style=for-the-badge&logo=firebase) | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github) |  
|  | ![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira) |  
|  | ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code) |  

---

## Roles and Responsibilities  
### **Team Members**  

#### **Tanisha Desai**  
- **Role:** Frontend Developer, UI Design  
- **Responsibilities:**
  
-Design and develop an interactive and responsive user interface using React.js.

-Implement image upload, mask selection (for inpainting), and canvas extension options (for outpainting).

-Develop before-and-after comparison view for restored and extended images.

-Integrate Firebase Authentication for secure login and user access.

-Ensure smooth communication between frontend and backend APIs.

#### **Shailza Dixit**  
- **Role:** Backend Developer, Data Fetching  
- **Responsibilities:**

-Develop RESTful APIs using Node.js and Express.js.

-Integrate deep learning models for image inpainting and outpainting.

-Handle image processing workflows and manage model inference requests.

-Optimize backend performance for faster image reconstruction.

-Ensure secure handling of user data and image files.

-Deploy and maintain backend services on cloud platforms.

#### **Srushti Shimpi**  
- **Role:** Backend Developer, Data Designing  
- **Responsibilities:**
 
-Design MongoDB schema for storing user data and restoration history.

-Manage Firebase Storage for uploaded and processed images.

-Maintain records of inpainting and outpainting operations.

-Ensure data integrity, scalability, and secure storage.

-Monitor cloud storage usage and optimize performance.

## Project Team Members  

<table>
  <tr align="center">
    <td>
      <img src="<image link>?size=250" width="180" height="180" /><br>
      <b>Member 1 (Team Lead)</b><br>
      Frontend Developer Project Management
    </td>
    <td>
     <img src="<image link>?size=250" width="180" height="180" /><br>
      <b>Member 2</b><br>
      Frontend Developer UI Design
    </td>
    <td>
     <img src="<image link>?size=250" width="180" height="180" /><br>
      <b>Member 3</b><br>
      Backend Developer Data Fetching
    </td>
    <td>
      <img src="<image link>?size=250" width="180" height="180" /><br>
      <b>Member 4</b><br>
      Backend Developer Data Designing
    </td>
  </tr>
</table>
