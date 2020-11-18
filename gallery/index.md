---
title: Team
---

# <i class="fas fa-users"></i>ผลงานของเรา

## ผลงานเว็บไซต์ 

{% capture largecards %}
{%
  include card.html
  size="large"
  link=tef-net.com
  image="images/BG1.jpg"
  heading="[www.TEF-Net.com](tef-net.com)"
  row1="เว็บไซต์โครงการทุนการศึกษาเพื่อน้อง (Thailand Educational Funding Network: TEF-Net) จัดทำโดย EZwebpage"
%}
{% endcapture %}

{% include centerer.html html=largecards %}

## ตัวอย่างรูปภาพสินค้าพร้อมคำอธิบาย Product gallery with description

{% capture mediumcards %}
{%
  include card.html
  size="medium"
  image="images/Packages_EZmini.jpg"
  heading="EZ Mini"
  row1="แพ็คเกจ EZ Mini เหมาะสำหรับเว็บไซต์ขนาดเล็ก ความยาวไม่เกิน 1 หน้า และมีรูปภาพน้อยกว่า 10 รูป"
%}
{%
  include card.html
  size="medium"
  image="images/Packages_EZpro.jpg"
  heading="EZ Pro"
  row1="แพ็คเกจ EZ Pro เหมาะสำหรับเว็บไซต์ขนาดกลาง ความยาวไม่เกิน 4 หน้า และมีรูปภาพน้อยกว่า 30 รูป"
%}
{%
  include card.html
  size="medium"
  image="images/Packages_EZpromax.jpg"
  heading="EZ Pro Max"
  row1="แพ็คเกจ EZ Pro Max เหมาะสำหรับเว็บไซต์ขนาดใหญ่ ความยาวเกิน 4 หน้า หรือมีรูปภาพมากกว่า 30 รูป"
%}
{% endcapture %}

{% include centerer.html html=mediumcards %}



## ตัวอย่างอัลบั้มรูปภาพ Gallery example

{%
  include gallery.html
  fit="false"
  image1="images/IMG_6981.JPG"
  image2="images/IMG_6978.JPG"
  image3="images/IMG_6976.JPG"
  image4="images/BG.jpg"
  image5="images/IMG_6980.JPG"
  image6="images/IMG_7104.JPG"
  image7="images/IMG_6944.JPG"
  image8="images/IMG_6975.jpg"
  image9="images/IMG_7105.JPG"
  image10="images/IMG_7103.JPG"
  image11="images/IMG_6849.jpg"
  image12="images/house.JPG"
%}
