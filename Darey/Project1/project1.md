# WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS

**Welcome to your first PBL Project!** I hope you're excited to dive into the hands-on experience. There's a lot of projects ahead, so let's get started without delay.

As you begin your journey in DevOps, you'll soon realize that your work as a DevOps engineer revolves around software, websites, and applications. There are various technology stacks that make different solutions possible, known as WEB STACKS. Examples include LAMP, LEMP, MEAN, and MERN stacks. Throughout your journey, you'll need to understand and implement these technology stacks. Let's take a closer look at what a Technology stack is.

## What is a Technology stack?

A technology stack is a set of frameworks and tools used to develop a software product. These frameworks and tools are specifically chosen to work together, creating a well-functioning software. They are acronyms for individual technologies used together for a specific technology product. Examples include:

- **LAMP** (Linux, Apache, MySQL, PHP or Python, or Perl)
- **LEMP** (Linux, Nginx, MySQL, PHP or Python, or Perl)
- **MERN** (MongoDB, ExpressJS, ReactJS, NodeJS)
- **MEAN** (MongoDB, ExpressJS, AngularJS, NodeJS)

:::note
At the beginning, some tasks may seem unfamiliar, and you might feel like you're just copying and pasting. That's okay! The goal is to let concepts sink into your subconscious, building up your skills. Keep an eye out for traps that may require troubleshooting during your project implementations.
:::

**After successfully completing PBL projects 1 to 4, you'll be able to:**

- Gain confidence in using the Linux Terminal.
- Deepen your understanding of Web Stacks and distinguish between different Web Technology stacks like LAMP, LEMP, MEAN, and MERN stacks.
- Develop solid Linux administration skills in storage management, NFS, troubleshooting, and basic networking.
- Acquire basic knowledge of the AWS platform and components used to host websites with various Web stacks.

Working with Linux often means dealing with tasks beyond your current knowledge level. You'll encounter challenges you haven't faced before, but with the help of Google search, you can accomplish a lot. Constructing effective search queries and navigating search results are essential skills to develop.

---

**Side Self-Study:**

- Google search and document your findings on Software Development Life Cycle (SDLC).
- Understand what LAMP stack means through another Google search.
- Read about 'chmod' and 'chown' commands in Linux to grasp how file and directory access and ownership work.
- Learn the differences between TCP and UDP and list down commonly used ports in Web (http, https, ssh, telnet, ftp, sftp, telnet).
- Familiarize yourself with basic text editing in the Vi (Vim) editor and practice.

As a beginner, it's helpful to set up your learning workspace. Check out the provided video series on Windows installation.

- [windows-installation:Part1](https://youtu.be/R-qcpehB5HY)
- [windows-installation:Part2](https://youtu.be/jsNIlK5s6pI)

---

### Step 0 : Preparing Prerequisites

To successfully complete this project, you'll require an AWS account and a virtual server running the Ubuntu Server OS. [AWS](https://aws.amazon.com/), being the largest Cloud Service Provider, offers a free tier account that we'll use for our projects.

For now, don't delve too deeply into AWS specifics; we'll have a dedicated introduction and configuration projects later in the course. Currently, all you need to understand is that AWS provides a free virtual server known as [**EC2 (Elastic Compute Cloud)**](https://aws.amazon.com/ec2/features/) that suits our requirements.

Setting up a new EC2 instance (a virtual server) is a straightforward process, requiring just a few clicks. You can either watch the videos provided below for a step-by-step guide:

- [AWS Account Setup and Provisioning an Ubuntu Server](https://www.youtube.com/watch?v=xxKuB9kJoYM&list=PLtPuNR8I4TvkwU7Zu0l0G_uwtSUXLckvh&index=6)
- [Connecting to Your EC2 Instance](https://www.youtube.com/watch?v=TxT6PNJts-s&list=PLtPuNR8I4TvkwU7Zu0l0G_uwtSUXLckvh&index=7)

Alternatively, you can follow the instructions outlined below.

1. Register a new AWS account following [this instruction](https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/).
