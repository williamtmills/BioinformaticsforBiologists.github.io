## Setting Up a Virtual Computer

One of the major barriers to using bioinformatics to process data is the compatibility of the user's operating system (Windows, MacOS, Linux, etc.) with the packages and tools being used. Additionally, working on shared computers and computing clusters introduces the problem of permissions for reading, writing, and executing code. To avoid these issues and universalize bioinformatic analyses, a virtual computer can be setup on a personal or shared computer that allows users to choose the operating system they desire and ensure permission to read, write, and execute code.

### Download VirtualBox

One of the most popular virtual computer programs is called [VirtualBox](https://virtualbox.org). Installing VirtualBox is straightforward and allows for robust configuration of settings to meet the user's needs.

1. Navigate to [VirtualBox](https://virtualbox.org)'s website.
2. Click the '[Download VirtualBox 6.1](https://www.virtualbox.org/wiki/Downloads)' button.
3. Select the operating system (Windows, OS X (Mac), Linux, Solaris) of the computer you are installing VirtualBox on (not the operating system you will eventually run in VirtualBox).

| Operating System (links download automatically) |
| :-- |
| [Windows](https://download.virtualbox.org/virtualbox/6.1.28/VirtualBox-6.1.28-147628-Win.exe) |
| [OS X (Mac)](https://download.virtualbox.org/virtualbox/6.1.28/VirtualBox-6.1.28-147628-OSX.dmg) |
| [Linux](https://www.virtualbox.org/wiki/Linux_Downloads) (users will have to select Linux distribution prior to download)|
| [Solaris](https://download.virtualbox.org/virtualbox/6.1.28/VirtualBox-6.1.28-147628-SunOS.tar.gz) |
| [Linux](https://download.virtualbox.org/virtualbox/6.1.28/VirtualBox-6.1.28-147628-Solaris.p5p) |

4. Once downloaded, open the package to install it on your computer.

### Download Ubuntu

While there are several options Linux distributions (Oracle, Ubundu, Debian, etc.), Ubuntu is one of the most popular.

1. Navigate to [Ubuntu]()'s website. 
2. Click the 'Download' drop-down menu in the top toolbar and under 'Ubuntu Desktop' click '[20.04 LTS](https://ubuntu.com/download/desktop/thank-you?version=20.04.3&architecture=amd64)' (download will begin automatically).

### Setting up VirtualBox

1. Open the VirtualBox application on your computer.
2. Click 'New'.
3. Fill out the 'Name and operating system' form. 

_Though not required, filling out the forms with the information shown will make the rest of the tutorial more easy to follow._

![alt text](https://github.com/williamtmills/BioinformaticsforBiologists.github.io/blob/gh-pages/nameandoperatingsystem.png?raw=true)

4. Click 'Continue'.
5. Fill out the 'Memory size' form.

_This form allows you to indicate how much of your computer's RAM you will be allocating to the virtual machine (when it is running). How much RAM you allocate to your virtual machine depends on how much RAM your computer has to begin with and how much RAM you will need to execute the programs and packages you will be running on your virtual machine. As a general rule of thumb, do not allocate more than half of your computer's RAM to the virtual machine. If you choose to allocate more than half of your computer's RAM to the virtual machine you may find your computer slowing down when the virtual machine is running and may even crash the virtual machine if the RAM allocated to the virtual machine plus the RAM needed to use your computer exceeds the RAM available on your computer._

_*Mac Users: To view how much RAM is available on your computer, click the apple logo in the tool bar and select 'About this Mac'. Under the 'Overview' tab the computer's RAM is listed next to 'Memory'._

_*Windows Users: To view how much RAM is available on your computer, open the 'System Information' application. The computer's RAM is listed next to 'Installed Physical Memory (RAM)'_

_For example, on a computer with 16 GB of RAM you might allocate 8GB to the virtual machine (for reference, 1 GB = 1024 MB)_

![alt text](https://github.com/williamtmills/BioinformaticsforBiologists.github.io/blob/gh-pages/memorysize.png?raw=true)

6. Click 'Continue'.
7. Fill out the 'Hard disk' form.










| Input | |
| :-- | :-- |
| Name: | Ubuntu |
| Machine Folder: (autopopulated) | /Users/yourusername/VirtualBox VMs |
| Type: | Linux |
| Version: | Ubuntu (64-bit) |

You can use the [editor on GitHub](https://github.com/williamtmills/BioinformaticsforBiologists.github.io/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/williamtmills/BioinformaticsforBiologists.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
