There are a plenty of tools we can combine to program robots. In this file, I highlight some tools that are relevant and/or interesting to use in robotics.
Not all of them are strictly related to robots, but some could be used on them.

## ▶️ Game Development
- [Unity Gaming Engine](https://unity.com/) - Mainly used to implement interactive 3D environments that could be used in combination with other toolkits.


## ▶️ Mixed Reality
- [Mixed Reality Toolkit](https://learn.microsoft.com/en-us/windows/mixed-reality/mrtk-unity/) - Used to implement mixed reality applications on Microsoft devices. The primary toolkit for Hololens.

## ▶️ Robot Network Communication
- [ABB Externally Guided Motion](https://library.e.abb.com/public/f05090fae99a4d0ba2ee332e50865791/3HAC073318%20AM%20Externally%20Guided%20Motion%20RW7-en.pdf) - Useful for implementing direct network communication between ABB robots and devices with low support. We used this approach to create the communication between Hololens 2 and our industrial robots from ABB. One may argue that we could have used ABB SDKs, but the SDKs didn't provide (at that moment) support for Unity applications. 
- [ABB PC SDK](https://developercenter.robotstudio.com/pc-sdk) - Probably one of the best approaches to implement network communication between ABB robots and computers. We used the PC SDK to implement our block-based languages through WPF applications in .NET environments. This SDK was widely supported by ABB at the moment. 

## ▶️ 3D Modeling
- [Blender](https://www.blender.org/) - My primary tool for 3D modeling. I used it to create models for our experiments, apps and papers. For paper illustrations, I love to use Blender's [Freestyle rendering engine](https://docs.blender.org/manual/en/latest/render/freestyle/introduction.html), it transforms the output image on a sketch. For more complex models, a less stressful option is to buy them on [TurboSquid](https://www.turbosquid.com/) (although some models might be too expensive for most researchers).

## ▶️ Desktop Development
- [Windows Presentation Foundation](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/) - Great framework to implement desktop applications for Windows. We used this on the two-armed and mobile robots experiments. 

## ▶️ Writing
- [Overleaf](https://overleaf.com/) - LaTeX is a standard for most researchers on Engineering. Overleaf is a collaborative online editor used to write papers on LaTeX. This is the primary tool I use to write papers in collaboration with my coworkers.
- [Grammarly](https://grammarly.com/) - I am an international student, and my first language is Portuguese. Grammarly helps me with my mistakes while writing in English. Its support is not perfect (e.g., it doesn't work on Overleaf), but tends to help a lot. If English is not your primary language and your advisor can pay for the premium version of Overleaf, ask for it. 
