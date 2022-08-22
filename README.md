# 0x0B. Implement a design with bootstrap
## Details
 By: Nicolas Philippot, UI/UX designer and Guillaume Salva, CTO at Holberton School Weight: 3Project will startAug 21, 2022 12:00 AM, must end byAug 29, 2022 12:00 AMManual QA review must be done(request it when you are done with the project)In this project, you will implement 3 web pages with Bootstrap.You will use all HTML/CSS/Accessibility/Responsive design/Bootstrap knowledges that you learned previously. 
You won’t have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have fully functional web pages that look the same as the designer file.
Here the final result:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3c71cc99d2fc1c12a3d3.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=f5f188868a321fbb5e88088e10e63df47e2e23ce9e2222dffff6f3e37d1b4244) 

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens  [here](https://intranet-projects-files.s3.amazonaws.com/holbertonschool-webstack/623/Archive.zip) 

### Requirements
* You have to use Bootstrap
* Your  ` styles.css `  must be as small as you can - you must use as much as you can Bootstrap classes
### Imports
For this project, you will need: fonts from Google, JQuery, Bootstrap CSS/JS
```bash
<link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Coiny&display=swap" rel="stylesheet">

<script src="https://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

```
## Tasks
### 0. Read and be familiar with Figma
          mandatory         Progress vs Score  Task Body Create an account in  [Figma](https://intranet.hbtn.io/rltoken/0OS4ME4Kjnw0I82IVkkoSw) 
  and open these files:
* [Homepage](https://intranet.hbtn.io/rltoken/RLej4Ua6W3EmDh7UCwGTzQ) 
 - [fig file](https://intranet.hbtn.io/rltoken/1ZTxYF-usvxpIjj44YYcyw) 

* [Pricing](https://intranet.hbtn.io/rltoken/xQCL77_ePGWntUAe4T7ebQ) 
 - [fig file](https://intranet.hbtn.io/rltoken/AdJ6ZyZrG90gRNAI5bt_lA) 

* [Courses](https://intranet.hbtn.io/rltoken/__3w9ryapSUAwMaAYYS6ZA) 
 - [fig file](https://intranet.hbtn.io/rltoken/1JL-gCkfJ5Hqb0Sf2lmymw) 

And “Duplicate to your Drafts” to have access to all design details.
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0fcfea2e413a2a6fc1cd26118a6ed34bdd4d34f8f5716664df798e0e18dc2235) 

Important notes with Figma:
* if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/4uQkoVbAjr7lRVqSVCWBcw) 
 and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/5HnXzrMbtVKLCScrdy4CIg) 

* some values are in float - feel free to round them
* “Be pixel perfect” - yes! but mainly make sure colors, size and position are correct. #C271FF is not purple.
For this task, please write an amazing   ` README.md ` 
Interactions note:
* Web pages must switch to the tablet version when the screen width is 768px
* Web pages must switch to the mobile version when the screen width is 576px
* button hover/active:  ` opacity: 0.9 ` 
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` README.md ` 
 Self-paced manual review  Panel footer - Controls 
### 1. Header first
          mandatory         Progress vs Score  Task Body Let’s start by the Homepage:  create the header/hero piece
Here an archive of all assets needed (for the entire project):
* [images_images.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/e62e701b6ce0374555e9.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=a4ee29041508698d7687e06c5e8ee5e0befd8b326890729e0580589e70816b80) 

* [holberton_school-icon.zip](https://holbertonintranet.s3.amazonaws.com/uploads/misc/2020/3/7159d988278de54d859d.zip?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=345600&X-Amz-SignedHeaders=host&X-Amz-Signature=9bc25083a72c4f1c595ac749270dc6d44d4ee2576a43b10b7b16014a59f1c8dc) 

Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/4/13572c3773e26651761e8b4a74b3383300ed9563.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=19f89acb6eb1f3fcdd5e66bcabed43a0a4980736b53fb64680773756ee09586f) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/8854d68a957ef7dc2315.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c1003bd082188a3e497d4d5d74588f44927cd55aa620f5f750f61e3ac54c2d01) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 0-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 2. Carousel of quotes
          mandatory         Progress vs Score  Task Body Create the section “Carousel of quotes”
By using a Carousel component of Bootstrap, create this Carousel of quotes. 
You can have for the moment one quote or twice the same for testing (like example below)
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/8455560f9ac188658195.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ea845e99a0dc876599faf94fd453303b5d65ef834109ed57daa0ffd056ae0d9c) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 1-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 3. Popular videos
          mandatory         Progress vs Score  Task Body Create the section “Most popular tutorials”
By using a Carousel component of Bootstrap, create this Carousel of video cards. 
Reminder:
* Desktop: 4 cards
* Tablet: 2 cards
* Mobile: 1 card
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/4b610dc2d2cc17ceb2f7.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=b94a1ba9099173cc4131d33ffa94ce8fac987febceebb1386064c0316d2b686a) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 2-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 4. Row of smiles
          mandatory         Progress vs Score  Task Body Create the section “Free membership”
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/970efd54768b693bbfac.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3bd382b2d4a9329875a1fa4062dbb07a0e9143912762bff9f3c1360d0e2252ff) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 3-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 5. Latest videos
          mandatory         Progress vs Score  Task Body Create the section “Latest videos”
Copy the block “Most popular tutorials” to “Latest videos”
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 4-homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 6. ... and the footer!
          mandatory         Progress vs Score  Task Body Create the footer
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/739d7cc60098e7ff8f25.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=6bbc54a611572377a0024ef503adf1a0368c4404ef4ccc36cb2495436839d389) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` homepage.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 7. Pricing - header
          mandatory         Progress vs Score  Task Body Now, let’s do the pricing page:  create the header/hero piece
The mobile version must be the same as the Homepage - it’s time to reuse code!
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/ccd30a4d80a990b96740.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=70575dc455790f8b833e3b76cd8d336f376a73ec31f61afb333c6f4154a91adf) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 0-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 8. Prices grid
          mandatory         Progress vs Score  Task Body Create the prices grid
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/0ac3872946a0014e4f99.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=86ca2dadd55711ecdd82828b975e78634e3c35bb47deaa23e960b7eb361b50ba) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/edea8172b9cc0a867237.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=aaa361c9ca1766b3d97149a695b903102c936de06d0802cd0bfa12148f97c797) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 1-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 9. Quotes section
          mandatory         Progress vs Score  Task Body Same as the Homepage,  create the Carousel of quotes
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 2-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 10. FAQ
          mandatory         Progress vs Score  Task Body Create the FAQ grid
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/db8f90e37593a29c1ab6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8b9452b75d0efaa8b17194a2035ad4f0fac3981f02b5dcb74a8b1607849ce7d9) 

Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/eaeb117d40690a451c7b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5162548c8b2dfeced9457cf437f1bb613d384976d1a30f58aef598eb7cf2d6bb) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 3-pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 11. Close the page with a footer
          mandatory         Progress vs Score  Task Body Same as Homepage,  create the footer
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` pricing.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 12. Courses - header
          mandatory         Progress vs Score  Task Body Now, let’s do the courses page:  create the header/hero piece
The mobile version must be the same as the Homepage - it’s time to reuse code!
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/a5ba265af5dd643ad942.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=59962594b80e45457126b8c34805a7181f2a9f7878cea84d85b90b202b172a14) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 0-courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 13. Search filters
          mandatory         Progress vs Score  Task Body Create the search filters section
Dropdown is a nice way to create filters.
For the selected/placeholder value of both dropdown, no need to have dynamic value - static content is totally ok.
Desktop:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/98c0564e59ec5620990e.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d69521adc721b759868c7c9da348eac51336946ea77d458555b69ae137ed802e) 

Tablet/Mobile:
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3627550eccca7958d390.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=423c6a41248cee5b6f29bd1aac60bb7017cfa36e7d7ca4b944e647659dc62ebb) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 1-courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 14. List of result
          mandatory         Progress vs Score  Task Body Create the result section of courses
You can reuse the same cell for testing. Don’t forget to test with odd and even number of cells.
 ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/76b2074f3f6bbd25cdb9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220821%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220821T221730Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=1bbec695468933df33d95f0d6b0a2ec6aa63ebbf52154411cefcf7eafd1a6557) 

 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` 2-courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
### 15. Close the page with a footer
          mandatory         Progress vs Score  Task Body Same as Homepage and Pricing page,  create the footer
 Task URLs  Github information Repo:
* GitHub repository:  ` holbertonschool-smiling-school ` 
* File:  ` courses.html, styles.css ` 
 Self-paced manual review  Panel footer - Controls 
Ready for a  manual review