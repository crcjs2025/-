<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Step 1: Enable GitHub Pages

_Welcome to GitHub Pages and Jekyll :tada:!_

The first step is to enable GitHub Pages on this [repository](https://docs.github.com/en/get-started/quickstart/github-glossary#repository). When you enable GitHub Pages on a repository, GitHub takes the content that's on the main branch and publishes a website based on its contents.

### :keyboard: Activity: Enable GitHub Pages

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
1. Under your repository name, click **Settings**.
1. Click **Pages** in the **Code and automation** section.
1. Ensure "Deploy from a branch" is selected from the **Source** drop-down menu, and then select `main` from the **Branch** drop-down menu.
1. Click the **Save** button.
1. Wait about _one minute_ then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.
   > Turning on GitHub Pages creates a deployment of your repository. GitHub Actions may take up to a minute to respond while waiting for the deployment. Future steps will be about 20 seconds; this step is slower.
   > **Note**: In the **Pages** of **Settings**, the **Visit site** button will appear at the top. Click the button to see your GitHub Pages site.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
ซีอาซีเจเล็ก แปลเพิ่มภาษาไทย
หน้า GitHub
สร้างไซต์หรือบล็อกจากที่เก็บ GitHub ของคุณด้วย GitHub Pages

ยินดีต้อนรับ
ด้วย GitHub Pages คุณสามารถโฮสต์บล็อกโครงการ เอกสารประกอบ ประวัติย่อ พอร์ตโฟลิโอ หรือเนื้อหาคงที่อื่นๆ ที่คุณต้องการได้ คลังข้อมูล GitHub ของคุณจะกลายเป็นเว็บไซต์ของตัวเองได้อย่างง่ายดาย ในหลักสูตรนี้ เราจะแสดงวิธีตั้งค่าเว็บไซต์หรือบล็อกของคุณเองโดยใช้ GitHub Pages

เหมาะสำหรับใคร : ผู้เริ่มต้น นักศึกษา ผู้ดูแลโครงการ และธุรกิจขนาดเล็ก
สิ่งที่คุณจะได้เรียนรู้ : วิธีสร้างไซต์ GitHub Pages
สิ่งที่คุณจะสร้าง : เราจะสร้างไซต์ GitHub Pages ง่ายๆ พร้อมบล็อก เราจะใช้Jekyllซึ่งเป็นเครื่องมือสร้างไซต์แบบคงที่
ข้อกำหนดเบื้องต้น : หากคุณต้องการเรียนรู้เกี่ยวกับสาขา คอมมิต และคำขอการดึง โปรดศึกษาบทนำสู่ GitHubก่อน
ระยะเวลา : หลักสูตรนี้ใช้เวลาเรียนน้อยกว่า 1 ชั่วโมง
ในหลักสูตรนี้คุณจะ:

เปิดใช้งาน GitHub Pages
กำหนดค่าเว็บไซต์ของคุณ
ปรับแต่งหน้าแรกของคุณ
สร้างโพสต์บล็อก
รวมคำขอการดึงของคุณ
วิธีการเริ่มต้นคอร์สนี้
เริ่มหลักสูตร

คลิกขวาที่เริ่มหลักสูตรและเปิดลิงก์ในแท็บใหม่
ในแท็บใหม่ ข้อความเตือนส่วนใหญ่จะกรอกให้คุณโดยอัตโนมัติ
สำหรับเจ้าของ เลือกบัญชีส่วนตัวหรือองค์กรที่จะโฮสต์ที่เก็บข้อมูล
เราขอแนะนำให้สร้างที่เก็บข้อมูลสาธารณะ เนื่องจากที่เก็บข้อมูลส่วนตัวจะใช้ Actions Minutes
เลื่อนลงไปและคลิก ปุ่ม สร้างที่เก็บข้อมูลที่ด้านล่างของแบบฟอร์ม
หลังจากสร้างที่เก็บข้อมูลใหม่แล้ว ให้รอประมาณ 20 วินาที จากนั้นรีเฟรชหน้า ทำตามคำแนะนำทีละขั้นตอนใน README ของที่เก็บข้อมูลใหม่
