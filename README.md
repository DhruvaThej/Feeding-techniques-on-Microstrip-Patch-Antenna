# Feeding-techniques-on-Microstrip-Patch-Antenna
# About
One of the major requirements of modern communication systems is compactness, which has led to miniaturization of antenna size. This has become much easier due to the advent of Microstrip Patch Antennas (MPAs), as they are smaller in size, easy to fabricate, and low in cost. These MPAs also eliminate feed radiation and provide high bandwidth. There are different types of feed mechanisms. This work provides a detailed analysis of feeding techniques for Rectangular Microstrip Patch Antenna (RMPA). A microstrip patch antenna is a planar directional antenna in which a metal patch is placed on top of a dielectric substrate, which is placed on top of a metal ground plane. The power transfer between a source and an antenna is done through a feed line. The feed connects the antenna with the radio transmitter or receiver. So the impedance patch must be matched with the impedance of the feed line. To avoid signal reflection which consumes power, impedance must be matched. In general, the characteristic impedance of a transmission line is 50 ohms. By the maximum power transfer theorem, the patch antenna should be fed at a point where the input impedance is 50 ohms for maximum input power. Various feeding techniques such as Edge feed, Inset feed, coaxial feed, and Aperture Coupled Feed were applied to RMPA and impedance matching characteristics were observed. Output parameters like Gain, return loss, VSWR, and bandwidth are compared among the feeding techniques. A design rule has also been formulated and presented the performance of the proposed design. An antenna of the same dimensions was used to analyze different feed techniques. An approximate formula is introduced to describe the resonance frequency that is then implemented in the design of notch width for inset-fed antennas to achieve better impedance matching. The designed patch antenna is operated at a 10 GHz frequency. Rogers RT/duroid 5880 is used as substrate material, which has a dielectric constant of 2.2 and a height of 0.1588cm. The design of the patch antenna was simulated using ANSYS electronics 2022R2 HFSS tool


# Introduction

This study is based on Rectangular Microstrip Patch Antennas (RMPA), which are used in advanced communication technologies due to their small size, ease of fabrication, and low cost. These are operated at high frequencies and used in applications like satellite communications, aircraft, mobile radios, and many other wireless systems. The MPA has two conductors separated by a dielectric material i.e., substrate. The upper conductor is known as a patch and lower conductor is a ground plane. There are different types of patch antennas square, circular, rectangular, and triangular patch antennas. The operation of MPAs is based on the concept of fringing fields, which are produced due to different sizes of patches and ground plane. These fringing fields influence the resonant frequency. In this case, the resonant frequency considered is 10 GHz. The basic equations for designing a rectangular patch antenna are given below. After obtaining the basic dimensions for RMPA, the implementation of feeding techniques is shown. Various feeding techniques such as Edge feed, Inset feed, Coaxial feed, and Aperture Coupled Feed were applied to RMPA and impedance matching characteristics were observed. For Edge-Fed RMPA, a quarter-wave transformer transmission line was used as a transmission line. The feed of 50Ω was directly connected to the patch in the inset feed RMPA. In coaxial-fed RMPA n-type coaxial connector was used for impedance matching. The same substrate is used for the upper and lower layers of Aperture fed RMPA. The results of simulation for different feeding techniques are observed and compared.

# Edge fed RMPA
This method is simple, and we can easily analyze it, and it can be easily manufactured. This antenna can be impedance-matched by doing some Structural modifications, this model does not require any modification in the geometry of the patch. The design of edge fed rectangular patch antenna is shown below

<h1 align="center"> 
  
![hh](https://github.com/DhruvaThej/Feeding-techniques-on-Microstrip-Patch-Antenna/assets/156312231/8bac6ecd-e230-41c1-9e3d-7baf0c5299ce)

# Inset fed RMPA
 The inset-fed mechanism involves the slot cuttings in the patch antenna. The impedance of the patch is high at the edges, it decreases as we move to the center of the patch. As the current at the center is high, the minimum impedance is at the center of the patch. So as the impedance decreases to the center there will be a point where it has 50Ω impedance. In the inset-fed method, the slot cutting is done once we identify this point. In inset fed, there is no need for any transmission line as the feed is given to the point where the impedance is matched.
 
 <h1 align="center">
   
 ![3](https://github.com/DhruvaThej/Feeding-techniques-on-Microstrip-Patch-Antenna/assets/156312231/953a28ba-11c1-413b-8b9d-29dd553bd156)

 # Coaxial fed RMPA
 
 In coaxial feed RMPA, the feed is given directly to the point where the impedance is 50Ω. Coaxial feed is widely used, and it is an effective method.
 
 <h1 align="center">
   
 ![4](https://github.com/DhruvaThej/Feeding-techniques-on-Microstrip-Patch-Antenna/assets/156312231/dce76da5-2582-4523-866e-5627cdd08133)

 # Aperture-fed RMPA

 In aperture-fed RMPA the ground plane is in between two substrates; the patch is above substrate 1, and the feed is below substrate 2. In this method, the ground plane is slotted to obtain resonant frequency e 1, and the feed is below substrate 2. In this method, the ground plane is slotted to obtain resonant frequency i.e., 10GHz.
 
 <h1 align="center">
   
 ![5](https://github.com/DhruvaThej/Feeding-techniques-on-Microstrip-Patch-Antenna/assets/156312231/fc6e10a6-efbc-4f97-81b0-47927933d8af)

 # results


  <h1 align="center">

![ssss](https://github.com/DhruvaThej/Feeding-techniques-on-Microstrip-Patch-Antenna/assets/156312231/a725ae7e-8758-4113-9ee9-259a25b08b42)

