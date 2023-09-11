# Tiny-vGS

Tiny virtual Ground Station (vGS) is a Raspberry Pi based Ground Station meant to get students involved in the intersection of space and ground station virtualization.

*We're still in the process of updating the public GH.

Video of Microsoft 2022 Hackathon:



[![Tiny vGS](https://github.com/FIU-ELF/Tiny-vGS/blob/main/Docs/Images/vid.JPG)](https://www.youtube.com/watch?v=BR16w32aYq8 "Tiny vGS")

# Background

Communities and remote users around the world rely on public weather data sets to have situational awareness of their environment. Virtualized ground stations by the top cloud providers help download weather satellite information at professional sites through Ground Stations as a Service (GSaaS) but what about the every person or unconnected community? The same principles that accerelate deploying professional installations can help them too! In this tutorial, you'll go through the motions to set up a weather satellite ground station using open source software that can run remotely. You'll also leverage cloud resources to create a "GSaaS like" environment to learn about the different tools used in real world virtualized ground stations.

# Mission 

Acquire images from a geostationary satellite ([GOES](/Docs/GOES.md)) using a backyard Ground Station setup. To do this, you'll acquire a ground station kit, use open source software to download an image and use the cloud to visualize system performance. You'll work through the steps to install & virtualize your setup:

1. Plan your installation- Plan your installation by performing a site survey: [Plan your installation](/Docs/PLANNING.md)
3. Plan your BOM & acquire hardware- Use a base BOM, add specific needs for your use case and acquire hardware: [Hardware BOM](/Docs/SAT_HARDWARE_BOM.md)
4. Setup your edge device- Create an edge appliance that allows you to run virtualized radio functions: [Setup your edge](/Docs/EDGE.md)
5. Assemble and install your setup- Let's assemble the kit and install the setup: [Installing the hardware](/Docs/INSTALL.md)
6. Virtualized Radio Functions & Infrastructure as Code- Learn about virtualized radio functions and infrastructure as code: [vRF & IAC](/Docs/IAC_VRF.md)
7. Point your dish & acquire your first image- You are ready to point your dish! Let's try to get an image: [Point your dish](/Docs/POINTING.md)
8. Design and perform trades on a Cloud based solution- Perform trade studies on how to create value added capability with the cloud: [The Cloud](/Docs/CLOUD.md)
9. Microservices- Run microservices to expose metrics to your operations support systems: [Microservices](/Docs/MICRO.md)
10. Operations Support Systems- Implement Operations Support Systems: [OSS](/Docs/OSS.md)
11. Business Support systems- Use cloud Business Support Systems to understand billing: [BSS](/Docs/BSS.md)
12. Content Delivery Network- Create a Content Delivery application for your images: [CDN](/Docs/CDN.md)
13. JSON EventHub description- Learn about the datasets going to EventHubs: [JSON](/Docs/JSON.md)
14. Chatbot- Create a chabot to interact with your data: : [CHAT](/Docs/CHAT.md)

# Future Ideas 

1. Add LEO support
2. GPS NTP time
3. Make the containers more efficient

# Thank you

The open source software community is leveraged heavily in this project. 

1. Thank you Pieter Noordhuis for your hard work with [GOES Tools](https://github.com/pietern/goestools) 
2. Thank you to [Nooelec](https://www.nooelec.com/store/) for creating kits that make GOES more accessible to the every day user
3. Thank you to the team that contributed to this project as part of the 2022 Microsoft Hackathon 




