# Project Promotion Guideline

## Outline

This document involves details regarding project promotion and is organized as follows:
- **Section 1.** Project Page
- **Section 2.** Personal Page
- **Section 3.** Promotion via Social Media
- **Section 4.** Potential Effect of Project Promotion

## Project Page
➤ **Preview:**
|![img1](https://hackmd.io/_uploads/rJj-L8rD0.png)|![img2](https://hackmd.io/_uploads/HyjWIUrPC.png)|
|---|---|
|![img3](https://hackmd.io/_uploads/r1iWLUHPC.png)|![img4](https://hackmd.io/_uploads/rJhbL8rwA.png)|

➤ **Create your own project page:**
- **Step 1:** Clone a project page template.
  - **A.** Demo-based pages [[demo]](https://nerfies.github.io/) [[source code]](https://github.com/nerfies/nerfies.github.io)
    - Sliding-bar figure comparison
    - GIF and figures
  - **B.** Descriptive pages [[demo]](https://chen-hao-chao.github.io/ebflow) [[source code]](https://github.com/chen-hao-chao/ebflow/tree/gh-pages)
    - Latex symbols
    - Poster embedding
    - ‘Keywords’ and ‘venue’ banners

- **Step 2:** Customize the contents and push to your Github repo
  - **Step 2.1:** Checkout to a new branch `gh-pages` and reset to the empty init commit.
  - **Step 2.2:** Push your pages to this branch.
  - **Step 2.3:** After you push the commit, wait for a few minutes and see if there is a green checkmark on your GitHub repo.
  ![img5](https://hackmd.io/_uploads/S1c1v8SDA.png)
  - **Step 2.4:** Check out your project page link via `Settings -> Pages`.
  ![img6](https://hackmd.io/_uploads/r1rMPLHP0.png)
  - **Step 2.5:** Add your project page link to your Github repo.
  
  | ![img7](https://hackmd.io/_uploads/rJQSvIBwA.png) | ![img8](https://hackmd.io/_uploads/B1cBwIHDA.png) |
  |--|--|

- **Step 3:** Improve visibility via adding indexing requests (e.g., [Google console](https://search.google.com/search-console/about))
  - **Step 3.1:** Go to the Google Search Console website and sign in with your Google account.
  - **Step 3.2:** Click `Add a property` and enter the URL of your GitHub repository. For example, if your repository is located at `github.com/username/repo`, enter `github.com/username/repo` as the URL.
  ![img9](https://hackmd.io/_uploads/B1jqGPBDA.png)
  - **Step 3.3:** Follow the verification steps (i.e., add a header to your project page and push the commit to your GitHub again) to prove that you own the repository.
  - **Step 3.4:** Once your ownership is verified, click on `URL Inspection` in the left sidebar.
  - **Step 3.5:** Type in the URL of your GitHub repository and click `Enter`.
  - **Step 3.6:** Click on `Request indexing` to tell Google to index your repository.
  ![img10](https://hackmd.io/_uploads/ryIxXDrPR.png)
  - **Step 3.7:** Wait for Google to index your repository. This can take several days.
  - **Reference:** https://github.com/orgs/community/discussions/42375#discussioncomment-5296219

## Personal Page
➤ **Preview:**

|![img11](https://hackmd.io/_uploads/ryIAdLrvC.png)|![img12](https://hackmd.io/_uploads/rkLAuLrDR.png)|
|---|---|
|![img13](https://hackmd.io/_uploads/HJU0u8rPR.png)|![img14](https://hackmd.io/_uploads/By80_USDC.png)|

➤ **Create your own personal page:**
  - **Step 1:** Clone a project page template.
    - **A.** Personal page code base [[demo]](https://alshedivat.github.io/al-folio/) [[source code]](https://github.com/alshedivat/al-folio)
      - Fancier news, blog posts, project preview
      - Finer categories
    - **B.** Lance’s refined version [[demo]](https://chen-hao-chao.github.io/) [source code -> please contact Lance]
      - Improved clarity
      - Simplified CV page
      - Highlighted first author
      - Customized blog-post page
      - Customized external page position (i.e., X, email, semantic scholar, google scholar)
  - **Step 2:** Customize your page [[tutorial]](https://github.com/alshedivat/al-folio/blob/master/CUSTOMIZE.md). 
    - Modify the following files to inculde your personal information:
      - `_config.yml`
      - `_pages/*.md`
    - Modify the following files to adjust the layout and style:
      - `_sass/*.scss`
      - `_layouts/*.liquid`
  - **Step 3:** Download [docker](https://www.docker.com/products/docker-desktop/) for previewing the personal page. In the root directory, run the following command:
      - ```
        docker compose up
        ```
  - **Step 4:** After modifying the page, push the commits and the repository will automatically generate the `gh-pages` branch for deployment.
  - **Step 5:** Improve visibility by following **Step 3** in the last section.
  - **Step 6:** Some additional steps that you might be interested in:
    - (Optional) Use [Google Analytics](https://marketingplatform.google.com/about/analytics/) to monitor the backend data.
    - (Optional) Remove the `.github/workflows/broken-links.yml` and `.github/workflows/prettier.yml` files to disable the deployment examinations.
    ![img15](https://hackmd.io/_uploads/HJKXEvBP0.png)

## Promotion via Social Media
I would recommend using [Twitter (X)](https://x.com/home) for promoting academic projects. An effective strategy would be:
- Repost the post from an active account.
- Share a single-line insight. (It must be understandable given that the reading time is less than one minute.)


The following is an example [[original post]](https://x.com/chenhao_chao/status/1803406463479759087):

> The reinterpretion of a normalizing flow (NF) as an energy-based model enables the generalization of this equality. 
>
> By separating the linear (Sl) and non-linear (Sn) layers of NF, we can extract the unnormalized density and use importance sampling to estimate the constant Z(θ).
> | ![GQb8nkDaIAEM44f](https://hackmd.io/_uploads/ryFLUPHD0.jpg) | ![GQb8nkBaIAQEJ1S](https://hackmd.io/_uploads/SyKULDHDA.jpg) |
> |--|--|

This would be more effective than simply ask for attention [[original post]](https://x.com/chenhao_chao/status/1803413388036550839):


> 📍Check out our updated blog post where we redefine the DLSM objective function for discrete variables.
>
> Read more:
> Blog: https://chen-hao-chao.github.io/dlsm/
> Paper: https://arxiv.org/abs/2203.14206
> #generative #AI #score #diffusion
> ![GQcC1EGaIAMavM7](https://hackmd.io/_uploads/HytMPDrDC.png)


Posts in a recursive format (made by repeatedly commenting the posts) are also popular [[original post]](https://x.com/du_yilun/status/1803055445906452774):
| ![img16](https://hackmd.io/_uploads/Bk4tDwHw0.png) | ![img17](https://hackmd.io/_uploads/SyK-_vSDR.png) |
|--|--|



## Potential Effects

➤ Examine the effects via **Google Analytics** and **Google Console**:
![img18](https://hackmd.io/_uploads/BkTXFDSDR.png)

➤ Examine the effects on **Twitter**:
![img19](https://hackmd.io/_uploads/rkGktPHDR.png)
