<div id="fa" dir="rtl">

# پروژه طراحی شبکه

این مخزن شامل تمامی فایل‌ها و مستندات لازم برای یک پروژه جامع طراحی شبکه است. این پروژه شامل نمودارهای شبکه، آدرس‌دهی IP، و جزئیات زیرشبکه‌بندی است که به دقت برای برآورده کردن نیازهای خاص طراحی شده است.

## مرور پروژه

هدف این پروژه طراحی یک شبکه است که چندین شعبه را پوشش دهد و اطمینان از آدرس‌دهی IP کارآمد، زیرشبکه‌بندی، و پیاده‌سازی مناسب خدمات شبکه را فراهم کند. شبکه برای پشتیبانی از حداکثر 250 کاربر متصل از طریق Wi-Fi و چندین سرور واقع در سرور فارم‌های هر شعبه طراحی شده است.

## فایل‌های موجود در این مخزن

- **Project Guide.pdf**: این سند راهنمایی‌ها و نیازمندی‌های پروژه طراحی شبکه را ارائه می‌دهد. مراحل لازم، تنظیمات آدرس IP، طرح‌های زیرشبکه‌بندی و سایر جزئیات مهم مورد نیاز برای تکمیل موفقیت‌آمیز پروژه را شرح می‌دهد.
- **pro5.pdf**: این گزارش نهایی ارائه شده برای پروژه است. شامل اطلاعات دقیق زیرشبکه‌بندی، محدوده‌های آدرس IP و تنظیمات خاص برای هر شعبه در شبکه است.
- **projectfinal.pkt**: این فایل حاوی نمودار شبکه‌ای است که با استفاده از Cisco Packet Tracer ایجاد شده است. طراحی شبکه را به صورت تصویری نمایش می‌دهد، شامل تمام شعبه‌ها، روترها، سوئیچ‌ها و سایر دستگاه‌های شبکه.

## جزئیات طراحی شبکه

### شعب و زیرشبکه‌بندی

- **شعبه اصفهان**
  - آدرس شبکه: 172.16.208.0/20
  - محدوده IP: 172.16.208.0 - 172.16.223.255
  - ماسک زیرشبکه: 255.255.240.0

- **شعبه بوشهر**
  - آدرس شبکه: 192.168.64.0/18
  - محدوده IP: 192.168.64.0 - 192.168.127.255
  - ماسک زیرشبکه: 255.255.192.0
  - چندین زیرشبکه برای بخش‌های مختلف، که استفاده کارآمد و سازماندهی IP را تضمین می‌کند.

- **شعبه تبریز**
  - آدرس شبکه: 172.16.240.0/20
  - محدوده IP: 172.16.240.0 - 172.16.255.255
  - ماسک زیرشبکه: 255.255.240.0

- **شعبه شیراز**
  - آدرس شبکه: 172.16.192.0/20
  - محدوده IP: 172.16.192.0 - 172.16.207.255
  - ماسک زیرشبکه: 255.255.240.0

### نیازمندی‌های کلیدی

1. **زیرشبکه‌بندی**: از آدرس‌های خصوصی کلاس C استفاده می‌شود، با زیرشبکه‌های خاصی که برای بخش‌ها و عملکردهای مختلف ایجاد شده‌اند.
2. **ظرفیت کاربر**: شبکه تا 250 کاربر متصل از طریق Wi-Fi در هر شعبه را پشتیبانی می‌کند.
3. **سرور فارم‌ها**: هر شعبه دارای یک سرور فارم با حداقل 360 آدرس IP اختصاص یافته است.
4. **خلاصه‌سازی IP**: خلاصه‌سازی بر روی روترها پیاده‌سازی شده است تا اطمینان حاصل شود که مسیریابی با حداقل جدول‌های مسیریابی انجام می‌شود.

### ویژگی‌های اختیاری

- VLANها برای دسترسی کارکنان IT به تمامی سرورها.
- دسترسی محدود به اینترنت برای برخی از سرورها از طریق پورت‌های خاص (مانند پورت 80).

## نحوه استفاده

1. **بررسی راهنمای پروژه**: نیازمندی‌ها و راهنمایی‌های شرح داده شده در `Project Guide.pdf` را درک کنید.
2. **بررسی گزارش نهایی**: `pro5.pdf` اطلاعات دقیقی در مورد طرح‌های زیرشبکه‌بندی و آدرس‌دهی IP ارائه می‌دهد.
3. **باز کردن نمودار شبکه**: از Cisco Packet Tracer برای باز کردن فایل `projectfinal.pkt` و مشاهده طراحی شبکه استفاده کنید.

## نتیجه‌گیری

این پروژه یک رویکرد جامع برای طراحی یک شبکه مقیاس‌پذیر و کارآمد برای چندین شعبه را نشان می‌دهد. با پیروی از راهنمایی‌های ارائه شده و بررسی گزارش نهایی، می‌توانید به نکات مفیدی در زمینه طراحی و پیاده‌سازی شبکه دست یابید.

با خیال راحت فایل‌ها را بررسی کنید و از آنها به عنوان مرجع برای پروژه‌های مشابه استفاده کنید.

## مجوز

این پروژه تحت مجوز MIT است. برای جزئیات به فایل LICENSE مراجعه کنید.

</div>

<div id="en" dir="ltr" style="display:none;">

# Network Design Project

This repository contains all the necessary files and documentation for a comprehensive network design project. The project includes network diagrams, IP addressing, and subnetting details, all meticulously crafted to meet specific requirements.

## Project Overview

The objective of this project is to design a network that spans multiple branches, ensuring efficient IP addressing, subnetting, and proper implementation of network services. The network is designed to support up to 250 users connected via Wi-Fi and several servers located in the server farms of each branch.

## Files in this Repository

- **Project Guide.pdf**: This document provides the guidelines and requirements for the network design project. It outlines the necessary steps, IP address configurations, subnetting schemes, and other crucial details needed for the successful completion of the project.
- **pro5.pdf**: This is the final report submitted for the project. It includes detailed subnetting information, IP address ranges, and specific configurations for each branch in the network.
- **projectfinal.pkt**: This file contains the network diagram created using Cisco Packet Tracer. It visually represents the network design, including all branches, routers, switches, and other network devices.

## Network Design Details

### Branches and Subnetting

- **Esfahan Branch**
  - Network Address: 172.16.208.0/20
  - IP Range: 172.16.208.0 - 172.16.223.255
  - Subnet Mask: 255.255.240.0

- **Bushehr Branch**
  - Network Address: 192.168.64.0/18
  - IP Range: 192.168.64.0 - 192.168.127.255
  - Subnet Mask: 255.255.192.0

- **Tabriz Branch**
  - Network Address: 172.16.240.0/20
  - IP Range: 172.16.240.0 - 172.16.255.255
  - Subnet Mask: 255.255.240.0

- **Shiraz Branch**
  - Network Address: 172.16.192.0/20
  - IP Range: 172.16.192.0 - 172.16.207.255
  - Subnet Mask: 255.255.240.0

### Key Requirements

1. **Subnetting**: Class C private IP addresses are used, with specific subnets created for different departments and functions.
2. **User Capacity**: The network supports up to 250 users connected via Wi-Fi in each branch.
3. **Server Farms**: Each branch has a server farm with at least 360 IP addresses allocated.
4. **IP Summarization**: Summarization is implemented on routers to ensure efficient routing with minimal routing tables.

### Optional Features

- VLANs for IT staff to access all servers.
- Limited internet access for certain servers via specific ports (e.g., port 80).

## How to Use

1. **Review the Project Guide**: Understand the requirements and guidelines outlined in `Project Guide.pdf`.
2. **Examine the Final Report**: `pro5.pdf` provides detailed information on the subnetting and IP addressing schemes used.
3. **Open the Network Diagram**: Use Cisco Packet Tracer to open the `projectfinal.pkt` file and visualize the network design.

## Conclusion

This project demonstrates a comprehensive approach to designing a scalable and efficient network for multiple branches. By following the provided guidelines and examining the final report, you can gain insights into effective network design and implementation strategies.

Feel free to explore the files and use them as a reference for similar projects.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

</div>

<script>
    function switchLanguage(lang) {
        document.getElementById('fa').style.display = lang === 'fa' ? 'block' : 'none';
        document.getElementById('en').style.display = lang === 'en' ? 'block' : 'none';
    }
</script>

<div>
    <button onclick="switchLanguage('fa')">فارسی</button>
    <button onclick="switchLanguage('en')">English</button>
</div>
