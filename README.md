# __OSI(Open System Interconnetion)__

# Introduction

1. The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network. It was the first standard model for network communications, adopted by all major computer and telecommunication companies in the early 1980s.

2. The modern Internet is not based on OSI, later we got an updated one and simple one that is TCP/IP model. However, the OSI 7-layer model is still widely used, as it helps isolate and troubleshoot networking problems.

3. OSI was introduced in 1983 by major companies and was taken by ISO in 1984.


# Beneficts Of OSI :

1. Divides the network communication process into layers to be easier to troubleshoot.

2. Allows multiple-vendor development through standardization of network components.

3. Layer separation makes changes in one layer do not affect other layers.

4. Various types of network hardware and software can communicate, Layers can interact with each other.

# OSI Model

![Image](https://cdn.educba.com/academy/wp-content/uploads/2019/07/OSI-Model.png)


# OSI Model Explained :

Let us learn about layers one by one in the above image

## Application Layer :

1. User interface to lower layers, Preparation of data for each service.

2. End-to-end communication on both sides, software applications reside in it
Sends requests and receives.

![Image](https://cf-assets.www.cloudflare.com/slt3lc6tev37/koKt5UKczRq47xJsexfBV/c1e1b2ab237063354915d16072157bac/7-application-layer.svg)

## Presentation Layer :

1. Responsible for common representation of data between source and destination, provides transformation of data.

2. Supports standardized application interface
Coding of data syntax 
Data encryption/decryption
Data compression/decompression

![Image](https://cf-assets.www.cloudflare.com/slt3lc6tev37/60dPoRIz0Es5TjDDncEp2M/7ad742131addcbe5dc6baa16a93bf189/6-presentation-layer.svg)


## Session Layer :
1. It helps in Establishing Session, Managing Session, Controlling Session, Terminating Session.

2. Making sure the connection is active during session, securing the connection, dialogue synchronization, checking for connection failure
Reconnecting if connection cuts off, terminating communication.

![Image](https://cf-assets.www.cloudflare.com/slt3lc6tev37/6jFRnaZSuIMoUzSotZXYbG/cc7a47d2b3f8d3e77b9ffbdb8b8d5280/5-session-layer.svg)

## Transport Layer :

1. Transport Layer helps in dividing data into small fragments that can be transmitted over network, ifferent networks have different Maximum Transmission Unit (MTU).

2. MTU defines maximum size of one data piece carried through the network.

3. Data is being divided and transmitted to recipient via transport layer, the MTU size is being acknowledged by transport layer.

4. MTU acknowledgment is during discovering routine and while establishing connection with the recipient.

![image](https://cf-assets.www.cloudflare.com/slt3lc6tev37/1MGbIKcfXgTjXgW0KE93xK/64b5aa0b8ebfb14d5f5124867be92f94/4-transport-layer.svg)

## Network layer :

1. Network layer organize data into packets, responsible of end-to-end addressing and routing, identifies unique logical address for machines.

2. Selects the best path for destination, routers work in the network layer, Performs fragmentation if segmentation is not enough,  receives the segments of data from Transport layer.

3. Finds a route for data to be delivered to the receiver
Routes may differ because it is being determined based on the following:
    1. Network overload
    2. Quality of Service (QoS)
    3. Cost of alternative routes
    4. Delivery priorities


![Image](https://cf-assets.www.cloudflare.com/slt3lc6tev37/76JgEjycZl12c90UByKfJA/d6578bcd7b151c489e61f42227a45713/3-network-layer.svg)

## Data Link Layer :

1. Data link layer helps in, Reliable data transfer across physical link, Responsible of physical addressing, Organize the data into frames, Puts frames on the physical medium.

2. Receives data packages from network layer , Convert data into the frames including the following, Data packages, Sender and the receiver physical addresses, Error checking and control information.


![Image](https://cf-assets.www.cloudflare.com/slt3lc6tev37/3MR4mPOwaos80t1annw7BG/8ea1c59ccfa1baf6e9738773daa30450/2-data-link-layer.svg)

## Physical Layer :


1. Transmits  bit stream over the physical link, Sends data signals to media and receives it, Adapts to the transmission media through, Cables, Copper (Coaxial, Twisted Pair),Fiber Optic (Single Mode, Multi Mode), Wireless.

2. Responsible for the representation of 1s and 0s
NIC, Hub, and Repeater work in Physical Layer.

![Image](https://www.siemxpert.com/blog/wp-content/uploads/2021/06/OSI-MODEL-physical-layer-1024x342.png)


## Conclusion :

The main concept of OSI is the process of communication between two end points in a telecommunication network can be divided into seven distinct layers, with layer one positioned at the bottom of the layer stack and layer seven at the top.


![Image](https://www.freecodecamp.org/news/content/images/2021/10/osi-model-layers.png)

## References :

* cloudflare.com
* wallaram.com
* scaler.com