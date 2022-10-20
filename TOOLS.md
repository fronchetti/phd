There are a plenty of tools that I use as a researcher. In this file, I highlight some of them that are relevant and/or interesting to use in robotics and while doing research.

**Disclaimer:** Some researchers prefer different tools than the ones listed below, and that's perfectly fine. Find the tools that are most appropriate for you and use them.

## ▶️ Writing
- [Overleaf](https://overleaf.com/) - LaTeX is a standard for most researchers on Engineering. Overleaf is a collaborative online editor used to write papers on LaTeX. This is the primary tool I use to write papers in collaboration with my coworkers.
- [Grammarly](https://grammarly.com/) - I am an international student, and my first language is Portuguese. Grammarly helps me with my mistakes while writing in English. Its support is not perfect (e.g., it doesn't work on Overleaf), but tends to help a lot. If English is not your primary language and your advisor can pay for the premium version of Overleaf, ask for it. 

## ▶️ Data Analysis
- [Excel](https://www.microsoft.com/en-us/microsoft-365/excel) - As an user of Linux-based systems, I underestimated for years the power of Excel. Now, it is one of my favorite tools to analyze data and to create visualizations for my papers. I highly recommend Excel for those who want a novice-friendly tool to work with. Look at my replication packages and you will probably find a spreadsheet file somewhere. 
- [R](https://www.r-project.org/) - When Excel can't get the job done, R and Python are my next options. A common scenario for me to use R is when I need to use statistical methods that are not implemented on Excel, but are widely available on R (e.g., [effsize](https://cran.r-project.org/web/packages/effsize/effsize.pdf)). Packages that I commonly use include [tidyr](https://tidyr.tidyverse.org/), [ggplot2](https://ggplot2.tidyverse.org/), [caret](https://topepo.github.io/caret/), [effsize](https://cran.r-project.org/web/packages/effsize/effsize.pdf), [dplyr](https://dplyr.tidyverse.org/), [plotly](https://plotly-r.com/).
- [Python](https://www.python.org/) - For many years Python was my first option to analyze data. Now that I have so much to do, even a few lines of code can be time consuming. Nowadays, I use Python for more complex tasks (e.g., machine learning), although I still love the language. My favorite modules include [pandas](https://pandas.pydata.org/), [numpy](https://numpy.org/), [matplotlib](https://matplotlib.org/), [scikit-learn](https://scikit-learn.org/stable/), [seaborn](https://seaborn.pydata.org/).

## ▶️ Illustration
- [Blender](https://www.blender.org/) - My primary tool for 3D modeling, and it is open-source! I used it to create models for our experiments, apps and papers. For paper illustrations, I love to use Blender's [Freestyle rendering engine](https://docs.blender.org/manual/en/latest/render/freestyle/introduction.html), it transforms the output image on a sketch. For more complex models, a less stressful option is to buy them on [TurboSquid](https://www.turbosquid.com/) (although some models might be too expensive for most researchers).
- [3DS Max](https://www.autodesk.com/products/3ds-max/overview) - A paid alternative to Blender that I use for models we buy from [TurboSquid](https://www.turbosquid.com/) (many designers don't create models for Blender). Students have free access to it through their university email. The Arnold rendering engine is super cool, and that's why I believe 3DS Max is worth mentioning.
- [Draw.io](https://draw.io/) - For diagrams, this website is usually my first choice. I commonly use it to create workflows describing how my methods were executed. The tool is free to use and can easily be connected to Google Drivew.
- [Pixlr](https://pixlr.com/) - For image editing, Pixlr is an online tool that provides the basic functionalities of programs such as Photoshop and GIMP. I use it everytime I need to edit an image (e.g. crop, resize, add border, change brightness, etc).

## ▶️ Game Development
- [Unity Gaming Engine](https://unity.com/) - Mainly used to implement interactive 3D environments that could be used in combination with other toolkits.

## ▶️ Mixed Reality
- [Mixed Reality Toolkit](https://learn.microsoft.com/en-us/windows/mixed-reality/mrtk-unity/) - Used to implement mixed reality applications on Microsoft devices. The primary toolkit for Hololens.

## ▶️ Robot Network Communication
- [ABB Externally Guided Motion](https://library.e.abb.com/public/f05090fae99a4d0ba2ee332e50865791/3HAC073318%20AM%20Externally%20Guided%20Motion%20RW7-en.pdf) - Useful for implementing network communication between ABB robots and external devices. We used this approach to create the communication between Hololens 2 and our industrial robots from ABB. One may argue that we could have used ABB SDKs, but the SDKs didn't provide (at that moment) support for Unity applications, nor gave us the ability to manipulate ABB robots without path planning intervention. For those looking for more information on ABB EGM, I wrote a complete tutorial in our [egm-for-abb-robots](https://github.com/vcuse/egm-for-abb-robots) repository. 

- [ABB PC SDK](https://developercenter.robotstudio.com/pc-sdk) - Probably one of the best approaches to implement network communication between ABB robots and computers. We used the PC SDK to implement our block-based languages through WPF applications in .NET environments. This SDK was widely supported by ABB at the moment. 

## ▶️ Desktop Development
- [Windows Presentation Foundation](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/) - Great framework to implement desktop applications for Windows. We used this on the two-armed and mobile robots experiments. 
